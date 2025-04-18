<%"---"%>
tags: Semester-6/seminar/paper 
aliases: 
  - {{title | replace(":", "") | replace("#", "") | replace("^", "") | replace("|", "") | replace("\[", "") | replace("\]", "") | replace("\\", "") | replace("/", "")}}
  - {{citekey}}
<%"---"%>

<%*
	let title = "{{title | replace(':', '') | replace('#', '') | replace('^', '') | replace('|', '') | replace('\[', '') | replace('\]', '') | replace('\\', '') | replace('/', '')}}";
	let date = tp.date.now("YYYY-MM-DD");
	await tp.file.rename(`${date} ${title}`);
_%>

> [!link]
> {{itemType}} {{pdfZoteroLink}}

> [!cite]
> {{citekey}}
> [https://doi.org/{{DOI}}](https://doi.org/{{DOI}})

> [!authors]
> {{authors}}{{directors}}

{% set uniqueTags = [] %}
{%- for annotation in annotations -%}
  {%- for tag in annotation.tags -%}
    {%- if tag.tag not in uniqueTags -%}
      {%- set uniqueTags = uniqueTags.concat([tag.tag]) -%}
    {%- endif -%}
  {%- endfor -%}
{%- endfor -%}

> [!keywords]
> **Tags:** {%- for tag in uniqueTags %} {{ tag }}{% if not loop.last %}, {% endif %}{% endfor %}

> [!hypothesis]-
> hypothesis:: 

> [!methodology]-
> methodology:: 

> [!result]- Result(s)
> results::

> [!summary]- Summary of Key Points
> summary:: 


---
## Notes
{% set currentPage = null %}
{% for annotation in annotations %}
{% if currentPage != annotation.page %}
### 📍 Page {{ annotation.page }}
{% set currentPage = annotation.page %}
{% endif -%}

{% if annotation.annotatedText -%}
> <mark class="hltr-{{ annotation.colorCategory | lower }}">{{ annotation.annotatedText | escape }}</mark> [🔗](zotero://open-pdf/library/items/{{ annotation.attachment.itemKey }}?page={{ annotation.page }}&annotation={{ annotation.id }})
{% endif -%}

{% if annotation.imageRelativePath -%}
![[{{ annotation.imageRelativePath }}]]
{% endif -%}

{% if annotation.comment -%}
**💬** {{ annotation.comment }}
{% endif -%}

{% if annotation.tags and annotation.tags.length -%}
**🏷️** {% for tag in annotation.tags %}| {{ tag.tag }} | {% endfor %}
{% endif -%}
{% endfor %}
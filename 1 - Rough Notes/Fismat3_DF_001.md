Source: [<font color="#FFBB64">1. Sifat Mekanik Material</font>](https://drive.google.com/file/d/1HNdWwKsBuEpLuzVJthCc3_8CuJmntGjN/view?usp=sharing)
Handbook: 
- [<font color="#FFBB64">Phase Diagrams in Materials Science</font>](https://drive.google.com/file/d/1dYiZbSXwkrHCs2UByYot6I4opZrNcWGE/view?usp=sharing)
- [<font color="#FFBB64">Phase Transformations in Metals and Alloys</font>](https://drive.google.com/file/d/1yvLY3LNnATM0ZEHqZGymbyhU_EvJRJR_/view?usp=sharing)

#DCFFB7 #FF6868 #FFBB64 #FFEAA7 #FisikaMaterial3
***

# Sifat Mekanik Material
<div style="text-align: center;"> <img src="https://i.imgur.com/2MeMvLQ.png" alt="Mechanical Properties"> </div>

# <font color="#DCFFB7">Tensile Test</font>
<p align="justify">Tensile strength is the <mark class="hltr-purple">maximum stress</mark> a material can bear before breaking when it is allowed to be stretched or pulled. It is a crucial property in material testing, as it provides valuable information about a material's mechanical behavior under static, axial loading. The purpose of tensile strength testing is to <mark class="hltr-purple">determine the material's tensile properties</mark>, such as yield point, elastic limit, percent elongation, elastic modulus, and toughness.</p>
<p align="justify">The principal behind tensile strength testing involves <mark class="hltr-purple">applying a force</mark> to a material sample while <mark class="hltr-purple">measuring its deformation</mark>. The stress is calculated as the amount of force divided by the original cross-sectional area of the sample. The stress-strain curve is then plotted, which shows the relationship between the applied stress and the resulting deformation. The tensile strength is determined as the maximum stress observed from the stress-strain curve</p>

## <font color="#FF6868">A. Loading Type</font>
Materials can experience several types of loading, including:
- Tension
- Compression
- Shear
- Bending
- Torsion

![Stress Type|400](https://upload.wikimedia.org/wikipedia/commons/2/2a/Different-types-of-mechanical-stress_EN.svg)

## <font color="#FF6868">B. Stress-Strain Concept</font>
To be able to compare the tensile strength of materials with different dimensions, the <mark class="hltr-purple">load is calculated per unit area</mark>

### <font color="#FFBB64">Stress</font>
$$Engineering \;Stress: \sigma = \frac{F}{A_o}$$
$$True \;Stress: \sigma_{t}= \frac{F}{A}$$
$$\sigma_{t} = \frac{F}{A}=\frac{F\times{A_o}}{A_o\times{A}}=\frac{F\times{L}}{A_{o}\times{L_o}}=\sigma(1+\epsilon)$$
$F$  : Load applied
$A_o$ : Cross sectional area
$A$  : Load acting on cross-sectional area

<p align="justify"><mark class="hltr-purple">Engineering stress</mark> is the applied load divided by the original cross-sectional area of a material. Also known as nominal stress.</p>
<p align="justify"><mark class="hltr-purple">True stress</mark> is the applied load divided by the actual cross-sectional area (the changing area with respect to time) of the specimen at that load</p>

### <font color="#FFBB64">Strain</font>
$$Engineering \;Strain: \epsilon = \frac{\delta}{l_{o} \times {100\%}}$$
$$True \;Strain: \epsilon_{t}= \int \frac{\delta L}{L}$$
$$\delta \epsilon_{t}=\frac{\delta L}{L}$$
$$\epsilon_t=\ln(\frac{L}{L_o})=\ln(1+\epsilon)$$

$l_o$ : Initial length
$\delta$ : total elongation
$l$ : changed length ($l_o+\delta$)

<p align="justify"><mark class="hltr-purple">Engineering strain</mark> is the amount that a material deforms per unit length in a tensile test. Also known as nominal strain.</p>
<p align="justify"><mark class="hltr-purple">True strain</mark> equals the natural log of the quotient of current length over the original length.</p>

```
Tensile: Positive stress-strain
Compressive: Negative stress-strain
```

![UTS](https://yasincapar.com/wp-content/uploads/2020/10/Untitled-Project2.gif)

```
Elastic Deformation: Reversible
Plastic Deformation: Irreversible
```
### <font color="#FFBB64">Ductility</font>
<p align="justify">Significant plastic deformation and energy absorption (toughness) reveals before fracture. Characteristic feature of ductile material is necking before material failure.</p>

$$\%E = \frac{l_f-l_o}{l_o}$$
$$\%RA = \frac{A_o-A_f}{A_o}$$
$\%E$ : Elongation Percentage
$\%RA$ : Reduction Area Percentage

### <font color="#FFBB64">Brittle</font>
<p align="justify">Little plastic deformation or energy absorption reveals before fracture. Characteristic feature of brittle materials is different compare to ductile materials. Brittle materials fracture without any necking.</p>

![Ductile vs Brittle](https://yasincapar.com/wp-content/uploads/2020/10/12.gif)

### <font color="#FFBB64">Young's Modulus</font>
<p align="justify">The mechanical property of a material to withstand the compression or the elongation with respect to its length.</p>

$$Young \;Modulus: E = \frac{\sigma}{\epsilon}$$
$$E = \frac{\sigma}{\epsilon} = \frac{\frac{F}{A}}{\frac{\Delta L}{L_0}} = \frac{FL_0}{A\Delta L}$$
$E$ : Young’s modulus (Pa)
$\sigma$ : uniaxial stress (Pa)
$\epsilon$ : strain
$F$ : force exerted by the object under tension
$A$ : actual cross-sectional area
$\Delta L$ : change in the length
$L_0$ : actual length

![Young Modulus](https://cdn1.byjus.com/wp-content/uploads/2020/09/Youngs-Modulus.png)

## <font color="#FF6868">C. Deformation Process</font>
![Tensile Test](https://www.researchgate.net/profile/Gomathy-Sasikala/publication/271714333/figure/fig3/AS:294991764180997@1447342925842/Different-stages-during-tensile-test-a-uniform-deformation-b-diffused-necking-c.png)
<center>(a) uniform deformation, (b) diffused necking, (c) Localized
necking, (d) fracture</center>

***
# <font color="#DCFFB7">Impact Test</font>
## <font color="#FF6868">A. Purpose</font>
<p align="justify">The material impact test evaluates a material's <mark class="hltr-purple">resistance to deformation</mark> and <mark class="hltr-purple">fracture under sudden shock loading</mark>. This information is crucial for selecting appropriate materials for applications involving impact, such as automotive parts, protective equipment, and construction materials.
</p>

## <font color="#FF6868">B. Pendulum Impact Test</font>
<p align="justify"><font color="#FFEAA7">1) Pendulum Mechanism</font>: Both Charpy and Izod tests use a pendulum with a weighted hammer that swings and strikes a notched specimen.</p>
<p align="justify"><font color="#FFEAA7">2) Energy Measurement</font>: The energy absorbed by the specimen before breaking is measured to determine its toughness. This is typically expressed in joules (J).</p>
<p align="justify"><font color="#FFEAA7">3) Notched Specimens</font>: A notch is introduced in the specimen to concentrate stress and initiate fracture in a controlled manner, providing more consistent results.</p>

![Pendulum Test](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcS1G_UWs45q9fEo1xOg_qMBhWVyHC1UOj5BvANKQwz3zkeKEHNt-FUug0vVqD4W)

| Feature | Charpy Test | Izod Test |
| ---- | ---- | ---- |
| **Specimen Orientation** | Horizontal, with notch facing away from the hammer strike. | Vertical, with notch facing the hammer strike. |
| **Hammer Type** | Ball-peen hammer. | Knife-edge hammer. |
| **Specimen Dimensions** | Typically 55 mm x 10 mm x 10 mm. | Typically 75 mm x 10 mm x 10 mm. |
| **Notch Type** | Can use both V-notch and U-notch. | Primarily uses V-notch. |
<p align="justify"><mark class="hltr-purple">The key difference</mark> between the Charpy impact test and the IZOD impact test is how the sample is secured. For the Charpy test, the sample is supported on two sides and the pendulum strokes the middle of the sample. In the IZOD test, the sample is supported on only one side, i.e., in a cantilever configuration, and the pendulum strikes it on the opposite side. </p>

$$Fracture \;Energy: KV = m \times g \times(h_o-h_{f)}- E_f$$
$KV$: Impact energy
$m$: pendulum mass
$g$: gravitational constant
$h_o$: initial height of the pendulum
$h_f$: final heigth of the pendulum
$Ef$: energy loss due to friction


### <strong><font color="#FFBB64">Ductile-to-Brittle Temperature Transition Curve</font></strong>

Additional Source:
- [Brittle Fracture and Impact Properties](https://akbis.gantep.edu.tr/yonetim/upload/files/32443-2536.pdf)
- [Brittle Fracture and Impact Properties 2](https://akbis.gantep.edu.tr/yonetim/upload/files/4841-6077.ppt)
- [Charpy Impact Test](https://www.xometry.com/resources/3d-printing/charpy-impact-test/)

<p align="justify">The term ductile-to-brittle transition describes a low-temperature brittleness exhibited by certain metal which otherwise are ductile metals.</p> 

$$DBTT \uparrow Ductile \uparrow $$
$$DBTT \downarrow Brittle \downarrow $$

![DBTT](https://images.prismic.io/xometry-marketing/9a19e640-05bc-41b8-a881-6a628f1a0176_ductile-to-brittle-transition-temperature.png?auto=compress%2Cformat&fit=max&w=513&h=311&fm=webp)

####  <font color="#FFEAA7">1) Crystal Structure</font> 
<p align="justify">Only BCC structure materials experience ductile to brittle transition temperature. FCC and HCP structure materials do not experience DBTT, therefore they give the same energy absoption at any temperature relatively.</p>

$$DBTT : BCC$$
$$Non \;DBTT: HCP \;and \;FCC$$

- <p align="justify"><font color="#c3d69b">BCC (Body-centered cubic)</font>: As you mentioned, BCC structures like ferritic steels typically have higher DBTTs compared to FCC and HCP structures. This is because BCC structures have limited slip systems at low temperatures, hindering plastic deformation and promoting brittle fracture.</p>

- <p align="justify"><font color="#c3d69b">FCC (Face-centered cubic):</font> These structures like austenitic steels generally have lower DBTTs due to multiple slip systems readily available even at low temperatures.</p>

- <p align="justify"><font color="#c3d69b">HCP (Hexagonal close-packed):</font> Similar to FCC, HCP structures also have relatively low DBTTs due to multiple slip systems and easy basal plane slip.</p>

![DBTT_Crystal Structure](https://o.quizlet.com/H2MIzQx1ljH4peZjua.xTw.png)

#### <font color="#FFEAA7">2) Interstitial Atom (Composition)</font>
<p align="justify">Elements like carbon and manganese can increase the DBTT by strengthening the grain boundaries and making dislocations less mobile, it also reduces energy required for impact fracture.</p>

$$Carbon \;and \;Manganese\uparrow \; DBTT \uparrow$$
$$Aluminum \; and\;Silicon \uparrow \; DBTT \downarrow$$
$$Nickel \uparrow \; DBTT \downarrow$$
- <p align="justify"><font color="#c3d69b">Carbon</font>: Increasing carbon content in steels raises the DBTT by strengthening the grain boundaries and hindering dislocation movement. This effect is pronounced at higher carbon levels.</p>

#### <font color="#FFEAA7">3) Grain Size</font>
<p align="justify">Finer grains have lower DBTTs due to increased grain boundaries, which hinder crack propagation.</p>

$$Grain \;Size \downarrow DBTT \downarrow$$

- <p align="justify"><font color="#c3d69b">Finer grains</font>: grain boundaries act as barriers to crack propagation, and with more boundaries in a finer grain structure, cracks have a harder time traveling through the material.</p>

- <p align="justify"><font color="#c3d69b">Coarser grains</font>: cracks can propagate more easily across larger grains with fewer grain boundaries to impede them.</p>

#### <font color="#FFEAA7">4) Heat treatment</font>
<p align="justify">The notched-bar impact test has the greatest importance in determining “ductile-to-brittle transition” of material. This transition occurs at a <mark class="hltr-purple">temperature below which the material is brittle</mark> and fractures with a low energy absorption & low ductility, and above which it is ductile.</p>
<p align="justify">The transition actually covers a range of temperatures in which <mark class="hltr-purple">degree of brittleness increases gradually as temperature falls</mark>. It is very difficult to make a universal definition of transition temperature since two different materials having the same transition temperature may have different failures.</p>

$$Temperature \downarrow DBTT \downarrow$$

![DBTT_Temperature](https://i.imgur.com/YYl4fxn.png)

$T_f$ : Temperature for 100% **brittle** fracture
$T_b$ : Temperature for 100% **ductile** fracture

##### <strong><font color="#f79646">Kinds of Heat Treatments</font></strong>

- <p align="justify"><font color="#c3d69b">Annealing</font>: Annealing involves heating the material to a specific temperature and then cooling it slowly to relieve internal stresses, remove defects, and increase ductility and toughness.</p>
- <p align="justify"><font color="#c3d69b">Quenching </font>: Quenching is a process of rapid cooling after heating, which can increase the hardness of the material. While it can make the material harder, it can also make it more brittle.</p>
- <p align="justify"><font color="#c3d69b">Tempering </font>: Tempering is often performed after quenching to reduce the brittleness created by the quenching process. It involves heating the material to a specific temperature and then cooling it, which helps to reduce the hardness and increase the toughness of the material.</p>
#### <font color="#FFEAA7">5) Specimen orientation</font>
<p align="justify">For impact test, anisotropic properties are also observed in rolled or forged products, giving different energy absorption according to specimen orientations.</p>

![DBTT_Orientation](https://i.imgur.com/Ppc7rX7.png)

- <p align="justify"><font color="#c3d69b">Longitudinal (A & B) </font>: shows the best energy absorption
because the crack propagation is across the fibre
alignment.</p>
- <p align="justify"><font color="#c3d69b">Transverse (C) </font>: gives the worst energy absorption 
because the crack propagates parallel to the rolling 
direction.</p>

# <font color="#DCFFB7">Hardness Test</font>

## Metode Pengukuran Kekerasan

Three main types of hardness measurements:
- Scratch
- Indentation
- Rebound

Based on scale:
- Macro
- Micro
- Nano
### Scratch Hardness
Invented by: Friedrich Mohs (1815)

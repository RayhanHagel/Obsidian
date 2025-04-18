# Pengertian
Korosi merupakan fenomena deteriorasi metal akibat adanya interaksi dengan lingkungan. Korosi terjadi akibat adanya proses elektrokimia pada interfasa antara logam dengan lingkungan.

Korosi dapat terjadi apabila terdapat
- perbedaan potensial listrik
- terdapat anoda dan katoda yang terhubung
- terdapat elektrolit (tanah atau air)

# Prinsip Elektrokimia
## Hukum Faraday
Menjelaskan mengenai hubungan antara jumlah muatan listrik yang mengalir dan jumlah material yang teroksidasi atau tereduksi di elektroda.

_Rumus Hukum Faraday_
$$m\:=\:\frac{Q}{F}\times\frac{M}{n}$$
Keterangan
$\begin{aligned}&m&&:\text{Massa zat yang dihasilkan atau dikonsumsi (g)}\\&Q&&:\text{Jumlah muatan listrik (C)}\\&F&&:\text{Konstanta Faraday (96.485 C/mol)}\\&M&&:\text{Massa molar zat(g/mol)}\\&n&&:\text{Jumlah elektron yang terlibat dalam reaksi}\end{aligned}$
## Hukum Nernst
Memberikan deskripsi kuantitatif tentang hubungan antara potensial elektrode dan konsentrasi ion di sekitarnya, yang sangat penting dalam perhitungan potensial sel di kondisi non-standar.

_Rumus Hukum Nernst_
$$E\:=\:E^{0}-\frac{RT}{nF}lnQ$$
Keterangan
$\begin{aligned}&E&&:\text{Potensial sel (V)}\\&E^0&&:\text{Potensial standar (V)}\\&R&&:\text{Konstanta gas (8,314 J/mol K)}\\&T&&:\text{Suhu absolut (Kelvin, K)}\\&n&&:\text{Jumlah elektron yang terlibat dalam reaksi}\\&F&&:\text{konstanta faraday (96.485 C/mol)}\\&Q&&:\text{Hasil bagi reaksi, yaitu rasio konsentrasi produk terhadap reaktan}\end{aligned}$
# Reaksi
## Korosi
![[Pasted image 20240923120015.png]]
*Korosi dapat terjadi apabila terdapat empat komponen utama*
- Anode
	- Reduction happens $\rightarrow$ Pitting
- Cathode
	- Oxidation happens $\rightarrow$ Deposition
- Electrolyte
	- Larutan kondusif untuk **aliran ion** antara anoda dan katoda
- Metallic Path
	- Jalur konduktif di luar elektrolit yang menghubungkan anoda dan katoda, memungkinkan **aliran elektron**

*Reaksi dapat dipercepat apabila*
- Physical Characteristics
	- Exposed area $\uparrow$ makes corrosion rate $\downarrow$
	- Time exposed $\uparrow$ makes corrosion rate $\uparrow$
- Environmental Characteristics
	- Acidic environment
	- Sulfur gas environment
	- Temperature $\uparrow$ makes corrosion rate $\uparrow$
	- Moisture (oxygenated moisture)
## Kinetika Korosi
Kinetika korosi mengacu pada laju reaksi elektrokimia yang terjadi pada permukaan logam yang terpapar lingkungan korosif.  

1. Metode Weight Loss
	Pengukuran perubahan massa sampel logam setelah terpapar lingkungan korosif selama periode tertentu.
$$4Fe + 3O_2 \rightarrow 2Fe_2O_3$$

2. Metode Polarisasi Elektrokimia
	Memanfaatkan perangkat seperti potentiostat/galvanostat dan perangkat lunak NOVA AUTOLAB. Teknik ini menentukan densitas arus korosi ($i_{corr}$) yang menggambarkan intensitas korosi pada permukaan logam

*Rumus Laju Korosi berdasarkan hukum Faraday*
$$CR\:=\frac{Mr\times i_{corr}}{n\times F}$$
Keterangan
$\begin{aligned}&CR&&:\text{Laju korosi (mm/year atau satuan lainnya)}\\&Mr&&:\text{Massa molar logam (g/mol)}\\&i_{corr}&&:\text{Densias arus korosi (A/cm}^{2})\\&n&&:\text{Jumlah elektron dalam reaksi}\\&F&&:\text{Konstanta Faraday (96.485 C/mol)}\end{aligned}$

*Evans Diagram*
Digunakan untuk memahami distribusi dan kontrol reaksi anodik dan katodik. Prinsip teori potensial campuran menjelaskan bahwa laju korosi ditentukan oleh titik perpotongan antara kurva polartias anodik dan katodik. Ini sangat esensial untuk memilih material tahan korosi dan merancang strategi perlindungan yang efektif untuk struktur logam.
	![[Evans Diagram.png]]

## Passivation
*Elemen yang dapat membuat protective film*
- Chromium, nickel, titanium, dan aluminum

*Fungsi lapisan pasif*
- untuk menjaga dari korosi lebih lanjut
- bersifat self healing apabila rusak

Lapisan pasif sensitif terhadap lingkungan sehingga dapat memiliki corrosion rate yang tinggi. Lihat juga [[passivation]]

# Jenis Korosi
## General Corrosion (Uniform Corrosion)
Ditandai dengan penipisan yang seragam tanpa serangan lokal, yang memengaruhi material seperti baja tahan cuaca dan paduan tembaga.

- **Korosi Atmosferik**
	- *Mekanisme*: Terjadi karena paparan logam terhadap atmosfer yang mengandung oksigen dan uap air, membentuk lapisan oksida pada permukaan logam.
	- *Faktor Penyebab*: Kelembapan udara, polutan, oksigen, dan suhu.
	- *Cara Menghindari*: Pelapisan logam (cat, galvanisasi), penggunaan inhibitor, dan pengontrol kelembapan.
	- ![[Atmospheric corrosion.png]]
	- Lihat juga [[atmospheric corrosion]] 

- **Korosi Galvanis**
	- *Mekanisme*: Terjadi saat dua logam berbeda bersentuhan dalam larutan elektrolit, menyebabkan logam yang lebih aktif (anoda) mengalami korosi.
	- *Faktor Penyebab*: Perbedaan potensial elektrokimia antara dua logam.
	- *Cara Menghindari*: Mengisolasi logam yang berbeda, menambahkan penghambat korosi, atau memilih pasangan logam yang cocok.
	- Lihat juga [[galvanic corrosion]]
- **Korosi Arus Liar**
	- *Mekanisme*: Korosi akibat arus listrik yang bocor ke logam dari sumber eksternal, misalnya dari sistem kelistrikan.
	- *Faktor Penyebab*: Arus bocor dari kabel atau sistem kelistrikan dekat logam.
	- *Cara Menghindari*: Isolasi logam dari sumber arus liar atau sistem grounding.
- **Korosi Biologis**
	- *Mekanisme*: Disebabkan oleh aktivitas mikroorganisme seperti bakteri penghasil asam atau sulfat.
	- *Faktor Penyebab*: Kehadiran mikroorganisme dan nutrisi dalam lingkungan.
	- *Cara Menghindari*: Pembersihan teratur, penggunaan inhibitor biologi, atau pengontrolan nutrisi.
	- *Reaksi Kimia*: Reaksi oksidasi pada logam dan reaksi mikroba yang menghasilkan asam atau senyawa korosif lain.
- **Korosi Molten Salt**
	- *Mekanisme*: Terjadi ketika logam bersentuhan dengan garam cair pada suhu tinggi, mempercepat laju korosi.
	- *Faktor Penyebab*: Suhu tinggi dan kontak langsung dengan garam cair.
	- *Cara Menghindari*: Penggunaan pelapis tahan panas atau logam yang tahan garam cair.
	- *Reaksi Kimia*: Logam teroksidasi oleh ion dalam garam.
- **Korosi Temperatur Tinggi**
	- Oksidasi $\rightarrow$ pembentukan kerak oksida $\rightarrow$ ketebalan menurun
	- Sulfidasi $\rightarrow$ uniform corrosion
	- Karburisasi $\rightarrow$ pembentukan karbida $\rightarrow$ brittle
## Localized Corrosion
- **Filiform**
	- *Mekanisme*: Serangan omnidirectional yang terjadi di bawah lapisan pelindung ketika uap air menyusup ke permukaan logam, menyebabkan korosi berbentuk benang.
	- *Faktor Penyebab*: Kelembapan tinggi dan adanya lapisan pelindung yang tidak sempurna.
	- *Cara Menghindari*: Pengaplikasian pelapis yang merata dan tahan air.
- **Crevice / Celah**
	- *Mekanisme*: Terjadi di area yang terperangkap air atau elektrolit dalam celah atau retakan, menyebabkan korosi lokal.
	- *Faktor Penyebab*: Keberadaan celah kecil atau rongga pada logam.
	- *Cara Menghindari*: Merancang tanpa celah, pembersihan rutin, dan pelapisan antikarat.
	- Lihat juga [[crevice corrosion]]
- **Pitting**
	- *Mekanisme*: Terjadi ketika korosi membentuk lubang kecil pada permukaan logam akibat inisiasi lokal di permukaan.
	- *Faktor Penyebab*: Kehadiran klorida, oksigen terbatas.
	- *Cara Menghindari*: Pelapisan logam, penggunaan inhibitor, atau pemilihan logam tahan pitting.
	- Lihat juga [[pitting corrosion]]
## Metallurgy Influenced Corrosion
Merupakan korosi yang disebabkan oleh faktor metalurgi seperti paduan kimia, perlakuan panas, stabilitas relatif komponen, fasa logam, fasa metaloid, dan variasi komposisi lokal.
- **Intergranular Corrosion (IGC)**
	- Dipengaruhi oleh metalurgi, terjadi pada batas butir yang menyebabkan pelepasan butir yang menyebabkan pelepasan butir dan pengerasan permukaan, dengan peningkatan laju korosi yang nyata dari waktu ke waktu.
	- Lihat juga [[Intergranular corrosion]]
- **Dealloying**
	- Melibatkan pelarutan dua logam dalam sautu paduan, melarutkan satu logam secara selektif atau keduanya. Logam yang terpengaruh menjadi terkeropos, kehilangan kekuatan, kekerasan, dan keuletan, dan dapat menyebabkan kegagalan mendadak.
## Mechanical Influenced Corrosion
Degradasi logam yang dibantu secara mekanis melibatkan mekanisme korosi dan keausan. 
- **Erosi**
	- Umum terjadi pada sistem penampung cairan, yang menyebabkan kerusakan bahkan pada tingkat korosifitas yang kecil. Logam dengan lapisan pelindung yang tebal lebih sensitif terhadap erosi
- **Fretting**
	- Terjadi ketika permukaan saling bersentuhan, menyebabkan gerakan kecil secara berkala dan menghasilkan lubang yang dikelilingi oleh produk korosi berbentuk tepung yang dipengaruhi oleh slip, frekuensi getaran, dan pembebanan.
- **Kavitasi**
	- Suatu bentuk kerusakan kavitasi yang dapat menyebabkan partikel logam masuk bersama aliran cairan, membentuk kawah dengan tepi yang tidak beraturan dan permukaan internal yang kasar.
- **Fatigue**
	- Kombinasi dari korosi dan kelelehan, mengurangi ketahanan lelah karena efek media korosif. Hal ini mengakibatkan retakan transgranular, tidak bercabang, atau bercabang jarang pada baja karbon.
## Environmental Influenced Corrosion
- **Stress Corrosion Cracking**
	- Ditandai dengan pola bercabang, terjadi pada logam akibat regangan tarik yang konstan, yang memengaruhi berbagai bahan seperti baja karbon, paduan tembaga, dan baja tahan karat.
- **Hydrogen Embrittlement**
	- Terjadi karena serangan asam dan kaustik yang menyebabkan atom hidrogen berdifusi dan bereaksi dengan karbida besi menghasilkan metana.
- **Liquid Metal Embrittlement**
	- Endapan logam pada suatu struktur yang menyebabkan keretakan karena penggetasan logam cair selama pengelasan atau operasi suhu tinggi. Untuk ngatasin ini harus dibersihkan secara kimiawi untuk mencegah pelapisan.

# Corrosion Protection
Jadi intinya tuh kalau misal kita mau proteksi suatu material dari korosi, kita harus menghilangkan salah satu faktor dari corrosion puzzle yang ada di [[#Korosi]]
## Environmental Modification
Jadi disini kita mau ngehilangin dari salah satu faktor bagian *electrolyte*. Jadi disini kita memodifikasi parameter lingkungan seperti pH, kelembapan, atau keberadaan oksigen yang berpotensi memicu korosi. Ini dilakukan dengan pengaturan atmosfer, pengontrolan senyawa kimia dalam lingkungan cair, atau pengurangan elemen agresif.

1. **Inhibitor**
	Inhibitor merupakan sebuah komponen kimia yang ditambahkan dalam jumlah kecil dengan tujuan untuk membentuk lapisan film tipis pada permukaan logam yang dapat menghindari permukaan logam terpapar lingkungan korosif.

	Berdasarkan jenis senyawa kimianya:
	- *Inhibitor Organik*
		Mengandung gugus polar seperti N, S, O, dan senyawa heterosiklik. Bekerja dengan membentuk lapisan hidrofobik.
	- *Inhibitor Anorganik*
		Senyawa garam kristalin seperti fosfat, molibdat, kromat, dan sodium nitrit. Bekejra dengan membentuk ikatan ionik pada permukaan logam untuk melindungi dari korosi.
		
	Berdasarkan mekanisme inhibisi
	- *Scavanger Inhibitor*
		Berfungsi untuk mengurangi konsentrasi oksigen terlarut dalam larutan.
	- *Interface Inhibitor*
		Membentuk lapisan pelindung pada antarmuka logam dan elektrolit. Inhibitor dapat berupa fasa cair atau gas.
	- *Neutralizer*
		Mengurangi korosi dengan menurunkan konsentrasi ion $H^+$ dalam larutan.

2. **Modifier**
	Modifier bekerja dengan menghambat proses elektrokimia dengan mengubah kondisi lingkungan di sekitar logam, sehingga mengurangi potensial terjadinya korosi. Prinsipnya adalah dengan menyesuaikan parameter seperti pH, konsentrasi ion, atau komposisi kimia larutan.

	Klasifikasi Modifier
	- *Modifier pH*
		- asam sitrat $\rightarrow$ menetralkan larutan basa
		- natrium karbonat $\rightarrow$ menetralkan larutan asam
	- Pengikat Ion Agresif
		- Senyawa fosfat $\rightarrow$ mengikat ion klorida
		- Etilen Diamin Tetra Asetat $\rightarrow$ mengikat ion logam berat dalam larutan

**Efisiensi Inhibitor**
$$\%Efisiensi\:=\:\frac{CR_{uninhibited}-CR_{inhibited}}{CR_{uninhibited}}\times100\%$$
Keterangan
$\begin{aligned}&CR_{uninhibited}&&:\text{Laju korosi tanpa inhibitor}\\&CR_{inhibited}&&:\text{Laju korosi dengan inhibitor}\end{aligned}$


**Jumlah inhibitor**
$$Q_{inh}=\frac{V_{fluid}}{1.0\times\:10^6}\times\:C_{inh}$$
Keterangan
$\begin{aligned}&Q_{inh}&&:\text{Jumlah inhibitor (Kg)}\\&V_{fluid}&&:\text{Volume fluida (L)}\\&C_{inh}&&:\text{konsentrasi inhibitor (ppm)}\end{aligned}$
## Potential Change
Merupakan metode proteksi korosi yang melibatkan *pengubahan potensial listrik* permukaan logam untuk mengendalikan reaksi elektrokimia yang menyebabkan korosi.

1. **Proteksi Anodik**
	Menggunakan arus listrik eksternal untuk *menggeser potensial elektroda logam ke zona pasif* sehingga terbentuk lapisan oksida pelindung di permukaan logam yang dapat mencegah transfer ion sehingga dapat mengurangi laju korosi. Oleh karena itu, metode ini hanya bisa digunakan pada *logam yang memiliki lapisan pasivasi*, seperti aluminium.

	*Komponen*
	- Arus listrik eksternal
	- Elektroda bantuan
	- Logam yang dilindungi $\rightarrow$ potensialnya dinaikin $\rightarrow$ Reduksi

	*Keunggulan*
	- Mengontrol korosi dalam kondisi yang sangat agresif
	- Memperpanjang masa pakai logam

	*Kekurangan*
	- Biaya pemasangan dan operasional tinggi
	- Pemeliharaan yang terus-menerus
	- Bila salah, dapat menyebabkan pitting atau korosi lokalisasi

2. **Proteksi Katodik**
	Metode efektif untuk mencegah korosi pada logam dengan mengubah logam menjadi katoda dalam sel elektrokimia

	Terbagi menjadi dua metode
	- *Sacrificial Anode*
		Menggunakan logam yang lebih reaktif (potensial lebih rendah) sebagai anoda. Sehingga logam tersebut akan terkorban dan melindungi material.
		$$i\:=\:\frac{C\times\:f\times\:y}{p}$$
		Keterangan
		$\begin{aligned}&i&&:\text{Arus keluaran (mA)}\\&C&&:\text{Konstanta material}\\&f&&:\text{Faktor ukuran}\\&y&&:\text{Faktor potensial}\\&\rho&&:\text{Resistivitas lingkungan}\end{aligned}$
		
	- *Impressed Current Cathodic Protection (ICCP)*
		Metode untuk memberikan arus proteksi pada logam sehingga logam yang dilindungi akan tetap menjadi katoda.

		_Rumus menghitung resistivitas_
		$$\rho=2πAR$$
		Keterangan
		$\begin{aligned}&\rho&&:\text{Resistivitas lingkungan}\\&A&&:\text{Jarak antar elektroda}\\&R&&:\text{Resistansi terukur}\end{aligned}$

		_Rumus mengitung arus proteksi dengan hukum ohm_
		$$\begin{matrix}I&=&\frac{V}{R}\end{matrix}$$
		Keterangan
		$\begin{aligned}&I&&:\text{Arus (A)}\\&V&&:\text{Tegangan (V)}\\&R&&:\text{Resistansi }(\Omega)\end{aligned}$
## Design Improvement
Merupakan upaya untuk meningkatkan ketahanan material terhadap korosi melalui modifikasi pada permukaan dan perubahan komposisi material. Pendekatan ini bertujuan untuk meningkatkan sifat fisik dan kimia dari material agar lebih tahan terhadap faktor lingkungan yang agresif.

1. **Surface Modification**
	Memodifikasi permukaan material dengan cara pelapisan, pengerasan permukaan, anodisasi, pelapisan galvanism dan teknik kimia ataupun fisika lainnya untuk membuat pelindung. Dengan adanya perubahan karakteristik permukaan, jadinya material tidak berkontak langsung dengan lingkungan korosif.

2. **Change Composition**
	Perubahan atau penyesuaian komposisi kimia material untuk meningkatkan ketahanan terhadap korosi. Misalnya penambahan kormium dan magnesium untuk membentuk lapisan oksida yang dapat mencegah korosi. Bisa juga dengan meningkatkan potensial (mengurangi reaktivitas) dengan menambahkan molibdenum, nikel, dan silikon.
## Coating
Merupakan proses penambahan lapisan (target) pada material yang ingin dilindungi (substrat). Hal ini sebagai ada barrier terhadap kontaminan atau lingkungan yang merusak sehingga dapat meningkatkan ketahanan korosi, abrasi, erosi material dan meningkatkan estetika.

**Syarat Coating**
- resistensi yang baik terhadap aliran elektron
- derajat adhesi yang tinggi
- laju difusi yang rendah
- durabilitas yang tinggi
- aman bagi kesehatan dan lingkungan
- terjangkau dalam hal ketersediaan dan biaya produksi

1. **Organic Coating**
	 Jenis pelapis dengan bahan organik
	 - *Solvent* $\rightarrow$ pembentuk lapisan coating (bentuk mula cair)
	 - *Pigmen* $\rightarrow$ memberikan warna agar tidak terpapar sinar matahari
	 - *Aditif dan Filler* $\rightarrow$ Meningkatkan resistansi dan mempercepat pengeringan coating
	 - *Ekstender* $\rightarrow$ Merekayasa kualitas cat dan meningkatkan performa coating (CaCO3, silika, barytes)
	 - *Binder* $\rightarrow$ Mengikat pigmen pada lapisan homogen, meningkatkan adhesi, kohesi, fleksibilitas, dan sifat mekanik (acrylic, alkyd, epoxy)

2. **Inorganic Coating**
	 Jenis pelapis dengan bahan inorganik
	 - *Bahan dasar* $\rightarrow$ Memberikan sifat ketahanan terhadap suhu tinggi dan korosi (silikat, oksida, karbonat)
	 - *Pigmen* $\rightarrow$ Memberikan warna dan proteksi sinar uv dan radiasi (mineral)
	 - *Binder* $\rightarrow$ Meningkatkan daya rekat coating dan meningkatkan kekerasan (silikat)
	 - *Aditif* $\rightarrow$ Meningkatkan sifat ketahanan abrasi, pengurangan kerapatan, pengendalian viskositas.

3. **Mixed Coating**
	 Gabungan dari organic dan inorganic coating, jadi dia menggunakan keunggulan dari keduanya.
	 - *Peningkatan ketahanan korosi*
	 - *Fleksibilitas dan Ketahanan*
		 - fleksibilitas $\rightarrow$ organic coating
		 - ketahanan $\rightarrow$ inorganic coating
	 - *Ketahanan terhadap suhu tinggi*
		 - Adhesi $\rightarrow$ organic coating
		 - ketahanan suhu tinggi $\rightarrow$ inorganic coating
## Plating
- Pelapisan permukaan untuk meningkatkan ketahanan korosi, memperbaiki sifat mekanik, dan estetika.

- *Electroplating:* Menggunakan arus listrik dalam elektrolit untuk mengendapkan logam pada permukaan substrat.
	- Faktor yang mempengaruhi
		- Overpotential hidrogen: arus menjadi lebih kuat pada batas logam dan elektrolit, dapat menyebabkan reduksi hidrogen
		- Charge transfer resistance: mempengaruhi laju deposit dan ketebalan lapisan
		- Resistansi polarisasi: resistansi antara elektroda dan elektrolit dapat mengurangi potensial listrik pada sel volta
	- Material: Zn, Cr, Cu, Ni, Au, timah, perak.

- *Electroless Plating:* Tidak memerlukan arus listrik, bergantung pada reaksi kimia, dapat diterapkan pada bahan non-konduktif.
	- Keuntungan
		- Substrat non konduktif
		- Lapisan yang merata
		- Tidak memerlukan peraltan khusus
		- Ketahanan korosi yang baik
	- Faktor
		- Kualitas larutan elektrolit: harus dikontrol biar kualitas
		- Suhu proses: gak boleh terlalu tinggi atau rendah
		- Adhesi: harus kuat

- *Mechanical Plating:* Menggunakan energi mekanik untuk mengendapkan partikel logam, cocok untuk berbagai jenis substrat.
	- Keuntungan
		- Ketahanan terhadap korosi
		- Kualitas permukan yang baik: lapisan merata
		- Fleksibilitas Material
		- Pengurangan risiko kerusakan: tidak ada listrik (gak bisa overheating)

	- Faktor
		- Kualitas partikel logam: ukuran dan komposisi partikel logam harus dipilih sesuai
		- Pengaturan energi mekanik: kekuatan dan durasi pengadukan mempengaruhi efisensi pelapisan.
## Tujuan
- mengetahui nilai kekerasan
- prinsip metode pengujian
- metode brinnel, vickers, knoop, rockwell
- pengaruh jenis logam dan temperatur
- pengelasan
## Standard
- **Rebound: ASTM E448** “Standard Practice for Scleroscope Hardness Testing of Metallic Materials”
- **Konversi: ASTM E140** "Standard Hardness Conversion Tables for Metals Relationship Among Brinell Hardness, Vickers Hardness, Rockwell Hardness, Superficial Hardness, Knoop Hardness, Scleroscope Hardness, and Leeb Hardness"
- **Brinell: ASTM E10** “Standard Test Method For Brinell Hardness Of Metallic Materials”.
- **Rockwell: ASTM E18** “Standard Test Methods for Rockwell Hardness of Metallic Materials”
- **Micro Vickers: ASTM E384** “Standard Test Method for Microindentation Hardness of Materials” 
- **Macro Vickers: ASTM E92** “Standard Test Methods For Vickers Hardness And Knoop Hardness Of Metallic Materials” 
- **Knoop: ASTM D1474** “Standard Test Methods for Indentation Hardness of Organic Coatings”

## Skala
- Macrohardness (Rockwell, Brinell, Vickers)
	- 50 N sampai 30.000 N
- Microhardness (micro-Vickers, Knoop)
	- 1 sampai 1000 gf
- Nanohardness (Indentasi Berkovich dan AFM)
	- 1 nano-Newton

## Metode Pengujian
- **Scratch** ![[Pasted image 20240921090354.png]]
- **Rebound**
	- Menggunakan scleroscope untuk mengukur tinggi pantulan
- **Indentasi**
	- Menggunakan indentor untuk membuat jejak, hasil bergantung pada indentor dan jenis pengujian. Area indentasi menunjukkan kekerasan
	- *Brinnel*
		- menggunakan hardened steel ball (D=10 mm)
		- Minimal indentasi 2x
		- Rumus ![[Pasted image 20240921091513.png]]
		- Prinsip
			- Indentor menyentuh permukaan secara tegak lurus.
			- Diameter indentasi diukur
		- Hasil
			- 80 HB, 10/1500/60 
			- Nilai Kekerasan, diameter indentor (mm)/ beban (kgf)/waktu indentasi (detik)
	- *Rockwell*
		- menggunakan indentor intan kerucut 120$\degree$ (D=1/16 inch) atau bola baja (D= 1/8 inch)
		- Minimal indentasi 3x (harus ada beban minor, beban mayor, dan dwell time)
		- Regular Rockwell Scales dan Superficial Rockwell Scales
		- Skala nya tuh pakai huruf, ABCDEFG, kalau makin ke arah A, untuk material yang lebih kuat.
	- *Vickers*
		- menggunakan indentor intan piramida 136$\degree$
		- Rumus ![[Pasted image 20240921094057.png]]
		- membutuhkan polishing karena dia mikro, sensitif banget.
		- Hasil
			- 350 HV 30/60
			- kekerasan 350HV, beban 30kgf, dan waktu 60 detik
	- *Knoop*
		- menggunakan indentor dengan sudut 172$\degree$-30'
		- untuk benda getas dan tipis
		- perlu polishing (Al2O3/diamond)
		- Rumus ![[Pasted image 20240921094434.png]]
		- Mencari anisotropi material

## Aplikasi Pengujian Kekerasan
### Anisotropi
Anisotropi merupakan perbedaan sifat pada material berdasarkan arah kristalografi yang berbeda
### Machinability
Kekerasan sangat mempengaruhi sifat mampu mesin dari sebuah material (machinability). 
### Indetifikasi Fasa
Kekerasan pada skala mikro juga dapat digunakan untuk mengidentifikasi fasa melalui nilai kekerasannya. 
### Prediksi Sifat Mekanis
TS (MPa) = 3,45 x HB
TS = 0,189 HV - 1,38

## Heat Affected Zone
![[Pasted image 20240921101123.png]]
Terbagi menjadi tiga bagian:
- Fusion Zone: pengaruh panas paling tinggi, kekerasan paling tinggi karena pendinginan cepat sehingga terbentuk martensite
	- baja hipoeutectodi: mikro widmanstatten
	- baja hypereutectoid: widmanstatten cementite
- HAZ dekat base metal
	- kekerasan tinggi karena rekristalisasi tapi tidak terjadi grain growth
- Base metal
	- Kekerasan cukup tinggi, gak dapat pengaruh temperatur
- HAZ dekat fusion zone
	- ini terjadi grain growth, jadi kekerasan paling buruk
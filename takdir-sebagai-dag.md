---
title: Memahami Takdir dengan Kerangka Directed Acyclic Graph
tags:
  - rukun-iman
  - iman-kepada-takdir
  - place-holder
---
# Memahami Takdir dengan Kerangka Directed Acyclic Graph (DAG)

## Apa itu DAG

[Directed Acyclic Graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph) adalah sebuah representasi data yang berupa graph, yaitu kumpulan [node](https://en.wikipedia.org/wiki/Vertex_(graph_theory)) dan [egdes](https://en.wikipedia.org/wiki/Edge_(graph_theory)), namun tidak terbentuk [cycle](https://en.wikipedia.org/wiki/Cycle_(graph_theory)). DAG akan kita gunakan untuk membuat diagram visual atas contoh kasus takdir.

Misalnya, ada seseorang yang baru lulus sekolah SMK kemudian dia berada di-persimpangan, apakah dia akan lanjut kuliah, langsung kerja, atau santai dulu.

![manusia dipersimpangan](Illustration/manusia%20dipersimpangan.png)

Katakanlah dia memilih langsung kerja, dan melamar di beberapa tempat. sampailah dia pada 2 pilihan karena ada 2 perusahaan yang menerima:
1. Kerja sebagai sales bank, yang bertugas mencari nasabah untuk mengajukan pinjaman bank.
2. Kerja sebagai mekanik di bengkel.
Semua punya kelemahan dan kelebihan. Misalnya, kerja di bengkel itu sesuai keahlian yang didapat semasa sekolah, tetapi kerja di ruang yang non-AC dan kotor dengan oli dan minyak. Kerja di bank tidak kotor, tetapi tidak sesuai dengan ilmu, namun paket gaji dan bonus lebih banyak, dengan resiko kerja di tempat ribawi.

![takdir berikutnya setelah takdir](Illustration/takdir%20berikutnya%20setelah%20takdir.png)

Kita bisa memodelkan peristiwa dan pilihan hidup sepanjang umur seorang manusia dengan pendekatan diatas, Dengan komponen:

- **Source (awal)** → kelahiran
- **Node** → keadaan hidup (kaya, miskin, sehat, ujian, peluang)
- **Edge (panah)** → pilihan manusia (taat, maksiat, sabar, lalai, taubat)
- **Sink (akhir)** → surga atau neraka

Demikianlah DAG, dia bergerak dari satu node ke node yang lain, dan tidak pernah kembali ke node sebelumnya.

## Dalil terkait Takdir

Hadis riwayat sahabat **Ubadah bin ash-Shamit** _radhiyallahu 'anhu_.

Rasulullah SAW bersabda:

> "Sesungguhnya sesuatu yang pertama kali Allah ciptakan adalah **Pena (Al-Qalam)**. Kemudian Allah berfirman kepadanya: **'Tulislah!'** Pena bertanya: 'Wahai Tuhanku, apa yang harus aku tulis?' Allah berfirman: **'Tulislah takdir segala sesuatu sampai datangnya hari kiamat.'**"
> 
> **(HR. Abu Dawud No. 4700 dan Tirmidzi No. 2155. Syekh Al-Albani mensahihkannya)**

Hadis dari **Abdullah bin 'Amr bin al-'Ash** _radhiyallahu 'anhuma_ menjelaskan kapan tepatnya proses penulisan itu selesai dilakukan sebelum penciptaan alam semesta fisik:

> "Allah telah mencatat takdir setiap makhluk **50.000 tahun sebelum** Dia menciptakan langit dan bumi."
> 
> **(HR. Muslim No. 2653)**

Hadis riwayat sahabat **Abdullah bin Abbas** _radhiyallahu ‘anhuma_. Rasulullah SAW bersabda kepada beliau:

> "...Ketahuilah, sekiranya seluruh umat berkumpul untuk memberimu suatu manfaat, mereka tidak akan bisa memberimu manfaat kecuali dengan sesuatu yang telah Allah tetapkan untukmu. Dan sekiranya mereka berkumpul untuk mencelakakanmu, mereka tidak akan bisa mencelakakanmu kecuali dengan sesuatu yang telah Allah tetapkan atasmu. **Pena telah diangkat dan lembaran-lembaran (tinta) telah kering.**"
> 
> **(HR. Tirmidzi No. 2516, ia berkata: "Hadis ini hasan shahih")**

> **“Tidak akan kamu dapati perubahan pada sunnatullah.”**  
> ([QS. Al-Ahzab 33 - 62](Quran/QS.%20Al-Ahzab%2033%20-%2062.md), [QS. Fathir 35 - 43](Quran/QS.%20Fathir%2035%20-%2043.md))

➡️ Aturan graph:

- sudah ditulis lengkap, mencakup semua kejadian sampai hari kiamat.
- tetap, tidak berubah, konsisten.

## Manusia memilih opsi takdir yang disediakan Allah

Graph takdir inilah isi dari lauhul mahfudz. Graph ini jauh lebih kompleks dari contoh graph diatas, karena jumlah kejadian nya sangat-sangat banyak. Opsi yang tersedia yang bisa dipilih seseorang sangat-sangat banyak.

Namun demikian, pilihan yang banyak tadi bisa dikelompokkan menjadi 2 kelompok besar, yaitu jalan **kebaikan** dan jalan **keburukan**.

![takdir terdiri dari pilihan baik dan buruk](Illustration/takdir%20terdiri%20dari%20pilihan%20baik%20dan%20buruk.jpg)

> وَهَدَيْنَـٰهُ ٱلنَّجْدَيْنِ
> **“Dan Kami telah menunjukkan kepadanya dua jalan.”**  
> ([QS. Al-Balad 90 - 10](Quran/QS.%20Al-Balad%2090%20-%2010.md))

➡️ Manusia selalu memiliki pilihan (outgoing edge)

Perkataan **Umar bin Khattab**:
> **“Kami lari dari satu takdir Allah menuju takdir Allah yang lain.”**  
> (HR. Bukhari)

➡️ Makna dalam GRAPH:

- pilihan manusia terbatas, sesuai dengan opsi takdir yang disediakan Allah, tidak bisa keluar dari graph.
- manusia memilih **jalur (edge) yang berbeda**, dan akan dimintai pertanggungjawaban atas pilihan tersebut.

## Akhir dari takdir adalah 1 dari 2

Ujung akhir takdir adalah 1 dari 2 kemungkinan: surga atau neraka. Selama manusia hidup, dia berada di tengah perjalanan graph (graph-traverse) - dia sudah lahir dan belum meninggal. Dia belum sampai pada kondisi final berakhir di surga atau di neraka.

### 📖 Dari Abdullah bin Mas'ud
Rasulullah ﷺ bersabda:
> إِنَّمَا الأَعْمَالُ بِالخَوَاتِيمِ  
> _“Sesungguhnya amal itu tergantung pada penutupnya (akhirnya).”_

📚 Sumber:
- Sahih al-Bukhari no. 6607
- Sahih Muslim no. 2643

### 📖 Dari Abdullah bin Mas'ud
Rasulullah ﷺ bersabda:

> _“Seseorang beramal dengan amalan ahli surga… hingga tinggal sejengkal, lalu ia didahului oleh ketetapan, maka ia beramal dengan amalan ahli neraka lalu masuk neraka. Dan seseorang beramal dengan amalan ahli neraka… lalu ia beramal dengan amalan ahli surga lalu masuk surga.”_

📚 Sumber:

- Sahih al-Bukhari no. 3208
- Sahih Muslim no. 2643

### 📖 [QS. Ali Imran 3 - 102](Quran/QS.%20Ali%20Imran%203%20-%20102.md)
> وَلَا تَمُوتُنَّ إِلَّا وَأَنْتُمْ مُسْلِمُونَ  
> _“Janganlah kalian mati kecuali dalam keadaan Muslim.”_

### 📖 [QS. Al-Baqarah 2 - 132](Quran/QS.%20Al-Baqarah%202%20-%20132.md)

> _“Janganlah kalian mati kecuali dalam keadaan berserah diri (Muslim).”_

### Kaitan dengan konsep GRAPH (DAG)

Dalam kerangka kita:

- Awal (start node) → tidak menentukan
- Tengah (proses) → belum menentukan
- **Akhir (final node) → penentu mutlak**

➡️ Maka:

- **Husnul khatimah** = berakhir di jalur kebaikan → Surga
- **Su’ul khatimah** = berakhir di jalur keburukan → Neraka

## Peran Allah dan Manusia

### 🟢 Allah:

- Menulis seluruh graph
- Menentukan hukum sebab-akibat
- Menentukan outcome setiap jalur

### 🔵 Manusia:

- Memilih edge (traversal)
- Bertanggung jawab atas pilihan
- Tidak bisa mengubah graph

## Taubat dalam Graph Takdir

> **Taubat = koreksi traversal**

- tidak menghapus node lama
- tapi mengubah arah dari posisi sekarang

> _“Orang yang bertaubat seperti tidak berdosa.”_  
> (HR. Ibnu Majah)

Kembali pada Surat [QS. Al-Balad 90 - 10](Quran/QS.%20Al-Balad%2090%20-%2010.md) dimana seseorang dapat memilih jalan yang sesat, selama dia masih hidup, dia belum final masuk surga atau neraka, masih ada kesempatan untuk koreksi. Koreksi ini disebut taubat, dimana seseorang kembali memilih jalan yang benar. Dalam ilustrasi graph, dia kembali memilih yang hijau.

Semakin kita konsisten di jalur hijau - jalan yang benar, semakin besar peluang masuk surga.
## Pengaruh Doa dalam Graph Takdir

### 📖 Dari Salman al-Farisi

Rasulullah ﷺ bersabda:
> لَا يَرُدُّ الْقَدَرَ إِلَّا الدُّعَاءُ  
> _“Tidak ada yang dapat menolak takdir kecuali doa.”_

📚 Sumber:
- Jami' at-Tirmidhi no. 2139 (hasan)

Apakah doa merubah takdir? Bukan! Doa adalah bagian dari pada takdir itu sendiri. Dalam graph takdir, Doa adalah node, manusia memilih berdoa atau tidak. Jika dia memilih berdoa, maka terbuka 2 jalur takdir ([QS. Al-Balad 90 - 10](Quran/QS.%20Al-Balad%2090%20-%2010.md)) dari doa tersebut.

## Pengaruh Tawakal dalam Graph Takdir

- Tawakal adalah konsekuensi iman kepada Allah
	- Dia harus tahu tuhannya ada. [QS. At-Tur 52:35-36](Quran/QS.%20At-Tur%2052%20-%2035%20sampai%2036.md)
	- Dia tahu tuhannya maha kuasa, sehingga memiliki kapasitas untuk menyelesaikan masalahnya.
		- [QS. Al-Baqarah 2:20](Quran/QS.%20Al-Baqarah%202%20-%2020.md)
		- [QS. Al-Mulk 67:2](Quran/QS.%20Al-Mulk%2067%20-%202.md)
		- [QS. Al-An’am 6:17](Quran/QS.%20Al-An’am%206%20-%2017.md)
		- [QS. Yasin 36:82](Quran/QS.%20Yasin%2036%20-%2082.md)
		- [QS. Ali Imran 3:160](Quran/QS.%20Ali%20Imran%203%20-%20160.md)
		- Dari Ibnu Abbas, Rasulullah ﷺ bersabda:“Ketahuilah, jika seluruh umat berkumpul untuk memberi manfaat kepadamu, mereka tidak akan bisa memberi manfaat kecuali yang telah Allah tetapkan…”(HR. Tirmidzi no. 2516)
	- Dia sudah tahu ada tuhan dan tuhannya maha kuasa, maka dia meminta kepada tuhan nya
		- [QS. Ghafir 40:60](Quran/QS.%20Ghafir%2040%20-%2060.md)
		- [QS. An-Naml 27:62](Quran/QS.%20An-Naml%2027%20-%2062.md)
		- [QS. Al-Baqarah 2:186](Quran/QS.%20Al-Baqarah%202%20-%20186.md)
	- Dia juga berusaha
		- Seorang sahabat bertanya:“Wahai Rasulullah, apakah aku harus mengikat untaku atau bertawakal?”Beliau menjawab:“Ikatlah (untamu) dan bertawakallah.”(HR. Tirmidzi no. 2517)
		- [QS. An-Najm 53:39](Quran/QS.%20An-Najm%2053%20-%2039.md)
		- Dari Umar bin Khattab:“…burung keluar pagi dalam keadaan lapar dan pulang sore dalam keadaan kenyang…”(HR. Tirmidzi no. 2344) burung nya keluar dulu (usaha dulu), diiringi tawakal.
		- [QS. Al-Ankabut 29:69](Quran/QS.%20Al-Ankabut%2029%20-%2069.md)
		- Hadis:“Sesungguhnya Allah mencintai jika salah seorang di antara kalian melakukan suatu pekerjaan, dia melakukannya dengan itqan (profesional/sempurna).”(HR. Al-Baihaqi dalam Syu’abul Iman)
		- [QS. Al-Mulk 67:2](Quran/QS.%20Al-Mulk%2067%20-%202.md)
		- Dari Az-Zubair bin Al-Awwam:“Nabi ﷺ memakai dua baju besi pada hari Uhud.”(HR. Bukhari dan Muslim) - artinya nabi berusaha dengan memakai baju perang dua lapis padahal Nabi adalah manusia yang paling bagus tawakal nya.
	- Dia sudah berusaha, diiringi dengan konsisten
		- Hadis:“Amalan yang paling dicintai Allah adalah yang paling terus-menerus meskipun sedikit.”(HR. Aisyah binti Abu Bakar, riwayat Bukhari & Muslim)
	- Dia sudah meminta kepada tuhan nya, dia juga sudah berusaha, sekarang dia berserah diri.
		- [QS. Ali Imran 3:159](Quran/QS.%20Ali%20Imran%203%20-%20159.md)

## Pengaruh Usaha dalam Graph Takdir

Kaidah:
* takdir tidak menghapus hukum sebab akibat.
* usaha tidak bisa melepaskan diri dari takdir.
Mengapa harus usaha:
* lakukan sebab, contoh:
	* jika ingin kenyang, maka makan.
	* jika ingin punya anak, maka menikah, meskipun menikah tidak menjamin punya anak, kalau tidak menikah dipastikan tidak punya anak.
* dituntut oleh syariat
	* [QS An-Najm 39](Quran/QS.%20An-Najm%2053%20-%2039.md)
	* [QS At-Taubah 105](Quran/QS.%20At-Taubah%209%20-%20105.md)
	- [QS Al-Baqarah 286](Quran/QS.%20Al-Baqarah%202%20-%20286.md)
- Bagian dari proses tawakal
- Ikhtiar tidak bisa melepaskan diri dari takdir. Kenapa dilakukan?
	- Karena diperintahkan dalam syariat: QS. [QS. Yusuf 12:67-68](Quran/QS.%20Yusuf%2012%20-%2067%20sampai%2068.md)
	- Karena manusia pindah node takdir dan akan membuka jalan baru [QS. Al-Balad 90:10](Quran/QS.%20Al-Balad%2090%20-%2010.md).
## Petunjuk Allah dalam Graph Takdir
Pertanyaan inti, kalau:
- manusia memilih jalan (edge)
- takdir sudah ditulis

❓ **Lalu di mana peran hidayah Allah?**

➡️ Jawaban:

> **Hidayah = kemampuan melihat dan memilih edge yang benar** 

Posisi Hidayah dalam GRAPH:
- **Node** → kondisi hidup
- **Edge** → pilihan
- **Doa** → usaha membuka jalur
- **Hidayah** → **penerangan jalur**

👉 Maka:

> **Hidayah = cahaya yang membuat kita tahu edge mana yang benar**

### Allah memberi hidayah pada manusia

📖 [QS. Al-Qaṣaṣ 28 - 56](Quran/QS.%20Al-Qaṣaṣ%2028%20-%2056.md)
> **إِنَّكَ لَا تَهْدِي مَنْ أَحْبَبْتَ وَلَٰكِنَّ اللَّهَ يَهْدِي مَنْ يَشَاءُ**
> 
> _“Engkau tidak dapat memberi hidayah kepada orang yang engkau cintai, tetapi Allah memberi hidayah kepada siapa yang Dia kehendaki.”_

➡️ Bahkan Nabi pun:
- tidak mengontrol hidayah
- hanya menyampaikan

📖 [QS. Muhammad 47 - 17](Quran/QS.%20Muhammad%2047%20-%2017.md)

> **وَالَّذِينَ اهْتَدَوْا زَادَهُمْ هُدًى**
> 
> _“Orang-orang yang mengikuti petunjuk, Allah tambahkan hidayah bagi mereka.”_

➡️ Artinya:
- hidayah itu **bertumbuh**
- seperti traversal yang makin benar

### Allah bisa menyesatkan manusia

📖 [QS. Ash-Shaff 61 - 5](Quran/QS.%20Ash-Shaff%2061%20-%205.md)

> _“Ketika mereka menyimpang, Allah memalingkan hati mereka.”_

➡️ Dalam graph:
- sering pilih edge salah
- → makin sulit melihat kebenaran

## Kesalahan umum

### Membandingkan graph takdir-mu dengan takdir orang lain

#### 1. Bentuk kesalahan

Contoh yang sering terjadi:

- “Kenapa dia santai tapi kaya?”
- “Saya sudah taat, kok hidup saya sulit?”
- “Dia tidak serius, tapi sukses…”

➡️ Ini semua adalah:

> **membandingkan node berbeda dalam graph yang berbeda**

#### 2. Masalah utamanya (dalam GRAPH)

Dalam model kita:

- setiap orang punya **graph sendiri**
- node (kondisi hidup) berbeda
- jalur (path) berbeda
- ujian berbeda

👉 Tapi manusia:

> **membandingkan node A miliknya dengan node B milik orang lain**

➡️ Ini error logika.

#### 3. Dalil larangan membandingkan (hasad)

📖 [QS. An-Nisa 4 - 32](Quran/QS.%20An-Nisa%204%20-%2032.md)

> **وَلَا تَتَمَنَّوْا مَا فَضَّلَ اللَّهُ بِهِ بَعْضَكُمْ عَلَىٰ بَعْضٍ**
> 
> _“Janganlah kalian iri terhadap apa yang Allah lebihkan sebagian kalian atas sebagian yang lain.”_


#### 4. Dalil: pembagian sudah ditentukan

📖 [QS. Az-Zukhruf 43 - 32](Quran/QS.%20Az-Zukhruf%2043%20-%2032.md)

> _“Kami yang membagi penghidupan mereka dalam kehidupan dunia…”_

➡️ Artinya:

- distribusi:
    - kaya / miskin
    - mudah / sulit  
        ➡️ **bagian dari graph yang sudah ditetapkan**

#### 5. Kenapa ini berbahaya?

##### ❌ 1. Melahirkan hasad

→ tidak ridha dengan graph sendiri

##### ❌ 2. Menuduh Allah tidak adil (secara implisit)

→ “Kenapa dia dapat, saya tidak?”

##### ❌ 3. Salah fokus

→ sibuk lihat node orang lain  
→ lupa memilih edge sendiri

### Merubah takdir

> **“Saya bisa merubah takdir”** atau sebaliknya  
> **“Takdir tidak bisa diapa-apakan sama sekali”**

Keduanya **tidak tepat**. 

#### 1. Bentuk kesalahan

Ada dua ekstrem:

##### ❌ A. Merasa bisa mengubah takdir sepenuhnya

- “Saya tentukan hidup saya sendiri”
- “Semua tergantung usaha saya”

➡️ ini mengabaikan Allah

##### ❌ B. Fatalisme (pasrah total)

- “Ngapain usaha, sudah ditulis”
- “Doa tidak ada gunanya”

➡️ ini mematikan ikhtiar

---

#### 2. Koreksi: Takdir tidak diubah, tapi **dijalani**

Dalam kerangka GRAPH:

- **Graph (struktur)** → sudah ditulis, tidak bisa diubah
- **Traversal (jalur yang ditempuh)** → kita pilih, inilah bentuk usaha kita.

👉 Jadi:

> **Kita tidak mengubah graph,  
> kita memilih jalur di dalam graph**

Perkataan Umar bin Khattab:

> _“Kami lari dari satu takdir Allah menuju takdir Allah yang lain.”_

📚 Sumber:

- **Sahih al-Bukhari no. 5729**

➡️ Ini kunci:

> bukan keluar dari takdir,  
> tapi berpindah antar jalur dalam takdir

---

## Hikmah beriman pada Takdir

### Tidak sombong

Beriman kepada takdir membuat manusia tidak sombong, sebab dia memandang semua pencapaian berasal dari Allah

📖 [QS. Al-Kahfi 18 - 39](Quran/QS.%20Al-Kahfi%2018%20-%2039.md)

> _“Mā shā’aLlāh, lā quwwata illā billāh”_  
> _(Semua ini atas kehendak Allah, tidak ada kekuatan kecuali dengan-Nya)_

📖 [QS. An-Naml 27 - 40](Quran/QS.%20An-Naml%2027%20-%2040.md)

> **هَٰذَا مِن فَضْلِ رَبِّي لِيَبْلُوَنِي أَأَشْكُرُ أَمْ أَكْفُرُ ۖ وَمَن شَكَرَ فَإِنَّمَا يَشْكُرُ لِنَفْسِهِ ۖ وَمَن كَفَرَ فَإِنَّ رَبِّي غَنِيٌّ كَرِيمٌ**

Terjemah inti:

> _“Ini termasuk karunia (فضل) dari Tuhanku, untuk mengujiku apakah aku bersyukur atau kufur…”_

Dalil bahwa tanpa iman kepada takdir membawa pada kesombongan, kisah Qorun:

📖 [QS. Al-Qaṣaṣ 28 - 78](Quran/QS.%20Al-Qaṣaṣ%2028%20-%2078.md)
> _“Sesungguhnya aku diberi harta itu karena ilmu yang ada padaku.”_  

### Tidak putus asa

#### 1. Akar keputusasaan

Putus asa muncul ketika seseorang merasa:

- “Hidup saya sudah hancur”
- “Tidak ada jalan lagi”
- “Semua sudah terlambat”

➡️ Dalam bahasa GRAPH:

> dia mengira **sudah tidak ada edge (jalan keluar) lagi**

#### 2. Koreksi: Graph Allah selalu punya jalur

Selama masih hidup, manusia selalu punya node berikutnya [QS. Al-Balad 90 - 10](Quran/QS.%20Al-Balad%2090%20-%2010.md)

👉 Artinya:

> **selalu ada kemungkinan jalur baru**

#### 3. Dalil larangan putus asa

📖 [QS. Az-Zumar 39 - 53](Quran/QS.%20Az-Zumar%2039%20-%2053.md)

> **لَا تَقْنَطُوا مِن رَّحْمَةِ اللَّهِ**
> 
> _“Janganlah kalian berputus asa dari rahmat Allah.”_

➡️ Ini larangan tegas:

> putus asa = tidak memahami keluasan graph Allah

#### 4. Dalil: Allah memberi jalan keluar

📖 [QS. At-Talaq 65 - 2 sampai 3](Quran/QS.%20At-Talaq%2065%20-%202%20sampai%203.md)

> _“Barang siapa bertakwa kepada Allah, niscaya Dia akan menjadikan baginya jalan keluar dan memberinya rezeki dari arah yang tidak disangka-sangka.”_

➡️ Dalam GRAPH:

> Allah bisa membuka **edge yang tidak terlihat sebelumnya**


---

📖 Kembali ke:
[Iman kepada takdir](iman-kepada-takdir.md)
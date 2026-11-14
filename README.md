# Materi Termoelektrik: Oksida Logam Transisi

## Gambaran umum

Termoelektrik adalah fenomena ketika perbedaan suhu menghasilkan tegangan listrik, atau ketika arus listrik memindahkan panas. Karena dapat mengubah panas langsung menjadi listrik tanpa bagian bergerak, bahan termoelektrik (TE) berpotensi digunakan untuk pemulihan panas buangan, pendinginan, sensor, dan sumber daya berukuran kecil.

Materi ini merangkum artikel tinjauan **“Transition metal oxides – Thermoelectric properties”** oleh Walia dkk. Artikel tersebut membahas oksida logam transisi (*transition metal oxides*, TMOs), termasuk oksida titanium, mangan, tungsten, seng, tembaga, vanadium, kobalt, rhodium, dan molibdenum. Sifat listrik dan panasnya dapat disetel melalui komposisi, doping, struktur, serta ukuran material. Stabilitas pada suhu tinggi, pilihan metode sintesis yang beragam, dan ketersediaan sejumlah oksida menjadi alasan material ini menarik untuk diteliti.

> **Catatan ruang lingkup:** sumber utama terbit pada 2013. Nilai kinerja dan contoh di bawah adalah hasil studi yang dirangkum dalam artikel tersebut; nilainya bergantung pada komposisi, struktur, metode pembuatan, dan suhu pengukuran, sehingga tidak dapat dibandingkan langsung tanpa konteks.

## Prinsip dan parameter utama

### Efek Seebeck

Jika kedua ujung bahan berada pada suhu berbeda, pembawa muatan bergerak dan menimbulkan beda potensial. Secara sederhana:

`ΔV ≈ S ΔT`

`S` adalah koefisien Seebeck (V/K), `ΔT` perbedaan suhu, dan `ΔV` tegangan yang dihasilkan. Tanda `S` berkaitan dengan jenis pembawa muatan dominan: elektron (tipe-n) atau lubang (tipe-p).

### Daya hantar listrik

Konduktivitas listrik `σ` (S/m) menggambarkan kemudahan arus mengalir. Pada oksida, nilainya dapat diubah dengan mengatur konsentrasi pembawa muatan—misalnya melalui doping atau kekurangan oksigen. Konduktivitas yang tinggi membantu menghasilkan daya, tetapi juga meningkatkan kontribusi elektron terhadap hantaran panas.

### Konduktivitas termal

Konduktivitas termal total dapat dipandang sebagai gabungan kontribusi kisi dan elektron:

`κ = κ_kisi + κ_elektron`

Pada banyak oksida semikonduktor, fonon yang merambat pada kisi menjadi penyumbang utama. Hamburan fonon oleh cacat kristal, batas butir, antarmuka, atau struktur berukuran nano dapat menurunkan `κ_kisi`. Untuk kontribusi elektron, pendekatan hukum Wiedemann–Franz menyatakan `κ_elektron ≈ LσT`, dengan `L` bilangan Lorenz dan `T` suhu mutlak.

### Faktor daya dan angka mutu

Dua ukuran yang umum dipakai adalah:

- **Faktor daya termoelektrik (TPF/PF):** `PF = S²σ`
- **Angka mutu tak berdimensi:** `ZT = S²σT/κ = PF·T/κ`

Nilai `ZT` yang lebih tinggi menandakan potensi konversi termoelektrik yang lebih baik. Sasaran rekayasa umumnya adalah memperoleh `S` dan `σ` yang tinggi sekaligus `κ` yang rendah. Sasaran tersebut tidak mudah dicapai karena parameter-parameter itu saling berhubungan: menaikkan konsentrasi pembawa muatan, misalnya, sering meningkatkan `σ` tetapi dapat menurunkan `S`.

## Cara meningkatkan kinerja oksida

Strategi yang dibahas dalam tinjauan meliputi:

1. **Mengatur stoikiometri dan doping** — perubahan kadar oksigen atau penambahan dopan mengubah konsentrasi pembawa muatan, tingkat energi, dan cacat kristal. Hal ini dapat menaikkan `σ` sekaligus menambah hamburan fonon.
2. **Nanostrukturisasi** — struktur nano menciptakan batas dan antarmuka yang menghamburkan fonon. Pengurungan kuantum juga dapat mengubah kerapatan keadaan elektronik dan koefisien Seebeck.
3. **Substruktur atau pelapisan berlapis** — bagian yang menghantarkan elektron dapat dipadukan dengan lapisan yang kuat menghamburkan fonon. Oksida kobalt berlapis menjadi contoh penting pendekatan ini.
4. **Membuat komposit** — fase kedua atau partikel terdispersi dapat menambah antarmuka dan mengubah hantaran panas maupun listrik.
5. **Mengatur dimensi** — sumur kuantum 2D, kawat nano 1D, serta struktur berdimensi nol seperti *quantum-dot superlattice* atau kawat nano bersegmen berpotensi mengubah kerapatan keadaan dan lintasan fonon. Prediksi untuk struktur 0D menjanjikan, tetapi menurut artikel tersebut riset eksperimentalnya masih terbatas.

Strategi terbaik bergantung pada penggunaan. Pendinginan dan pemanenan panas umumnya diuntungkan oleh faktor daya tinggi dan konduktivitas termal rendah. Sensor suhu memerlukan koefisien Seebeck tinggi agar sinyal tegangan mudah dibaca. Sebaliknya, sumber gelombang termopower juga memerlukan hantaran panas yang cukup untuk mendukung perambatan gelombang panas.

## Contoh material dalam tinjauan

| Material atau sistem | Temuan yang disorot | Implikasi |
|---|---|---|
| **TiO₂ / TiOₓ** | TiO₂ stoikiometrik memiliki `ZT` rendah (dilaporkan `< 0,025`), sedangkan reduksi, doping, dan pembentukan antarmuka dapat memperbaiki kinerjanya. Struktur dua dimensi berbasis SrTiO₃ juga menunjukkan potensi besar dalam studi yang dirangkum. | Contoh kuat bahwa pengaturan kekurangan oksigen dan dimensi dapat mengubah sifat TE. |
| **MnO₂ dan CaMnO₃** | Film tipis MnO₂ dilaporkan memiliki `S` sekitar 1900 µV/K dan PF sekitar 3600 µW/(m·K²) pada 623 K. CaMnO₃ yang didoping merupakan kandidat tipe-n pada suhu tinggi. | Menarik untuk pemanenan panas, meskipun PF tinggi tidak otomatis berarti `ZT` tinggi. |
| **ZnO** | Doping Al dan kombinasi dopan seperti Al–Ga dapat meningkatkan PF dan menurunkan hantaran panas. Artikel melaporkan `ZT` hingga sekitar 0,65 pada 1247 K untuk komposisi ZnO terdoping Al–Ga tertentu. | Salah satu kandidat oksida tipe-n untuk pemulihan panas suhu tinggi. |
| **Oksida kobalt berlapis** | NaₓCoO₂ dan Ca₃Co₄O₉ menggabungkan lapisan penghantar listrik dengan lapisan yang membantu menghamburkan fonon. Nilai `ZT` yang dilaporkan mencapai sekitar 0,75 untuk kristal NaCo₂O₄ pada suhu ruang dan sekitar 0,5 untuk komposit Ca₃Co₄O₉ tertentu pada 1000 K. | Contoh pendekatan substruktur untuk memperoleh hantaran listrik baik dan hantaran panas lebih rendah. |
| **CuO, Cu₂O, dan La₂CuO₄** | Hasil bergantung kuat pada fase, stoikiometri, dan doping; artikel juga mencatat bahwa data termoelektrik lengkap untuk beberapa bentuk intrinsik masih terbatas. | Menunjukkan pentingnya mengukur `S`, `σ`, dan `κ` pada sampel serta kondisi yang sama. |
| **V₂O₅** | Bahan murni umumnya dibatasi konduktivitas listrik yang rendah; hidrasi, nanostrukturisasi, dan doping dapat mengubah PF. | Dapat dipertimbangkan untuk sensor atau aplikasi tertentu, tetapi peningkatan `σ` tetap menjadi tantangan. |
| **Oksida lain** | Fe₂O₃, CdO, NiO terdoping, dan komposit ZrO₂/CoSb₃ juga menunjukkan hasil yang menarik dalam studi tertentu. | Kandidat tambahan, dengan tingkat bukti dan kesiapan yang beragam. |

Angka pada tabel merupakan contoh hasil penelitian yang dikutip oleh artikel, bukan spesifikasi baku material. Nilai PF menggunakan satuan µW/(m·K²); nilai `ZT` tidak berdimensi.

## Aplikasi potensial

- **Pendinginan dan refrigerasi:** modul TE dapat memindahkan panas saat dialiri arus. Susunan elemen tipe-p dan tipe-n memungkinkan pendinginan lokal, misalnya untuk pengendalian suhu komponen elektronik atau sensor.
- **Pemanenan panas buangan:** generator TE dapat mengubah panas dari knalpot kendaraan atau proses industri menjadi listrik. Stabilitas oksida pada suhu tinggi menjadikannya menarik, tetapi efisiensi dan daya keluaran modul masih perlu ditingkatkan.
- **Generator termoelektrik surya (STEG):** panas terkonsentrasi dari matahari dimanfaatkan untuk membentuk gradien suhu pada elemen TE; sistem ini dapat melengkapi sel fotovoltaik.
- **Generator termoelektrik radioisotop (RITEG):** sumber panas dari peluruhan radioisotop dapat dikonversi menjadi listrik untuk sistem yang memerlukan operasi lama dan andal, seperti misi antariksa.
- **Sensor suhu, gas, dan biologis:** perubahan tegangan Seebeck dapat digunakan untuk mendeteksi suhu atau panas yang timbul dalam reaksi kimia dan proses biologis. Beberapa oksida juga digunakan dalam sensor gas.
- **Sumber gelombang termopower:** reaksi eksotermik yang merambat melalui material penghantar dapat menghasilkan tegangan. Tinjauan menyoroti ZnO dan MnO₂ sebagai contoh oksida yang menghasilkan tegangan besar pada sistem yang dilaporkan.

## Tantangan dan arah pengembangan

Tantangan utama yang ditekankan artikel adalah efisiensi material dan modul yang masih terbatas, serta pemahaman yang belum lengkap mengenai transpor fonon dan elektron pada cacat, batas butir, dan antarmuka. Efek doping dan kekurangan oksigen juga tidak selalu sama untuk setiap oksida atau kondisi sintesis. Selain itu, data pada rentang suhu yang luas belum tersedia untuk banyak material.

Pengembangan selanjutnya memerlukan:

- pengukuran `S`, `σ`, dan `κ` secara konsisten pada komposisi, fase, dan rentang suhu yang sama;
- pengendalian struktur, ukuran butir, antarmuka, stoikiometri, dan konsentrasi dopan selama sintesis;
- pemodelan transpor yang lebih baik untuk bahan kompleks dan berstruktur nano;
- pengujian modul lengkap, bukan hanya sampel material, untuk menilai daya, efisiensi, stabilitas, dan skalabilitas;
- penelitian lebih lanjut pada struktur 0D dan material berlapis/komposit.

## Ringkasan

Oksida logam transisi menawarkan kombinasi stabilitas termal, fleksibilitas rekayasa, dan potensi biaya yang menarik untuk teknologi termoelektrik. Kinerja terbaik tidak ditentukan oleh satu parameter saja: `S`, `σ`, dan `κ` perlu dioptimalkan bersama untuk suhu serta aplikasi tertentu. Doping, pengaturan stoikiometri, nanostrukturisasi, substruktur, dan komposit merupakan alat utama untuk mengupayakannya, tetapi efisiensi rendah serta pemahaman transpor yang belum tuntas masih menjadi hambatan.

## Sumber

Walia, S. dkk. “Transition metal oxides – Thermoelectric properties.” *Progress in Materials Science*, volume 58 (2013), hlm. 1443–1489. [https://doi.org/10.1016/j.pmatsci.2013.06.003](https://doi.org/10.1016/j.pmatsci.2013.06.003)
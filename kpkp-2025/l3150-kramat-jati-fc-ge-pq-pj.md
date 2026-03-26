# L3150 Kramat Jati (FC, GE, PQ, PJ)

<figure><img src="../.gitbook/assets/IMG_20250721_115720.jpg" alt="" width="375"><figcaption></figcaption></figure>

## A. Analisa dan indikasi

* Full counter: tidak bisa print karena cycle print sudah lewat batas, minta di reset via software
* General Error: disk encoder copot dari gear, harus di lem ulang
* Print quality: hasil print kacau, tidak ada warna hitam yang keluar, bahkan warna hanya sedikit bayangan saja
* Paper jam:&#x20;
  * saat print kertas berhenti ditengah-tengah
  * saat print kertas los, kemungkinan ada gear ompong

## B. Action

### B1. Waste Inkpad counter

<figure><img src="../.gitbook/assets/IMG_20250721_091059.jpg" alt=""><figcaption></figcaption></figure>

Saat posisi lampu indikator seperti berikut menunjukkan printer dalam keadaan full counter. Maka printer tidak bisa dipakai.

<figure><img src="../.gitbook/assets/IMG_20250721_091144.jpg" alt=""><figcaption></figcaption></figure>

Terlihat poin _pad counter_ dan setelah di _initialize_ untuk mereset poin ke angka 0 agar printer bisa kembali digunakan.

{% hint style="info" %}
Ditahap ini printer sudah bisa printing untuk mengetes hasil cetakan nozzlenya
{% endhint %}

<figure><img src="../.gitbook/assets/IMG_20250721_155645.jpg" alt=""><figcaption><p>Hasil print test</p></figcaption></figure>

{% hint style="info" %}
Hasil print kacau

warna hitam sama sekali tidak keluar, warna cyan, magenta, yellow hanya sedikit
{% endhint %}

### B2. Service Adapter/CISS

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td>sebelum</td><td><a href="../.gitbook/assets/IMG_20250721_141029.jpg">IMG_20250721_141029.jpg</a></td></tr><tr><td>sesudah</td><td><a href="../.gitbook/assets/IMG_20250721_141053.jpg">IMG_20250721_141053.jpg</a></td></tr><tr><td>refill</td><td><a href="../.gitbook/assets/IMG_20250721_141138.jpg">IMG_20250721_141138.jpg</a></td></tr></tbody></table>

{% hint style="info" %}
part ini masih bagus, gelembung udara dan tidak mudah terbentuk didalam adapter sehingga tinta didalam adapter/CISS full
{% endhint %}

### B3. Service Print Head + Power ink flushing

{% embed url="https://youtube.com/shorts/ojr3Kvjq644" %}

{% hint style="info" %}
Hasil refurbish

kuning dan biru belum sempurna, karena ada bending sedikit. Merah dan hitam hampir bagus (untuk print standard harusnya masih meninggalkan garis)
{% endhint %}

<figure><img src="../.gitbook/assets/IMG_20250721_142617 (1).jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Hasil power ink flushing dan refurbish print head

tinta hitam keluar
{% endhint %}

<figure><img src="../.gitbook/assets/IMG_20250721_144134.jpg" alt=""><figcaption><p>Setelah action</p></figcaption></figure>

{% hint style="info" %}
Hasil akhir

kesimpulannya dengan hasil cetak yang tidak sesuai dengan hasil keluaran warna saat refurbish (disaat ciss adapter kondisinya bagus) maka dinyatakan problem bukan dari hanya dari print head.&#x20;
{% endhint %}

Maka, dilanjut cek ink system

### B4. Check Ink system

<figure><img src="../.gitbook/assets/IMG_20250721_152420.jpg" alt=""><figcaption></figcaption></figure>

Setelah dilakukan pengetesan menarik tinta ink system dari selang pembuangan ternyata tidak ada tinta yang tertarik walaupun posisi print head sudah tepat diatas ink system

{% hint style="info" %}
Kesimpulan

problem print quality ada 2 part yang menjadi perhatian yaitu print head dan ink system
{% endhint %}

### B5. Service Disk encoder + check gear dan karet shaft/pickup roller

<figure><img src="../.gitbook/assets/IMG_20250721_093254.jpg" alt=""><figcaption></figcaption></figure>

disk encoder dan sensor dibersihkan, lalu dilem ulang agar pergerakan kertas keluar terbaca baik di sensor.

{% hint style="info" %}
part masih bisa di service dan berfungsi normal
{% endhint %}

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td>gear &#x26; clutch</td><td><a href="../.gitbook/assets/IMG_20250715_170022.jpg">IMG_20250715_170022.jpg</a></td></tr><tr><td>gear 2</td><td><a href="../.gitbook/assets/IMG_20250715_170037.jpg">IMG_20250715_170037.jpg</a></td></tr><tr><td>gear 3</td><td><a href="../.gitbook/assets/IMG_20250715_170029.jpg">IMG_20250715_170029.jpg</a></td></tr></tbody></table>

{% hint style="info" %}
gerigi masih kokoh belum ada yang ompong

Kesimpulannya, problem paper jam dan _nge-lost_ disebabkan oler kotornya dan kurang menempelnya disk encoder pada gear sisi kiri. Namun, disarankan ganti baru karena yang lama sudah pengok
{% endhint %}

## C. Request Sparepart

* Print Head
* Ink system L3150
* Disk encoder
* Kabel Scanner

## D. Update

* [ ] Print Head (ID: 38E88 77POX)
  * [x] repair dengan cleaner 8 jam (27 Juli 2025)
  * [x] repair dengan spuit refurbish (27 Juli 2025)
  * [ ] replace
* [ ] Mainboard sort di mosfet setelah head cleaning

Hasil Print Head setelah di repair

* Hitam:  banyak bolong dan bending
* Kuning: bending dikit
* Merah: bolong dikit
* Biru: bolong dikit

- [ ] Ink

## E. Request Part (Update 27 Juli 2025)

* Print Head L3150&#x20;
  * Rp700.000 (kenalan pic: Mamat)&#x20;
    * Rp997.500 (FastPrint Jakarta)
* mosfet L3150 1 set&#x20;
  * Rp9.500 (FixPrint Jakarta)
















<html>
<body>
<h1><p align="center">Software Requirements Spesification</p></h1>

<p align="center"><b>Version 1.0.5 </b><br>
<p align="center">12 Februari 2018</b><br><br>
<p align="center">
<img src="http://i67.tinypic.com/2yuhmww.png"/>
</p>

<br><p align="center"><b> APLIKASI POS QR-CODE ANDROID</b><br>
<p align="center"><b>Aplikasi Menggunakan Kode QR
</b>
<p align="center">Kelompok 2<br>
 Mochamad Faizal 			(1603179)<br>
 Luqmanul Hakim				(1603076)<br>
 Inneke Widianti			(1603072)<br>
 Rizaluddin Sidqi Baihaqi	(1603082)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b><br>
<p align="center"><b>2018</b><br><br>
</p>
</body>
</html>

##
### BAB I Pendahuluan
Dokumen ini berisi penjelasan pemakaian dan penulisan dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Specification (SRS). Dokumen ini selanjutnya akan menggunakan istilah SRS.

Software Requirement Specification (SRS) menjelaskan berbagai macam kebutuhan pembuatan produk, yaitu kebutuhan spesifik yang terdiri dari kebutuhan fungsionalitas, termasukdidalamnya input, proses, dan output dari produk dan non-fungsionalitas. Kebutuhan antar muka juga digambarkan dengan jelas di dalam dokumen ini, terdiri dari kebutuhan antar pengguna, antar hardware yang menjelaskan kebutuhan yang harus ada untuk menjalankan atau mengoperasikan aplikasi sistem, kebutuhan antar software yang menjelaskan bagaimana cara pengguna berinteraksi dengan sistem, dan kebutuhan antar komunikasi.

Dokumen ini dibuat untuk membantu membuat spesifikasi perangkat lunak yang akan dikembangkan dengan rancangan berorientasi proses. Pada prinsipnya, hasil analisis sistem perangkat lunak dengan rancangan ini diuraikan sebagai sekumpulan proses yang terorganisasi secara hirarkis, memberikan solusi, batasan masalah agar proyek tidak menyimpang terlalu jauh dari tujuan awal, dan manfaat dari sistem informasi yang akan dibuat. Software Requirement Spesification ini dapat dijadikan acuan agar proyek dapat berjalan dengan lancar selama pengerjaannya.

__1.1 Tujuan__
<br>Tujuan dari dokumen Software Requirement Specification (SRS) ini adalah memberikan gambaran yang spesifik dari kebutuhan software. Spesifikasi kebutuhan tersebut termasuk dari segi perangkat lunak dan perangkat keras, untuk memberikan gambaran dan penjelasan mengenai pembuatan produk, penjelasan hal-hal yang dibutuhkan untuk pembuatan produk termasuk kebutuhan fungsional hingga nonfungsional, dan kebutuhan antar muka mulai dari antar muka pengguna hingga antar muka komunikasi.

__1.2 Lingkup__
<br>Semua hal yang tercantum didalam dokumen ini merupakan bagian dari ruang lingkup kebutuhan pembangunan perangkat lunak yang berupa aplikasi kasir QR Code berbasis android yang digunakan untuk perhitugan keuangan pada toko-toko.

__1.3 Definisi, Akronim dan Singkatan__
<br>

Definisi, Akronim dan Singkatan | Penjelasan |
-----------------|---------------------------
SRS/SKPL | adalah dokumen yang menggambarkan secara detail spesifikasi kebutuhan software dalam pembangunan proyek perangkat lunak Aplikasi Kasir QR Code Berbasis Android.|
DFD | adalah suatu diagram yang menggunakan notasi-notasi untuk menggambarkan arus dari data pada suatu sistem atau menjelaskan proses kerja suatu sistem, yang penggunaannya sangat membantu untuk memahami sistem secara logika, tersruktur dan jelas.|
Software | Perangkat Lunak.|
Hardware | Perangkat Keras|
SRS | Software Requirements Specification.|
SKPL | Spesifikasi Kebutuhan Perangkat Lunak.|
DFD | Data Flow Diagram|
IEEE | The Institute of Electrical and Electronics Engineers|

__1.4 References__
<br>
- IEEE Std. 830-1998, IEEE Recommended Practice for Software Requirement Specifications.

__1.5 Overview__
<br>Dokumen SRS ini merupakan acuan untuk mengetahui spesifikasi kebutuhan dalam menyelesaikan proyek ini. Dokumen SRS ini berisi tentang deskripsi tentang kebutuhan perangkat lunak (tools pendukung, peranangan sistem yang akan dikembangkan), perangkat keras, dan sumber daya manusia (SDM)

### BAB II GAMBARAN UMUM
Pada umumnya toko-toko yang tidak terlalu besar metode transaksi pembayarannya manual seperti ditulis dikertas lalu di jumlah dengan kalkulator, dengan metode seperti itu memakan waktu dan tidak efisien, karena untuk transaksi pembayaran harus cepat dan tepat patal jadinya jika penghitungan salah, toko dapat merugi, ditambah pohon-pohon yang ada di muka semakin menipis, ini terjadi karena pohon menjadi bahan baku pembuatan kertas, semakin sedikitnya pohon, bumi semakin panas dan cuaca pun tidak menentu, dan sudah jelas kerusakan alam sudah mulai terlihat akibat pohon-pohon dimuka bumi ini berkurang.

Oleh karena itu kelompok kami mempunyai ide yang mungkin dapat meminimalisir penggunaan kertas secara berlebihan, yaitu dengan membuat aplikasi point of sales dengan QR-Code berbasis android. Aplikasi menggunakan sistem scan kode QR untuk setiap jenisa makanan yang dijual pada toko-toko, dari sistemnya sendirinya digunakan oleh 4 user, yaitu pembeli, kasir/karyawan, pemilik toko dan admin.

Dari sistem pembeli menggunakan imei dan nomor telpon untuk mendaftar kan smartphonenya, jiak imei nya sudah didaftar kan dan di data diri diisi dengan data pembeli maka aplikasi tersebut sudah bisa digunakan. Pada sistem pembeli terdapat beberapa fungsi utama yaitu :
<ul><li> Pembeli dapat melihat harga makanan dengan melakukan sca QR Code.</li>
<li> Pembeli dapat melakukan Top Up agar pada saat transaksi pembayaran tidak mengeluarkan uang cash.</li>
<li> Pembeli dapat melihat jumlah harga dari makanan yang dibeli.</li>
<li> Rincian pembeli langsung diterima oleh kasir setelah pembeli selesai melakukan memilih makanan yang akan mereka beli.</li>
</ul>

Pada sitem karyawan memiliki fungsi utama yaitu :
<ul>
<li> Menerima rincian pembelian.</li>
<li> Mengisi dompet elektronik pembeli(Top Up).</li>
<li> Mamasukan data barang.</li>
<li> Transaksi pembayaran.</li>
</ul>

Pada sistem pemilik toko memiliki fungsi utama yaitu :
<ul>
<li> Melihat rekap data bulanan.</li>
<li> Melihat omset bulanan. </li>
<li> Melihat data barang. </li>
</ul>

Admin disini adalah super user yang mengelola setiap data sistem ini. Sistem admin memiliki beberpa fungi utama yaitu :
<ul>
<li> Menerima data pada tiap-tiap toko.</li>
<li> Aprovement jika ada pembel yang mendaftar.</li>
<li> Presentase jumlah produk yang banyak terjual pada tiap-tiap toko perbulan secara otomatis.</li>
</ul>

__2.1 Perspektif produk__
<br>Aplikasi point of sales dengan QR-Code berbasis android adalah sebuah sistem transaksi pembayaran yang diaplikaskan pada android. Dimana user dari aplikasi ini pembeli, kasir/karyawan, pemilik toko sedangkan untuk pengolahan datanya dikelola oleh admin yang menggunakan sistem web.

Pada sisem QR Kode mengunakan dara tiap jenia makanan yang dijual ditoko. Data tersebut di enkripsi menjadi sebuah kode QR. kode tersebut akan ditempel pada setiap baris pada jenis makanan yang ada di toko, tujuannya agar pembeli dapat dengan mudah melakukan scan untuk melihat harga pada tiap makanan atau membelinya dengan cara melakukan scan terlebih dahulu. Sebelum pembeli menggunakan aplikasi ini, pembeli diwajibkan mendaftar dengan imek hanphone masing-masing dan nomor handphone tersebut.

Pada sistem pembeli, dapat melakukan scan QR pada tiap-tiap jenis makanan yang ditoko, dan membeli dengan jumlah yang di inginkan, setelah melakukan pembelian, makanan dicek dikasir untuk dicocokan dengan data yang ada pada aplikasi, jika data dana barang sudah benar, lalu penghitungan, setelah pembayaran, struk digital pun langsung dikirim pada aplikasi pembeli. Pada sistem kasir/karyawan, dapat melihat makanan apa saja yang pembeli beli,lalu dihitung.

____2.1.1 Antarmuka sistem____

<br>Dalam penggunaan & pengguna berinteraksi langsung dengan aplikasi melalui android.

![](http://i63.tinypic.com/ri9ouf.jpg)

____2.1.2 Antarmuka pengguna____
<div>
	<table>
		<tr align="center">
			<td><b>Icon Aplikasi</b></td>
			<td><b>Splashscreen</b></td>
			<td width="300"><b>Sign In</b></td>
		</tr>
		<tr  valign="top" align="center">
				<td><img src="http://i66.tinypic.com/30cyg7q.png" width="180" height="350" /><br><p align="justify">Ini adalah tampilan ikon aplikasi Q-Pay pada menu di Smartphone.</p></td>
				<td><img src="http://i65.tinypic.com/k48ms7.png" width="180" height="350" /><br><p align="justify">Splashscreen adalah tampilan awal saat aplikasi dibuka, pada aplikasi kami tampilan awalnya beupa logo dan nama aplikasi.</p></td>
				<td><img src="http://i64.tinypic.com/rr73uh.png" width="180" height="350" /><br><p align="justify">Pada tampilan sign in ini user akan memasukkan username dan password untuk bisa masuk ke tampilan dashboard, pada platform android terdapat  2 user yaitu member dan karyawan, kemudian setelah berhasil login akan secara otomatis diarahkan ke menu dari masing-masing user.</p></td>		
		</tr>
		<tr align="center">
			<td><b>Sign Up</td>
			<td><b>Dashboard Member</td>
			<td><b>Navbar Menu</td>
		</tr>
		<tr valign="top" align="center">
				<td><img src="http://i64.tinypic.com/554ax0.png" width="180" height="350" /><br><p align="justify">Tampilan Sign Up ini adalah tampilan register bagi member yang belum mempunyai akun.</p></td>
				<td><img src="http://i63.tinypic.com/2u6k4js.png" width="180" height="350" /><br><p align="justify">Pada tampilan Dashboard member ini terdapat tampilan utama yang berisi foto-foto dan promo toko.</p></td>
				<td><img src="http://i65.tinypic.com/20itelf.png" width="180" height="350" /><br><p align="justify">Pada tampilan Navbar ini tersedia menu-menu untuk member seperti scan, daftar belanja, topup, struk, setting dan lainnya.</p></td>		
		</tr>
		<tr align="center">
			<td><b>Scan</td>
			<td><b>Hasil Scan</td>
			<td><b>Daftar belanja</td>
		</tr>
		<tr valign="top" align="center">
				<td><img src="http://i68.tinypic.com/eb6649.png" width="180" height="350" /><br><p align="justify">Pada tampilan scan ini member akan melakukan scan pada QR Code yang ditempel pada rak produk menggunakan menu scan dari aplikasi Q-pay</p></td>
				<td><img src="http://i63.tinypic.com/m75qom.png" width="180" height="350" /><br><p align="justify">Pada tampilan hasil scan akan muncul tampilan berupa pop up dimana akan ditampilkan nama produk dan juga harga produk, kemudian member diminta untuk memasukkan jumlah produk jika ingin melanjutkan pembelian.</p></td>
				<td><img src="http://i67.tinypic.com/2aeyud1.png" width="180" height="350" /><br><p align="justify">Pada menu daftar belanja ini akan tampil list produk yang sudah di scan beserta keterangan harga masing-masing produk dan total harga yang harus dibayar.</p></td>		
		</tr>
		<tr align="center">
			<td><b>Struk</td>
			<td><b>Detail Struk</td>
			<td><b>Dashboard Karyawan</td>
		</tr>
		<tr valign="top" align="center">
				<td><img src="http://i68.tinypic.com/2hx7tr9.png" width="180" height="350" /><br><p align="justify">Pada menu struk ini akan ditampilkan list dari struk transaksi yang pernah dilakukan member di toko tersebut beserta dengan tanggal transaksinya.</p></td>
				<td><img src="http://i64.tinypic.com/334p8ie.png" width="180" height="350" /><br><p align="justify">Padaq tampilan detail struk ini akan ditampilkan rincian dari produk, harga, beserta total harga dari transaksi yang pernah dilakukan member.</p></td>
				<td><img src="http://i67.tinypic.com/34j3fyc.png" width="180" height="350" /><br><p align="justify">Dashboard karyawan ini merupakan menu utama dari user karyawan dimana akan ditampilkan nama karyawan yang telah login.</p></td>		
		</tr>
		<tr align="center">
            <td> <b>Navbar Karyawan</td>
			<td> <b>Data Barang</td>
		</tr>
		<tr valign="top" align="center">
            <td><img src="http://i64.tinypic.com/xlbk06.png" width="180" height="350" /><br><p align="justify">Pada tampilan navbar karyawan ini terdapat menu-menu yang bisa digunakan oleh user karyawan diantaranya menu data barang dan menu transaksi.</p></td>
			<td><img src="http://i68.tinypic.com/wcl84j.png" width="180" height="350" /><br><p align="justify">Pada menu data barang ini karyawan dapat mengelola data barang seperti menambahkan barang, mengubah data barang, menghapus data barang dan melihat data barang.</p></td>
		</tr>
	</table>
    </div>

____2.1.3 Antarmuka perangkat keras____
<br>Kebutuhan minimum perangkat keras yang dapat digunakan oleh aplikasi ini adalah :
<br>- Smarthpone Android
<br>- PC/Laptop

![use case 1](http://i63.tinypic.com/2na8rxe.jpg)

____2.1.4 Antarmuka perangkat lunak____
<br>Perangkat lunak yang dibutuhkan untuk aplikasi ini yaitu :
<ul>
<li>Android Studio</li>
<li>Sublime Teks</li>
<li>XAMPP</li>
<li>Balsamiq Mockup3</li>
</ul>

____2.1.5 Antarmuka komunikasi____
<br>Yang dibutuhkan hanya sebuah android yang dapat terhubung ke internet.

____2.1.6 Batasan-batasan memori____
<br>Perangkat lunak hanya dapat dijalankan di android.

____2.1.7 Operasi-operasi____

____2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi____

__2.2 Fungsi-fungsi produk__

![use case 2](http://i65.tinypic.com/2m29wsw.jpg)

![use case 3](http://i65.tinypic.com/23w49wg.jpg)

__2.3 Karakteristik pengguna__

__2.4 Batasan-batasan__

__2.5 Asumsi-asumsi dan ketergantungan/keterkaitan__


## BAB III KEBUTUHAN LAIN YANG SPESIFIK
Kebutuhan fungsional adalah kebutuhan yang harus dipenuhi agar suatu sistem dapat berjalan atau dapat dikatakan kebutuhan tambahan yang memiliki input, proses dan output. Kebutuhan fungsional yang harus ada dalam sistem yang akan dikembangkan ini yaitu sistem harus dapat mempermudah pengguna dalam menggunkan aplikasi ini.


## BAB IV INFORMASI PENDUKUNG
![](http://i64.tinypic.com/jz8qh2.jpg)
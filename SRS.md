<b>
	<h1>
		<i>Software Rewuired Specification (SRS)</i>
	</h1>
</b>
<ol>
<li>Pendahuluan</li>
<ol>
1.1	Tujuan<br>
<i>Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun ”Aplikasi Laundry Client Berbasis Mobile”. Dokumen ini dibangun untuk memudahkan dalam melakukan proses pembagian kelompok secara acak dan merata yang dilakukan oleh pengguna. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak ”Aplikasi Laundry Client Berbasis Mobile”.</i><br>
</ol>
<ol>
1.2	Lingkup Masalah<br>
<i>Aplikasi Laundry Client Berbasis Mobile yang kami buat untuk mempermudah pelanggan untuk melakukan sebuah transaksi, agar pelanggan tidak usah datang ketempat laundry jadi hanya di jemput oleh jasa kurir yang disediakan oleh laundry tersebut</i><br>
</ol>
<ol>
1.3	Definisi, akronim, singkatan<<br>
<i>Akronim dan Singkatan :</i><br>
<i><i>•	SRS : Software Requirement Specification<i></i><br>
<i>Definisi :</i><br>
<i>•	Software Requirement Specification adalah perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasih pembuat dengan pengguna.</i><br>
<i>•	use case adalah situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda.</i><br>
</ol>
<ol>
1.4	Referensi<br>
<i>Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah:</i><br>
<i>•	Praktikum Analisis dan Desain Sistem Informasi, 2009</i><br>
<i>•	Sistem Informasi Sekolah Terpadu, 2009</i><br>
</ol>
<ol>
1.5	Overview<br>
<i>Dokumen SRS ini dibagi menjadi tiga bagian utama, yaitu :</i>
<i>bagian pertama berisi penjelasan tentang dokumen SRS yang mencakup tujuan pembuatan dokumen ini, lingkup masalah yang diselesaikan oleh perangkat lunak yang dikembangkan, definisi, referensi dan deskripsi umum. Bagian kedua berisi penjelasan secara umum mengenai Aplikasi Random Grup yang akan dibangun, meliputi fungsi dari perangkat lunak, karakteristik pengguna, batasan dan asumsi yang diambil dala pembuatan perangkat lunak. Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih rinci.</i>
</ol>
</ol>
<ol>
2. Gambaran Umum <br>
</ol>
<ol>
<i> 2.1 Perspektif produk </i><br>
<i>Pendefinisian Aplikasi Laundry ini yaitu untuk membantu user dalam menggunakan jasa laundry.Pembuatan Aplikasi Laundry bertujuan untuk membantu pengguna jika ingin menggunakan jasa laundry</i><br>
<i> 2.1.1 Antarmuka sistem <br>
<i> Dalam penggunaan, pengguna berinteraksi langsung dengan aplikasi melalui hp/mobile </i><br>
<i> 2.1.2 Antarmuka pengguna</i><br>
<i> Perangkat lunak untuk aplikasi ini dibuat dengan menggunakan aplikasi android studio.Dimana tampilan didesain dengan menggunakan templete yang ada. Perangkat lunak untuk layanan dalam aplikasi ini dilengkapi dengan menu untuk pengaksesan berbagai fungsi yang disediakan. </i><br>
<i> 2.1.3 Antarmuka perangkat keras</i><br>
<i> perangkat keras yang dapat digunakan dalam perangkat lunak yang dibuat: </i><br>
<i> Handphone/Mobile </i><br>
<i> Semua perangkat keras yang digunakan merupakan perangkat standar dalam mobile</i><br>
<i> 2.1.4 Antarmuka perangkat lunak </i><br>
<i> Perangkat lunak yang dibutuhkan untuk laundry </i><br>
<i><li> Sistem Operasi Windows (7,8,10)dll<i></li><br>
<i><li> Untuk pengolahan database : SQL Server 2008 </li></i><br>
<i><li> Untuk koneksi Database digunakan ADOdB </li> </i><br>
<i> 2.1.5 Antarmuka komunikasi </i><br>
<i> Proses komunikasi dalam sistem ini menggunakan jaringan loka, dimana dikontrol oleh komputer server <i><br>
<i> 2.1.6 Batasan-batasan memori </i><br>
<i> Perangkat lunak hanya dijalankan di windows (7,8,10 dll). Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan. Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada pada saat ini tanpa adanya user. <i><br>
<i> 2.1.7 Operasi-operasi </i><br>
<i> Perangkat lunak dapat dijalankan di PC ataupun Mobile </i><br>
<i> </i>
<i> 2.1.8 Fungsi-fungsi produk </i><br>
<i> Fungsi dari Aplikasi Laundry berdasarkan pengguna sisten ini adalah sebagai berikut : </i><br>
<i><li> Membantu user dalam menggunakan jasa laundry secara mudah dan jelas </li></i><br>
<i><li> Program ini bisa menampung user yang ingin menggunakan jasa laundry </li></i>
</ol>
<ol>
<i>2.2 Fungsi – fungsi produk</i><br>
<i>Fungsi dari Aplikasi Laundry berdasarkan pengguna sistem ini adalah sebagai berikut :</i><br>
<i>a.	Membantu pelanggan dalam memesan laundry dengan mudah dan cepat.</i><br>
<i> 2.3 Karakteristik pengguna </i>
<i> Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses dan level autentifikasi. </i><br>
<i> Batasan-batasan </i><br>
<i> 1. Perangkat lunak hanya dijalankan di PC & Mobile </i><br>
<i> 2. Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fugsi yang ada dapat dilaksanakan </i><br>
<i> 3. Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada. </i><br>
</ol>
<ol>
<i>2.4 Batasan – batasan</i><br>
<i>1.	Perangkat lunak hanya dijalankan di Windows (7, 8, 10 ).</i><br>
<i>2.	Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.</i><br>
<i>3.	Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada.</i><br>
</ol>
<ol>
<i> 2.5 Asumsi-asumsi dan ketergantungan / keterkaitan </i><br>
<i> Maksimal penginputan data atau memasukan nama user pada aplikasi adalah semaksimal mungkin. </i><br>
<i> Kebutuhah-kebutuhan penyeimbang </i><br>
</ol>
<ol>
3. Kebutuhan lain yang spesifik<br>
		<i>Kebutuhan fungsional adalah kebutuhan yang harus dipenuhi agar suatu sistem dapat berjalan atau dapat dikatakan 
	kebutuhan tambahan yang memiliki input, proses, dan output. Kebutuhan fungsional yang harus ada dalam sistem yang akan 
	dikembangkan ini adalah sebagai berikut : </i>
	<i>1. Sistem harus dapat mempermudah pengguna / user dalam menggunakan aplikasi ini.</i><br>
</ol>
<ol>
4. Informasi pendukung <br> 
	<i>Kebanyakan informasi pendukung yang kami dapat dari artikel, makalah, dan tugas akhir yang diperoleh dari internet</i><br>
</ol>
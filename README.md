Proyek Akhir Pemrograman Internet

Berikut ini adalah daftar proyek yang harus dibuat oleh mahasiswa yang mengambil mata kuliah Pemrograman Internet, namun tidak menutup kemungkinan juga pembaca yang lain dapat mencoba membuatnya.
Proyek yang saya sediakan berikut ini tidak terlalu spesifik namun cukup dapat mencakup materi yang diajarkan di mata kuliah ini.  Mahasiswa dapat membuat sendiri desain user interface sesuai kreativitas masing-masing. Boleh memakai template dari Internet atau CSS Framework seperti Foundation, Bootstrap, Responsee, dll. Jika menggunakan template hasil download dari Internet, WAJIB menuliskan URL sumber template di bagian footer-nya.
Spesifikasi yang tercantum adalah spesifikasi minimal dan mahasiswa harus menambahkan beberapa fitur pendukung meskipun tidak tercantum pada spesifikasi, sampai pada taraf kepantasan sebuah aplikasi yang layak publish di Internet.
Setelah jadi, aplikasi di-upload pada hosting masing-masing (gratis maupun berbayar) dan source code-nya di-update secara teratur pada github.com. Pastikan pada saat penilaian, source code dan aplikasi yang diunggah adalah versi final terakhir.
Tugas ini adalah tugas mandiri. Jika ada lebih dari satu proyek yang hasilnya sama persis, maka yang dapat nilai adalah pengumpul pertama, sisanya langsung E (failed).

Proyek 1 : Online vote Pemira
Aplikasi ini digunakan untuk melakukan pemilihan umum raya presiden dan wakil presiden BEM.  Aplikasi ini juga menggantikan surat suara konvensional berupa kertas menjadi Online vote. Aplikasi ini juga dapat memperlihatkan siapa calon yang dapat dipilih beserta nomor urut dan visi-misinya. 

Deskripsi :
Aplikasi ini memiliki 2 pengguna, yaitu :

1.	Panitia Pemira : mendaftarkan siapa calon presiden dan wakil presiden BEM disertai dengan foto, visi misi dan data calon secara detail dan lengkap.
2.	Calon pemilih : Mendaftarkan diri. Pemilih yang sudah mendaftar, mendapatkan hak pilih untuk memilih salah satu calon.

Workflow :

1.	Panitia melakukan input data pasangan calon, visi misi, foto.
2.	Voter melakukan pendaftaran untuk mendapatkan hak pilih.
3.	Voter dapat melakukan vote untuk salah satu pasangan calon.

Spesifikasi :

1. Panitia harus login untuk melakukan input data calon presiden dan wakil presiden.
2. Voter melakukan registrasi untuk mendapatkan hak pilih.
3. Pengguna yang tidak punya akun tidak bisa login.
4. Biodata calon diinput adalah NIM, nama, fakultas, jurusan, IPK, visi misi, foto calon
5. Biodata voter yang diinput adalah NIM, nama, fakultas, jurusan
6. Voter yang sudah pernah melakukan vote tidak dapat vote untuk yang kedua kalinya.
7. Semua data diinput ke database melalui user interface.
8. Aplikasi dapat menampilkan jumlah vote masing-masing pasangan calon

Proyek 2 : Pendaftaran UKM

Deskripsi
Aplikasi ini digunakan untuk membantu Unit Kegiatan Mahasiswa(UKM) dalam melakukan promosi dan pendaftaran UKM di sebuah Universitas. Pendaftaran secara Online akan mempermudah UKM dalam melakukan rekap pendaftaran sehingga mengurangi kesalahan data atau data yang tercecer.

Pengguna aplikasi ini ada 2, yaitu :

1.	UKM
2.	Mahasiswa

Workflow 

1. UKM menentukan berapa jumlah mahasiswa yang diperbolehkan mendaftar di UKM yang bersangkutan.
2. UKM berhak memverifikasi/menerima mahasiswa yang diterima masuk ke dalam UKM tersebut.
3. Mahasiswa yang ingin mendaftar diperbolehkan mendaftar tanpa login.
4. Satu mahasiswa diperbolehkan mendaftar maksimal 2 UKM.
5. Mahasiswa dapat melihat hasil daftar yang diterima/tidak.

Spesifikasi 

1. Untuk dapat menentukan kriteria mahasiswa yang diterima, UKM login terlebih dahulu. Boleh juga menentukan kuota berapa mahasiswa yang diterima.
2. Mahasiswa yang ingin mendaftar dapat melihat ketentuan menjadi anggota UKM.
3. Calon anggota UKM diwajibkan mengisi formulir pendaftaran yang disediakan dan maksimal mendaftar untuk 2 UKM.
4. Daftar UKM yang dipilih di-load melalui database.
5. Daftar mahasiswa yang diterima akan ditampilkan di halaman utama aplikasi ini.
 
Proyek 3 : Aplikasi pendaftaran mahasiswa baru secara Online. 

Deskripsi :

Aplikasi ini digunakan untuk membantu dalam pendataan calon mahasiswa baru di sebuah Universitas. Pendaftaran dibatasi untuk satu jalur saja yaitu jalur prestasi. Melalui aplikasi ini, juga dapat ditampilkan daftar mahasiswa yang diterima melalui jalur prestasi.


Workflow :

1. Calon mahasiswa melakukan pendaftaran melalui aplikasi.
2. Output dari pendaftaran ini adalah data diri mahasiswa dan nomor pendaftaran serta password yang akan digunakan untuk login.
3. Login ke aplikasi tujuannya adalah untuk melakukan edit data, upload bukti pembayaran, dan melengkapi data lainnya termasuk prestasi, sertifikat/piagam dan pas foto.
4. Administrator bertugas untuk melakukan penghitungan bobot prestasi yang nantinya akan digunakan sebagai acuan untuk menentukan apakah calon mahasiswa tersebut diterima atau ditolak.
5. Administrator juga bertugas untuk memverifikasi bukti pembayaran yang telah dilakukan oleh calon mahasiswa.

Spesifikasi :

1. Calon mahasiswa dapat melakukan pendaftaran dengan mengisi formulir pendaftaran yang disediakan oleh aplikasi.
2. Jurusan yang dapat dipilih oleh mahasiswa maksimal dua jurusan. Jurusan di-load melalui database.
3. Setelah selesai mendaftar, hasil pendaftaran ditampilkan lengkap dengan nomor pendaftarannya. 
4. Nomor pendaftaran digunakan sebagai username untuk login, sedangkan password ditulis sendiri bersamaan dengan mengisi formulir pendaftaran.
5. Mahasiswa dapat melakukan pembaruan data, upload bukti pembayaran, upload sertifikat/piagam dan pas foto. Proses-proses tersebut didahului dengan login.
6. Administrator dapat melihat siapa saja yang telah mendaftar, melakukan penghitungan bobot prestasi, verifikasi pembayaran calon mahasiswa. Proses-proses tersebut didahului dengan login.
7. Mahasiswa yang telah membayar dan diverifikasi pembayarannya, berhak mengikuti seleksi administratif yaitu penghitungan bobot prestasi. Jika tidak membayar biaya pendaftaran, maka tidak diikutkan pada seleksi administratif.


Proyek 4 : Aplikasi review untuk kegiatan call for Paper
Aplikasi ini merupakan aplikasi yang akan membantu panitia kegiatan call for Paper untuk melakukan seleksi terhadap Paper yang sudah masuk.
Pengguna aplikasi ini ada 2 :

1.	Peserta call for Paper
2.	Panitia


Workflow :

1.	Calon peserta call for Paper melakukan pendaftaran sesuai dengan bidang kajiannya.
2.	Calon peserta meng-upload Paper melalui aplikasi. 
3.	Panitia login untuk memeriksa siapa saja yang sudah mendaftar pada kegiatan tersebut.
4.	Panitia dapat melakukan review terhadap Paper yang sudah masuk untuk ditentukan Paper mana yang layak atau tidak layak.
5.	Panita mengumumkan hasil Paper yang diterima dan ditolak ke halaman utama aplikasi.

Spesifikasi :

1.	Calon peserta mendaftar dengan mengisi formulir pendaftaran sesuai dengan bidang kajiannya.
2.	Calon peserta hanya dapat mendaftar satu kali dengan email yang sama.
3.	Calon peserta dapat meng-upload papernya ke dalam aplikasi.
4.	Panitia me-review Paper dengan membaca file yang diupload oleh calon peserta, kemudian mengisi formulir review Paper untuk kemudian ditentukan apakah Paper tersebut diterima atau ditolak. Kegiatan review ini didahului dengan login panitia.
5.	Setiap Paper yang sudah masuk, akan diumumkan apakah diterima atau ditolak.


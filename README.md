# Nensi-Fitriyanti_09011182328113_SK3B
<div align="center">

## LAPORAN PRAKTIKUM SISTEM OPERASI 
## INSTALASI LINUX (UBUNTU)

Dosen Pengampu:\
Ahmad Heryanto, M. T.\
Adi Hermansyah, M. T.\
Sutarno, M.T.\
Iman Saladin B. Azhar, S. Kom., M. M.SI.\
Dr. Ahmad Zarkarsi, M. T.

<img width="400" alt="LOGO UNSRI" src="https://github.com/user-attachments/assets/dfdba8bf-0b08-4c7c-9cf1-2967730ddc9d">

Disusun Oleh:\
Nama: Nensi Fitriyanti\
NIM: 09011182328113\
Hari/Tanggal: Jumat, 30 Agustus 2024

JURUSAN SISTEM KOMPUTER  
FAKULTAS ILMU KOMPUTER  
UNIVERSITAS SRIWIJAYA  
2024
<br>
<br>

## DAFTAR ISI

</div>

>
[PENDAHULUAN](#pendahuluan)
  > [Latar Belakang](#latar-belakang)\
  > [Tujuan](#tujuan)\
  > [Teori](#teori)

>
[Alat dan Bahan](#alat-dan-bahan)
  > [Alat](#alat)\
  > [Bahan](#bahan)

>
[PEMBAHASAN](#pembahasan)
  > [Langkah Instalasi Linux](#langkah-instalasi-linux)\
  > [Langkah On Of Linux](#langkah-on-of-linux)

>
[PENUTUP](#penutup)
  > [Kesimpulan](#Kesimpulan)

>
[DAFTAR PUSTAKA](#daftar-pustaka)

<div align="center">
<br>
<br>

## PENDAHULUAN

</div>

### Latar Belakang

<div align="justify">

Linux Ubuntu adalah distribusi sistem operasi berbasis Linux yang dikembangkan oleh Canonical Ltd., diluncurkan pada 2004 dengan tujuan memudahkan penggunaan Linux. Ubuntu dikenal karena sifatnya yang gratis, open source, serta antarmuka yang ramah pengguna dan dukungan keamanan yang kuat. Instalasi Ubuntu melibatkan langkah-langkah seperti mempersiapkan perangkat keras, mencadangkan data, dan menggunakan media instalasi seperti USB bootable. Proses instalasi mencakup boot dari media, pengaturan bahasa, partisi disk, dan konfigurasi sistem, yang setelahnya diakhiri dengan restart dan penyelesaian pengaturan tambahan.

### Tujuan
-	Memahami bagaimana cara instalasi sistem operasi Ubuntu menggunakan VirtualBox.
-	Mempraktikkan langkah-langkah konfigurasi sistem operasi Ubuntu.
-	Menyediakan sistem operasi Linux yang mudah digunakan.
- Mendukung filosofi perangkat lunak.

### Teori
Sistem operasi adalah perangkat lunak utama yang mengatur penggunaan sumber daya perangkat keras komputer dan menyediakan layanan untuk perangkat lunak aplikasi. Fungsinya meliputi manajemen sumber daya seperti CPU, memori, penyimpanan, serta perangkat input/output. Sistem operasi juga menyediakan antarmuka pengguna, baik dalam bentuk teks atau grafis, untuk memudahkan interaksi antara pengguna dan komputer. Selain itu, sistem operasi mengatur pelaksanaan program dengan mengelola proses dan thread, serta memastikan efisiensi melalui penjadwalan CPU dan pengelolaan status proses. Dalam hal memori, sistem operasi mengontrol distribusi dan penggunaan memori utama menggunakan teknik seperti paging dan segmentasi. Pengelolaan file dan sistem penyimpanan juga sangat penting, di mana sistem operasi menangani struktur, penyimpanan, dan akses data pada perangkat penyimpanan. Terakhir, sistem operasi menerapkan kebijakan keamanan untuk melindungi data dan sumber daya dari akses yang tidak sah, sehingga proses dan pengguna tidak saling mengganggu atau merusak sistem. Contoh penerapan sistem operasi ini dapat dilakukan dengan menggunakan Linux Ubuntu versi 22.04.4 LTS dalam lingkungan virtual menggunakan VirtualBox. Dengan cara ini, kita  dapat mengeksplorasi dan mengelola berbagai fungsi sistem operasi dalam lingkungan yang terisolasi tanpa mempengaruhi sistem utama.

</div>

<div align="center">
<br>
<br>

## Alat dan Bahan

</div>

<div align="justify">

### Alat
- Komputer/Labtop: Pastikan computer anda memiliki cukup RAM dan ruang penyimpanan untuk menjalankan VirtualBox dan sistem operasi virtual.
- VirtualBox: Aplikasi virtualisasi yang digunakan untuk menjalankan mesin virtual, yang dapat diunduh pada situs resmi VirtualBox


### Bahan
- File ISO Ubuntu: Gambar disk dari Ubuntu yang dapat diunduh dari situs resmi Ubuntu.
- Ruang Penyimpanan Virtual: Ruang yang disediakan untuk mesin virtual (dapat dikonfigurasi dalam VirtualBox).


</div>

<div align="center">
<br>
<br>

## PEMBAHASAN

</div>

<div align="justify">

## Langkah Instalasi Linux
</div>

<div align="justify">

1. Siapkan VirtualBox untuk menginstal linux, jika belum ada silahkan download terlebih dahulu.

<img width="400" alt="VirtualBox-Logo" src="https://github.com/user-attachments/assets/cd8c4862-6d77-42a9-94d8-273d476f2ea4">

2. Download ubuntu dengan versi sesuai dengan kapasitas laptop, disini kita akan menggunakan linux ubuntu versi 22.04.4 LTS

<img width="400" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/0a6382f7-4411-4080-b14f-86afde248819">

3. Setelah selesai download ubuntu versi 22.04.4 LTS, buka VirtualBox tampilan awal seperti gambar di bawah ini

<img width="400" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/f38dbd3b-6cd1-4269-bb1b-0676de67c51a">

4. Lalu pilih icon New pada bagian atas, pada kolom yang muncul beri nama Linux-Ubuntu

<img width="400" alt=" Screenshot (197)" src="https://github.com/user-attachments/assets/d7e3271d-9501-4278-b1cf-be469269c82d">

5. Lalu ganti ISO Image > Other > Ubuntu-22.04.4 > Open  > Next

<img width="400" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/1ffdc193-3398-4939-9c3f-23f505df0bc5">

<img width="400" alt="Screenshot (199)" src="https://github.com/user-attachments/assets/4bbeecaf-c618-426b-8a21-c9ff22b7bc46">

<img width="400" alt="Screenshot (200)" src="https://github.com/user-attachments/assets/9cc027f8-9550-4c81-94d0-0399c711267e">

6. Setelah itu, atur base memory dan processors, atur size serta tidak melebihi dari garis hijau > Next

<img width="400" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/636c5697-9c34-4e44-a0fa-9445e30cf856">

7. Lalu atur Virtual Hard disk atur minimal 50GB agar pada saat instal tidak ada masalah > Next > finish

<img width="400" alt="Screenshot (203)" src="https://github.com/user-attachments/assets/67b4e860-4a13-4d09-824c-c4951f4c16e8">

8. Setelah itu, kita atur ubuntunya dengan masuk ke-settings > Display > atur size Video Memory sampai full > OK

<img width="400" alt="Screenshot (204)" src="https://github.com/user-attachments/assets/0c3ee8bd-b989-4355-ae87-ba0e422af76d">

9. Selanjutnya klik start dan otomatis akan mendownload tunggu sampai selesai 

<img width="400" alt="gambar nensi 11" src="https://github.com/user-attachments/assets/5f12ef98-7929-475a-8761-44a039ebe9ad">

<img width="400" alt="nensiii" src="https://github.com/user-attachments/assets/0de22a75-e56b-4d18-885d-722778fead26">

<img width="400" alt="nensi 25 1" src="https://github.com/user-attachments/assets/a3ef43b9-7212-4d82-ab5c-70462240139e">

10. Setelah itu akan muncul tampilan Welcome atur ke Bahasa inggris > Install Ubuntu

<img width="400" alt="ubuntu nensi 10" src="https://github.com/user-attachments/assets/e85aada0-6ff2-46b6-aa39-d568b6e41441">

11. Lalu akan masuk ke menu Keyboard layout > continu

<img width="400" alt="ubuntu" src="https://github.com/user-attachments/assets/a9d0cf39-892e-4e69-a67c-fc93ae706885">

12. Muncul menu Updates and other software dengan settingan Normal installation > Next

<img width="400" alt="nensi 12" src="https://github.com/user-attachments/assets/6391b5e0-f348-4449-bfb6-b53da4556d85">

13. Lalu kita masuk ke menu selanjutnya yaitu installation type pilih Eraser > Install Now

<img width="400" alt="nensi 13" src="https://github.com/user-attachments/assets/fe5cf432-4486-45f7-a372-f8d21865715d">

14. Selanjutnya akan muncul partisi seperti ini > continu

<img width="400" alt="nensi 14" src="https://github.com/user-attachments/assets/24d5b416-bc90-4919-8275-4934d2cb936a">

15. Kemudian time zone alokasikan di Indonesia/Jakarta > continu

<img width="400" alt="nensi 15" src="https://github.com/user-attachments/assets/ccf0d543-2872-437e-ae90-f317247d3c2c">

16. Masuk ke menu selanjutnya untuk mengatur nama, nama computer,username dan password > continu

<img width="400" alt="ware are you nensi" src="https://github.com/user-attachments/assets/bb86dfd1-1a94-4c2f-a485-0e0a02efd4ce">

17. Kita tunggu proses install-nya sampai selesai

<img width="400" alt="nensi 17" src="https://github.com/user-attachments/assets/068f5a9a-4fff-42a6-986f-8454bb4c3049">

18. Setelah install selesai klik restart now

19. Jika muncul tulisan (Please remove the installation modium, then press ENTER) maka klik enter pada keyboard

<img width="400" alt="nensi 19" src="https://github.com/user-attachments/assets/a32af065-b978-46a1-99f3-a1d1195767d4">

20. Setelah itu tunggu proses loading Ketika sudah selesai akan tampil username lalu klik > masukkan password yang sudah dibuat tadi > enter di keyboard

<img width="400" alt="user name nensi" src="https://github.com/user-attachments/assets/96ab9327-3f6c-4a40-9f7f-bc6456ff9a86">

21. Selesai, jika ada settingan lanjutan bisa di skip atau next hingga done

<img width="400" alt="nensi 21" src="https://github.com/user-attachments/assets/a86fbfbd-2742-4683-8d2d-e4041e6bf342">
-4447-a6ca-d713ddfb85ae)

22. Finish tampilannya seperti pada gambar di bawah

<img width="400" alt="nensi 22" src="https://github.com/user-attachments/assets/8682c403-53fc-4bdf-8986-cd62fd5095cb">

</div>

<div align="justify">

## Langkah On Of Linux
  
</div>

<div align="center">
<br>
<br>

1. Pada pojok kanan terdapat icon battray lalu klik dan muncul menu pilih power of/log out

![nensi 25 1](https://github.com/user-attachments/assets/5219339c-772f-4c90-a9ed-25f596c0c436)

2. Setelah itu pilih power off

![nensi 25 2](https://github.com/user-attachments/assets/b1a0642d-a975-4937-801f-3ad7186f111c)

3. Tampilannya akan kembali seperti ini, jika ingin meng-aktifkan kembali klik stard

![nensi 25 3](https://github.com/user-attachments/assets/65c04de4-742c-408a-854a-edddbd0e1bcc)

</div>

<div align="center">
<br>
<br>

## PENUTUP

</div>

<div align="justify">

## Kesimpulan

</div>

<div align="justify">

Menginstal Linux Ubuntu dengan VirtualBox memungkinkan untuk menjalankan Ubuntu di mesin virtual tanpa mengubah sistem utama. Dengan menggunakan VirtualBox dan file ISO Ubuntu, kita dapat menguji dan belajar tentang Linux dengan risiko minimal, dengan menjaga sistem utama tetap utuh. Metode ini juga menawarkan fleksibilitas dalam pengelolaan sumber daya dan isolasi lingkungan, membuatnya ideal untuk eksperimen dan pelatihan.

</div>

<div align="center">
<br>
<br>

## Daftar Pustaka

</div>

<div align="justify">

- Praktikum 1	Sistem Operasi Linux
- Muzaki Nur Rahman, Instalasi Linux Ubuntu. https://mytutorialinstalasilinux.blogspot.com/2016/12/makalah-instalasi-linux-ubuntu.html
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Hostinger, Ubuntu, 2023. https://www.hostinger.co.id/tutorial/cara-install-ubuntu
- Marcel Prastiko Arthana, 2019. https://id.scribd.com/document/453381733/MAKALAH-LINUX-UBUNTU-docx
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- Ubuntu Documentation Team. (2024). Ubuntu Server Guide. https://ubuntu.com/server/docs

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 2

## Informasi Mahasiswa
- Nama: Nensi Fitriyanti
- NIM: 09011182328113
- Kelas: SK3B

<br>

<div asign= "justify">

## Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi mount point?

![tugas 2 nensi](https://github.com/user-attachments/assets/bc477838-b251-47e2-9e21-5930d3dc2d85)


<br>

## Jawaban

Alasan memilih tanda "/" sebagai mount point saat instalasi Linux sangat penting karena:

1. Direktori Root: "/" adalah direktori dasar dari semua file dan folder dalam sistem, memastikan semua elemen sistem berada di lokasi yang tepat.
2. Struktur Hierarki: Semua direktori dan file dimulai dari "/", sehingga memilihnya menjamin struktur file sistem baru teratur dengan benar.
3. Manajemen Partisi: "/" mengatur partisi utama untuk sistem operasi dan data penting, membantu dalam pengelolaan ruang penyimpanan.
3. Standarisasi: Memilih "/" adalah praktik umum dalam distribusi Linux untuk memastikan instalasi dan pengaturan sistem yang konsisten.
4. Dengan memilih "/", artinya memastikan pengaturan sistem operasi Linux dilakukan dengan benar.

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 3

## Informasi Mahasiswa
- Nama: Nensi Fitriyanti
- NIM: 09011182328113
- Kelas: SK3B

<br>

<div align="Justify">

## Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs ! 

<br>

## Jawab:

1. ext4 (Fourth Extended File System):
   ext4 ialah sistem berkas Linux yang lebih baru dan canggih daripada ext3.
   Fitur : 
     - Mendukung partisi hingga 1 Exabyte dan file hingga 16 Terabyte.
     - Memiliki mekanisme journaling untuk melindungi data.
     - Alokasi ruang yang efisien, mempercepat pemulihan data.
     - Mendukung extents untuk mengurangi fragmentasi.

2. ext3 (Third Extended File System):
   ext3 merupakan sistem berkas Linux dengan journaling, penerus ext2.
   Fitur:
     - Mendukung partisi hingga 16 Terabyte dan file hingga 2 Terabyte.
     - Memiliki mekanisme journaling untuk meningkatkan keandalan data.
     - Kompatibel dengan ext2, memudahkan upgrade.
     - Kurang efisien dibandingkan ext4 dalam hal kinerja dan manajemen ruang.

3. swap:
   swap adalah ruang di disk digunakan sebagai tambahan RAM.
   Fitur:
     - Memfungsikan area cadangan untuk RAM, mencegah kehabisan memori.
     - Dapat membantu sistem tetap stabil ketika memori fisik penuh.
     - Ukuran swap bisa disesuaikan tergantung kebutuhan sistem.
     - Kinerja lebih lambat dibandingkan RAM, tetapi lebih baik daripada kehabisan memori.

4. NTFS (New Technology File System):
   NTFS adalah sistem berkas Windows modern dengan fitur canggih.
   Fitur:
     - Mendukung partisi/file dengan ukuran besar.
     - Fitur keamanan seperti permissions, enkripsi, dan kompresi.
     - Menyediakan mekanisme journaling untuk integritas data.
     - Mendukung pemulihan data dan sistem file yang lebih efisien.

5. FAT32 (File Allocation Table 32):
   FAT32 adalah sistem berkas yang lebih tua dan sederhana, sering digunakan pada perangkat portabel.
   Fitur:
     - Mendukung partisi hingga 2 Terabyte dan file hingga 4 Gigabyte.
     - Kompatibel dengan banyak sistem operasi termasuk Windows, macOS, dan Linux.
     - Tidak mendukung fitur-fitur canggih seperti journaling atau enkripsi.
     - Kinerja terbatas pada ukuran file dan partisi besar.

6. Btrfs (B-tree File System):
   ini adalah istem berkas Linux yang modern dengan fitur-fitur canggih.
   Fitur:
     - Mendukung snapshot dan cloning untuk pencadangan dan pemulihan data.
     - Fitur built-in untuk pengelolaan ruang dan pemeriksaan integritas.
     - Mendukung ukuran partisi dan file yang sangat besar.
     - Menyediakan kemampuan pemulihan data dan pengelolaan yang lebih fleksibel.
</dir>

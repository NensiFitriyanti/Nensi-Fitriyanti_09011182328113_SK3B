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

logo

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

## Daftar Isi

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

## Pendahuluan

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

![VirtualBox-Logo](https://github.com/user-attachments/assets/cd8c4862-6d77-42a9-94d8-273d476f2ea4)

2. Download ubuntu dengan versi sesuai dengan kapasitas laptop, disini kita akan menggunakan linux ubuntu versi 22.04.4 LTS

![Screenshot (187)](https://github.com/user-attachments/assets/0a6382f7-4411-4080-b14f-86afde248819)

3. Setelah selesai download ubuntu versi 22.04.4 LTS, buka VirtualBox tampilan awal seperti gambar di bawah ini

Screenshot (188)](https://github.com/user-attachments/assets/05c756f2-9b92-4949-b8e3-5c7e08709dc2)

4. Lalu pilih icon New pada bagian atas, pada kolom yang muncul beri nama Linux-Ubuntu

![Screenshot (197)](https://github.com/user-attachments/assets/d7e3271d-9501-4278-b1cf-be469269c82d)

5. Lalu ganti ISO Image > Other > Ubuntu-22.04.4 > Open  > Next

![Screenshot (198)](https://github.com/user-attachments/assets/1ffdc193-3398-4939-9c3f-23f505df0bc5)

![Screenshot (199)](https://github.com/user-attachments/assets/4bbeecaf-c618-426b-8a21-c9ff22b7bc46)

![Screenshot (201)](https://github.com/user-attachments/assets/56b12407-bf59-4db9-9f98-109a619dc0d8)

6. Setelah itu, atur base memory dan processors, atur size serta tidak melebihi dari garis hijau > Next

![Screenshot (202)](https://github.com/user-attachments/assets/636c5697-9c34-4e44-a0fa-9445e30cf856)

7. Lalu atur Virtual Hard disk atur minimal 50GB agar pada saat instal tidak ada masalah > Next > finish

![Screenshot (203)](https://github.com/user-attachments/assets/67b4e860-4a13-4d09-824c-c4951f4c16e8)

8. Setelah itu, kita atur ubuntunya dengan masuk ke-settings > Display > atur size Video Memory sampai full > OK

![Screenshot (204)](https://github.com/user-attachments/assets/0c3ee8bd-b989-4355-ae87-ba0e422af76d)

9. Selanjutnya klik start dan otomatis akan mendownload tunggu sampai selesai 

![nensiii](https://github.com/user-attachments/assets/0de22a75-e56b-4d18-885d-722778fead26)

10. Setelah itu akan muncul tampilan Welcome atur ke Bahasa inggris > Install Ubuntu

![ubuntu nensi 10](https://github.com/user-attachments/assets/e85aada0-6ff2-46b6-aa39-d568b6e41441)

11. Lalu akan masuk ke menu Keyboard layout > continu

![ubuntu](https://github.com/user-attachments/assets/a9d0cf39-892e-4e69-a67c-fc93ae706885)

12. Muncul menu Updates and other software dengan settingan Normal installation > Next

![nensi 12](https://github.com/user-attachments/assets/6391b5e0-f348-4449-bfb6-b53da4556d85)

13. Lalu kita masuk ke menu selanjutnya yaitu installation type pilih Eraser > Install Now

![nensi 13](https://github.com/user-attachments/assets/fe5cf432-4486-45f7-a372-f8d21865715d)

14. Selanjutnya akan muncul partisi seperti ini > continu

![nensi 14](https://github.com/user-attachments/assets/24d5b416-bc90-4919-8275-4934d2cb936a)

15. Kemudian time zone alokasikan di Indonesia/Jakarta > continu

![nensi 15](https://github.com/user-attachments/assets/ccf0d543-2872-437e-ae90-f317247d3c2c)

16. Masuk ke menu selanjutnya untuk mengatur nama, nama computer,username dan password > continu

![nensi 16](https://github.com/user-attachments/assets/514ce037-3803-42b0-8406-5690bea9d701)

17. Kita tunggu proses install-nya sampai selesai

![nensi 17](https://github.com/user-attachments/assets/068f5a9a-4fff-42a6-986f-8454bb4c3049)

18. Setelah install selesai klik restart now

19. Jika muncul tulisan (Please remove the installation modium, then press ENTER) maka klik enter pada keyboard

![nensi 19](https://github.com/user-attachments/assets/a32af065-b978-46a1-99f3-a1d1195767d4)

20. Setelah itu tunggu proses loading Ketika sudah selesai akan tampil username lalu klik > masukkan password yang sudah dibuat tadi > enter di keyboard

![nensi 20](https://github.com/user-attachments/assets/2b2de46e-25b4

21. Selesai, jika ada settingan lanjutan bisa di skip atau next hingga done

![nensi 21](https://github.com/user-attachments/assets/a86fbfbd-2742-4683-8d2d-e4041e6bf342)
-4447-a6ca-d713ddfb85ae)

22. Finish tampilannya seperti pada gambar di bawah

![nensi 22](https://github.com/user-attachments/assets/8682c403-53fc-4bdf-8986-cd62fd5095cb)

</div>

<div align="justify">

## Langkah On Of Linux
  
</div>

   ![Langkah 16](https://github.com/SyaifulKaromah/foto-repo/blob/9797ba3bfb71e27f75f3f8eadd4a7099ad99a2bf/selesai.png)


<div align="center">
<br>
<br>

## Hasil dan Pembahasan

</div>

<div align="justify">

1. Pada pojok kanan terdapat icon battray lalu klik dan muncul menu pilih power of/log out
2. Setelah itu pilih power off
3. Tampilannya akan kembali seperti ini, jika ingan meng-aktifkan kembali klik stard

</div>

<div align="justify">

### PENUTUP

</div>

<div align="center">
<br>
<br>

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
- Canonical Ltd. (2024). Ubuntu Desktop for developers. https://ubuntu.com/desktop/developers
- Oracle Corporation. (2024). Oracle VM VirtualBox User Manual. https://www.virtualbox.org/manual/
- Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). Operating System Concepts (10th ed.). Wiley.
- Tanenbaum, A. S., & Bos, H. (2014). Modern Operating Systems (4th ed.). Peason.
- Ubuntu Documentation Team. (2024). Ubuntu Server Guide. https://ubuntu.com/server/docs

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 2

## Informasi Mahasiswa
- Nama: M. Syaiful Karomah
- NIM: 09011282328111
- Kelas: SK3C

<br>

<div asign= "justify">

## Analisislah pada gambar kenapa saat instalasi perlu dipilih "/" pada opsi mount point?

![Mount Point Selection](https://github.com/SyaifulKaromah/foto-repo/blob/e433532cee5da6d4afdc9639eebc9ae06a79300b/Mount.png)

<br>

## Jawaban

Ada beberapa alasan mengapa saat instalasi perlu dipilih "/" pada opsi mount point:

1. Tanda "/" merupakan direktori root, yang mana merupakan tempat tertinggi dalam struktur sistem file. Jadi, ketika dipilih "/" sebagai mount point, maka sebenarnya kita memasang sistem operasi di direktori root.

2. Pilihan "/" membuat kita bisa mengakses semua file dan folder di System. Misalnya ketika ingin membuka file di Desktop, Jalur lengkapnya adalah "/Desktop". Jadi dengan di pilihnya "/" sebagai mount point, maka semua jalur file dapat diakses dengan mudah.

3. Karena hampir semua distribusi Linux menggunakan "/" sebagai direktori root.

</div>

----
<br>
<br>

[←    BACK](#praktikum-1---sistem-operasi)
# Soal 3

## Informasi Mahasiswa
- Nama: M. Syaiful Karomah
- NIM: 09011282328111
- Kelas: SK3C

<br>

<div align="Justify">

## Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs ! 

<br>

## Jawab:

1. ext4:
  - Penerus dari ext3 dengan peningkatan performa dan fitur
  - Mendukung volume dan file berukuran sangat besar
  - Memiliki fitur journaling untuk mencegah kerusakan data

2. ext3:
  - Versi sebelumnya dari ext4
  - Menambahkan fitur journaling ke ext2
  - Kompatibel dengan ext2 dan ext4

3. swap:
  - Bukan sistem file, melainkan ruang pada hard drive yang digunakan sebagai memori virtual
  - Membantu sistem ketika RAM fisik penuh

4. NTFS:
  - New Technology File System, dikembangkan oleh Microsoft
  - Digunakan pada sistem operasi Windows modern
  - Mendukung fitur keamanan, kompresi, dan enkripsi

5. FAT32:
  - File Allocation Table 32-bit
  - Sistem file lama namun masih kompatibel dengan banyak perangkat
  - Memiliki batasan ukuran file maksimal 4GB

6. Btrfs:
  - B-tree File System, dikembangkan untuk Linux
  - Menawarkan fitur canggih seperti snapshots, kompresi, dan RAID
  - Fokus pada toleransi kesalahan dan kemudahan pengelolaan penyimpanan

</dir>

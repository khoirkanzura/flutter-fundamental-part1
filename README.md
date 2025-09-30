# Laporan Praktikum Pemrograman Mobile

## Aplikasi Pertama dan Widget Dasar Flutter

**Nama  :** Khoir Karol Nurzuraidah  
**NIM   :** 2341760048  
**Kelas :** SIB 3C  

---

## Langkah Praktikum

### Praktikum 1: Membuat Project Flutter Baru
- **Langkah 1:**  
  Buka Visual Studio Code (VS Code), tekan **Ctrl + Shift + P** → pilih **Flutter: New Application Project** untuk membuat proyek baru.  
  <p align="center"><img src="./images/01.png" alt="Screenshot 1" width="400"/></p>  

- **Langkah 2:**  
  Pilih folder penyimpanan proyek (disarankan di *Documents* atau *Desktop*). Setelah itu, pilih **Select a folder to create the project in** untuk menentukan lokasi penyimpanan proyek.  

- **Langkah 3:**  
  Beri nama proyek `hello_world`, lalu tekan Enter.  
  <p align="center"><img src="./images/02.png" alt="Screenshot 2" width="400"/></p>  

- **Langkah 4:**  
  Akan muncul pesan **"Your Flutter Project is ready!"** yang menandakan proyek berhasil dibuat.  
  <p align="center"><img src="./images/03.png" alt="Screenshot 3" width="400"/></p>  

---

### Praktikum 2: Menghubungkan Perangkat Android atau Emulator

#### Mengaktifkan proses debug USB
- **Langkah 1:**  
  Di perangkat Android: **Settings → About phone → ketuk Build number 7x** sampai muncul pesan *You are now a developer!*.  
  <p align="center"><img src="./images/32.png" alt="Screenshot 32" width="400"/></p>  
  <p align="center"><img src="./images/33.png" alt="Screenshot 33" width="400"/></p>  

- **Langkah 2:**  
  Masuk ke **Settings → System → Developer options → aktifkan USB Debugging**.  
  <p align="center"><img src="./images/34.png" alt="Screenshot 34" width="400"/></p>  
  <p align="center"><img src="./images/35.png" alt="Screenshot 35" width="400"/></p>  
  <p align="center"><img src="./images/36.png" alt="Screenshot 36" width="400"/></p>  

#### Android Studio
- **Langkah 3:**  
  Buka **Tools > SDK Manager > SDK Tools**, centang **Google USB Driver**, lalu klik OK.  
  <p align="center"><img src="./images/37.png" alt="Screenshot 37" width="400"/></p>  
  <p align="center"><img src="./images/37.1.png" alt="Screenshot 37.1" width="400"/></p>  

#### Menjalankan aplikasi di perangkat Android
- **Langkah 4:**  
  1. Sambungkan perangkat Android ke komputer menggunakan kabel USB. Akan muncul dialog untuk mengizinkan debug USB.  
  2. Centang **Always allow from this computer**, lalu klik **OK**.  
  3. Di Android Studio, pastikan perangkat Anda dipilih di dropdown device. Klik ikon **Run**.  
  <p align="center"><img src="./images/38.png" alt="Screenshot 38" width="400"/></p>  
  <p align="center"><img src="./images/39.png" alt="Screenshot 39" width="400"/></p>  

---

### Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum
- **Langkah 1:**  
  Buat repository baru di GitHub dengan nama `flutter-fundamental-part1`.  
  <p align="center"><img src="./images/07.png" alt="Screenshot 07" width="400"/></p>  

- **Langkah 2:**  
  Klik **Create repository**.  
  <p align="center"><img src="./images/08.png" alt="Screenshot 08" width="400"/></p>  

- **Langkah 3:**  
  Buka project `hello_world` di VS Code → buka **Terminal > New Terminal**, lalu lakukan inisialisasi git.  
  <p align="center"><img src="./images/09.png" alt="Screenshot 09" width="400"/></p>  

- **Langkah 4:**  
  Buka menu **Source Control** di sisi kiri VS Code, lalu lakukan **stage (+)** pada file `.gitignore`.  
  <p align="center"><img src="./images/10.png" alt="Screenshot 10" width="400"/></p>  

- **Langkah 5:**  
  Commit dengan pesan **"tambah gitignore"**.  
  <p align="center"><img src="./images/11.png" alt="Screenshot 11" width="400"/></p>  

- **Langkah 6:**  
  Lakukan push dengan klik menu titik tiga > **Push**.  
  <p align="center"><img src="./images/12.png" alt="Screenshot 12" width="400"/></p>  

- **Langkah 7:**  
  Di pojok kanan bawah akan tampil opsi **Add Remote**. Klik tombol tersebut.  
  <p align="center"><img src="./images/13.png" alt="Screenshot 13" width="400"/></p>  

- **Langkah 8:**  
  Salin tautan repository GitHub, lalu klik **Add remote**. Beri nama remote **origin**.  
  <p align="center"><img src="./images/14.png" alt="Screenshot 14" width="400"/></p>  
  <p align="center"><img src="./images/14.0.png" alt="Screenshot 14.0" width="400"/></p>  

- **Langkah 9:**  
  Ulangi proses stage dan commit pada file `README.md`. Setelah push, masukkan username GitHub dan token. Reload repo, maka hasil push akan terlihat.  
  <p align="center"><img src="./images/15.png" alt="Screenshot 15" width="400"/></p>  
  <p align="center"><img src="./images/15.0.png" alt="Screenshot 15.0" width="400"/></p>  
  <p align="center"><img src="./images/16.png" alt="Screenshot 16" width="400"/></p>  

- **Langkah 10:**  
  Push semua file project dengan memilih **Stage All Changes**, lalu commit dengan pesan **"project hello_world"**.  
  <p align="center"><img src="./images/17.png" alt="Screenshot 17" width="400"/></p>  
  <p align="center"><img src="./images/18.png" alt="Screenshot 18" width="400"/></p>  

- **Langkah 11:**  
  Ubah platform di VS Code (pojok kanan bawah) ke emulator/device/Chrome. Jalankan project dengan **F5**.  
  <p align="center"><img src="./images/19.png" alt="Screenshot 19" width="400"/></p>  

- **Langkah 12:**  
  Ubah teks aplikasi menjadi **nama lengkap**, jalankan ulang project, lalu screenshot hasilnya (`01.png`). Tambahkan ke README.md.  
  <p align="center"><img src="./images/20.png" alt="Screenshot 20" width="400"/></p>  
  <p align="center"><img src="./images/21.png" alt="Screenshot 21" width="400"/></p>  

---

### Praktikum 4: Menerapkan Widget Dasar

#### Langkah 1: Text Widget
- Buat folder `basic_widgets` di dalam folder `lib`, lalu buat file `text_widget.dart`.  
- Lakukan import ke `main.dart`, ganti Text bawaan dengan kode tersebut.  
- Jalankan aplikasi, screenshot hasil, lalu tambahkan ke README.md.  
<p align="center"><img src="./images/22.png" alt="Screenshot 22" width="400"/></p>  
<p align="center"><img src="./images/23.png" alt="Screenshot 23" width="400"/></p>  

#### Langkah 2: Image Widget
- Buat file `image_widget.dart` di dalam folder `basic_widgets`.  
- Tambahkan file logo ke folder `assets`, lalu sesuaikan kode & import ke `main.dart`.  
- Jalankan aplikasi, screenshot hasil, tambahkan ke README.md.  
<p align="center"><img src="./images/24.png" alt="Screenshot 24" width="400"/></p>  

---

### Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino

#### Langkah 1: Cupertino Button dan Loading Bar
- Buat file `loading_cupertino.dart` di folder `basic_widgets`.  
- Import `material.dart` dan `cupertino.dart`.  
- Tambahkan kode untuk `CupertinoButton` & `CupertinoActivityIndicator`.  
<p align="center"><img src="./images/25.png" alt="Screenshot 25" width="400"/></p>  
<p align="center"><img src="./images/25.1.png" alt="Screenshot 25.1" width="400"/></p>  

#### Langkah 2: Floating Action Button (FAB)
- Buat file `fab_widget.dart` di folder `basic_widgets`.  
- Tambahkan kode FAB dengan `StatelessWidget`.  
<p align="center"><img src="./images/26.png" alt="Screenshot 26" width="400"/></p>  
<p align="center"><img src="./images/26.1.png" alt="Screenshot 26.1" width="400"/></p>  

#### Langkah 3: Scaffold Widget
- Gunakan widget `Scaffold` untuk tata letak Material Design.  
<p align="center"><img src="./images/27.png" alt="Screenshot 27" width="400"/></p>  
<p align="center"><img src="./images/27.1.png" alt="Screenshot 27.1" width="400"/></p>  

#### Langkah 4: Dialog Widget
- Implementasikan `AlertDialog` dan `SimpleDialog` pada `main.dart`.  
<p align="center"><img src="./images/28.png" alt="Screenshot 28" width="400"/></p>  
<p align="center"><img src="./images/28.1.png" alt="Screenshot 28.1" width="400"/></p>  

#### Langkah 5: Input dan Selection Widget
- Gunakan widget input seperti `Checkbox`, `Radio Button`, `Slider`, `Switch`, `Date & Time Picker`, dan `TextField`.  
<p align="center"><img src="./images/29.png" alt="Screenshot 29" width="400"/></p>  
<p align="center"><img src="./images/29.1.png" alt="Screenshot 29.1" width="400"/></p>  

#### Langkah 6: Date and Time Pickers
- Tambahkan widget untuk memilih tanggal/waktu (DatePicker & TimePicker).  
<p align="center"><img src="./images/30.png" alt="Screenshot 30" width="400"/></p>  
<p align="center"><img src="./images/30.1.png" alt="Screenshot 30.1" width="400"/></p>  
<p align="center"><img src="./images/30.2.png" alt="Screenshot 30.2" width="400"/></p>  

---

<h1>Membuat Dokumen HTML dengan nama file</h1>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Mengenal JavaScript</title>
    </head>
    <body>
        <h1>Pengenalan JavaScript</h1>
        <h3>Contoh dokument.write dan console.log</h3>
        <script>
            document.write("Hello Word");
            console.log("Hello Word");
        </script>    
    </body>
    </html>

![image](https://github.com/user-attachments/assets/88e82f44-7e77-4adb-b1d9-c89aa5ed57ca)

Kode JavaScript ini menggunakan `document.write` untuk menampilkan "Hello World" langsung di halaman web, sementara `console.log` mencetak teks tersebut di konsol browser. `document.write` berguna untuk menampilkan konten di halaman, sedangkan `console.log` bermanfaat untuk debugging tanpa memengaruhi tampilan halaman.
<br> <hr>

<h2>2. Pemakaian Alert sebagai property window.</h2>

![image](https://github.com/user-attachments/assets/7d399d55-fb52-4ce5-874e-8359455c8d85)

Kode JavaScript ini memakai `window.alert` untuk menampilkan kotak pesan (alert box) yang berisi teks "ini merupakan pesan untuk anda" begitu halaman dimuat. Pengguna harus menutup kotak pesan ini agar dapat melanjutkan interaksi dengan halaman.
<br> <hr>

3. <h2>Pemakaian method dalam objek</h2>

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Skrip JavaScript</title>
        </head>
        <body>
            percobaan memakai JavaScript:<br>
            <script language = "javascript">
                document.write("Selamat mencoba Javascript<br>");
                document.write("Semoga sukses!");
            </script>
            
        </body>
        </html>

![image](https://github.com/user-attachments/assets/81769967-d2c7-441f-b880-61ce7d0754d3)
Kode JavaScript ini menampilkan teks "selamat mencoba javascript" diikuti dengan pindah baris (`<br>`), lalu menampilkan "semoga sukses!" di halaman web. `document.write` digunakan untuk langsung menuliskan teks ke halaman saat kode dijalankan.
<br> <hr>

<h2>Pemakaian Prompt</h2>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Pemasukan data</title>
    </head>
    <script language = "javascript">
        var nama = prompt("Siapa nama anda?","Masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
    <body>
        
    </body>
    </html>

![image](https://github.com/user-attachments/assets/c861ea9e-1707-413d-bef6-52a35fca0ab8)

Setelah perintah tadi lalu muncul seperti gambar diatas, lalu ketik "nama Dhean Shafwan" lalu akan muncul seperti gambar dibawah ini
<br>

![image](https://github.com/user-attachments/assets/66ade576-9796-4073-a15e-91447191f2af)

nah "Dhean Shafwan" akan muncul seperti yang diatas 
<hr> <br>

<h2>5. Pembuatan fungsi dan cara pemanggilannya</h2>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Contoh program javascript </title>
        <script language = "javascript">
            function pesan(){
                alert("Memanggil javascript lewat body onload")
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/06ab4dfe-670c-4aff-8e48-2183ccb2ac84)

Kode ini memunculkan kotak pesan (alert box) dengan teks "memanggil javascript lewat body onload" ketika halaman selesai dimuat. Atribut `onload="pesan()"` di dalam tag `<body>` secara otomatis memanggil fungsi `pesan()` saat halaman selesai dimuat, sehingga pesan ditampilkan sebagai pop-up.
<hr> <br>

<h2>6. Dasar Pemrograman Di Javascript</h2>
<h3>Operasi Dasar Aritmatika</h3>

    <html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function test (val1, val2)
            {
                document.write("<br>"+"perkalian : val1*val2"+"<br>")
                document.write(val1*val2)
                document.write("<br>"+"pembagian : val1/val2 "+"<br>")
                document.write(val1/val2)
                document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
                document.write(val1+val2)
                document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
                document.write(val1-val2)
                document.write("<br>"+"mmodulus : val1%val2 "+"<br>")
                ocument.write(val1%val2)
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/af85aa1d-8152-4b78-81a2-53c57e2503f5)
![image](https://github.com/user-attachments/assets/070f6d97-f51a-4d92-9398-5064f6db1e10)

Kode ini mendefinisikan fungsi `test(val1, val2)` yang menjalankan operasi aritmatika (perkalian, pembagian, penjumlahan, pengurangan, dan modulus) pada dua angka yang diberikan. Ketika tombol "arithmetic" diklik, fungsi dipanggil dengan nilai 9 dan 4. Hasil dari setiap operasi ditampilkan di halaman melalui `document.write`, menghasilkan output berikut:

Perkalian: 36  
Pembagian: 2.25  
Penjumlahan: 13  
Pengurangan: 5  
Modulus: 1
<hr> <br>

<h2>7. Seleksi kondisi (if..else)</h2>

    <html>
    <head>
        <title>contoh if-else</title>
        <script language="javascript">
            var nilai = prompt("nilai (0-100): ", 0);
            var hasil = " ";
            if (nilai >= 60)
            hasil = "lulus";
            else
            hasil = "tidak lulus";
            document.write("hasil: " + hasil);
        </script>
    </head>
    <body>
    </html>

![image](https://github.com/user-attachments/assets/a99a8fcf-66a6-4c24-a9a3-efdbade171c4)

setelah mengikuti perintah tersebut akan muncul gambar seperti ini, lalu saya akan mengisi dengan angka 75

![image](https://github.com/user-attachments/assets/105072e2-6bdd-4a23-8c92-6058ee1fb706)

dan hasilnya lulus.
<br> <hr>

<h2>8. Penggunaan operator switch untuk seleksi kondisi</h2>
    
    <html>
    <head>
        <title>contoh if-else</title>
        <script language="javascript">
                function test() {
                    let val = window.prompt("Input nilai (1-5):")
                    switch (val) {
                        case "1":
                            document.write("Bilangan satu")
                            break
                        case "2":
                            document.write("Bilangan dua")
                            break
                        case "3":
                            document.write("Bilangan tiga")
                            break
                        case "4":
                            document.write("Bilangan empat")
                            break
                        case "5":
                            document.write("Bilangan lima")
                            break
                        default:
                            document.write("Bilangan lainnya")
               }
        }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
    </html>
    
![image](https://github.com/user-attachments/assets/229c2106-9ca4-4daa-9b1a-e457f68f90f9)

Ketika angka 4 dimasukkan sebagai output dari perintah tersebut, hasil yang ditampilkan adalah 

![image](https://github.com/user-attachments/assets/d39dd14b-cf12-4ab6-983b-d163eb2da49e)

"bilangan 4"
<br> <hr>

<h2>9. Form Input</h2>

    <html>
    <head>
        <title>Contoh if-else</title>
        <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value; // Ganti 'ver' dengan 'var'
            if (val1 % 2 == 0)
                document.kirim.T2.value = "bilangan genap";
            else
                document.kirim.T2.value = "bilangan ganjil";
        }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20"> <!-- Ganti T2 dengan T1 -->
            MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p> <!-- Tambahkan tanda kutip -->
        </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/2afad38e-1200-434a-9a2f-99344e431f51)

Kode ini memeriksa apakah nilai yang dimasukkan pada kotak input pertama (T1) merupakan bilangan genap atau ganjil. Saat tombol "TEBAK" ditekan, hasilnya akan ditampilkan di kotak input kedua (T2) dengan keterangan "bilangan genap" atau "bilangan ganjil".
<br> <hr>

<h2>10. from button</h2>

    <html>
    <head>
        <title>objek document</title>
    </head>
    <body>
        <script language="javascript">
            function ubahWarnaLB(warna) {
                document.bgColor = warna;
            }
            function ubahWarnaLD(warna) {
                document.fgColor = warna;
            }
            </script>
            <h1>tes</h1>
            <form>
                <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
                <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
                <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
                <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
            </form>
            <script language = "javascript">
                document.write("Dimodifikasi terakhir pada " +
                document.lastModified);
            </script>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/cf8ea8b8-7f13-4ddc-8c7b-509852b86c73)
![image](https://github.com/user-attachments/assets/d1175f60-f83c-4c52-ad38-016e024ccc84)
![image](https://github.com/user-attachments/assets/6a87d819-db51-436f-a93f-e54df76e715f)
![image](https://github.com/user-attachments/assets/4008d309-7478-41bd-91a0-ce6b904798d1)
![image](https://github.com/user-attachments/assets/735ac4b2-088f-4643-8be7-5515014d689c)

Kode ini menyediakan tombol untuk mengganti warna latar belakang dan warna teks pada halaman. Fungsi `ubahWarnaLB` digunakan untuk mengubah warna latar belakang (bgColor), sedangkan fungsi `ubahWarnaLD` digunakan untuk mengubah warna teks (fgColor). Tombol yang tersedia memungkinkan pengguna untuk memilih warna latar belakang hijau atau putih serta warna teks kuning atau biru. Di bagian bawah halaman, `document.write` menampilkan informasi tentang terakhir kali halaman dimodifikasi menggunakan `document.lastModified`.
<br> <hr>

<h2>11. HTML DOM</h2>

    <!--
    File: daftar_menu.html
    -->
    <html>
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele) {
                var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
                var harga = 0;
    
                if (ele.checked) {
                    harga = ele.value;
                    total += parseInt(harga);
                } else {
                    harga = ele.value;
                    if (total > 0)
                        total -= parseInt(harga);
                }
    
                document.getElementById('total').value = total;
            }
        </script>
    </head>
    <body>
        <h1>Daftar Menu Makanan</h1>
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><hr />
        <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/ac0a3c4a-f14e-42c3-b078-ec2da3054e6b)

Kode ini menampilkan daftar menu makanan dengan checkbox untuk memilih item dan menghitung total harga. Fungsi `hitung` akan menambah atau mengurangi harga dari item yang dipilih atau dibatalkan, kemudian memperbarui nilai total di kotak input total. Setiap checkbox memiliki nilai harga sesuai dengan itemnya, dan saat dipilih, total harga akan diperbarui secara langsung di halaman.
<br> <hr>

<h1>Pertanyaan dan Tugas</h1>
<h2>1. Buat script untuk melakukan validasi pada isian form.</h2>
    
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Validasi Form</title>
        <script>
            function validateForm() {
                // Mengambil nilai dari input
                var name = document.forms["myForm"]["name"].value;
                var email = document.forms["myForm"]["email"].value;
                var phone = document.forms["myForm"]["phone"].value;

            // Validasi Nama
            if (name === "") {
                alert("Nama harus diisi.");
                return false;
            }

            // Validasi Email
            var emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/; // Regex untuk validasi email
            if (email === "") {
                alert("Email harus diisi.");
                return false;
            } else if (!emailPattern.test(email)) {
                alert("Email tidak valid.");
                return false;
            }

            // Validasi Nomor Telepon
            var phonePattern = /^[0-9]+$/; // Regex untuk validasi nomor telepon
            if (phone === "") {
                alert("Nomor telepon harus diisi.");
                return false;
            } else if (!phonePattern.test(phone)) {
                alert("Nomor telepon hanya boleh berupa angka.");
                return false;
            }

            // Jika semua validasi berhasil
            alert("Form berhasil dikirim!");
            return true; // Mengizinkan form untuk disubmit
        }
    </script>
    </head>
    <body>
        <h1>Formulir Pendaftaran Lomba Informatika 2024 </h1>
        <form name="myForm" onsubmit="return validateForm()">
            <label for="name">Nama:</label><br>
            <input type="text" name="name"><br><br>
            
        <label for="email">Email:</label><br>
        <input type="text" name="email"><br><br>
        
        <label for="phone">Nomor Telepon:</label><br>
        <input type="text" name="phone"><br><br>
        
        <input type="submit" value="Kirim">
    </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/f745e0d9-931b-4077-8952-9a33db8e720f)
![image](https://github.com/user-attachments/assets/89d5a3ed-73f1-4261-8004-62237c9877e8)

Fungsi validateForm(): Fungsi ini dijalankan saat form disubmit. Ia mengambil nilai dari input dan melakukan validasi.
Validasi Nama: Memastikan bahwa kolom nama tidak kosong.
Validasi Email: Memastikan kolom email tidak kosong dan memenuhi pola email yang benar menggunakan regular expression (regex).
Validasi Nomor Telepon: Memastikan kolom nomor telepon tidak kosong dan hanya berisi angka.
Menggunakan alert: Jika ada kesalahan dalam input, pengguna akan diberi tahu melalui pesan alert.
Mengizinkan atau Mencegah Pengiriman Form: Jika semua validasi berhasil, form akan disubmit; jika tidak, pengiriman akan dibatalkan.




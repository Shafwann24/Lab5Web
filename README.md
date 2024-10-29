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

2. <h2>2. Pemakaian Alert sebagai property window.</h2>

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



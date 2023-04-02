# Tugas-4-Pemograman-Web
# Langkah-Langkah Praktikum
Buat file baru dengan nama header.php
![Screenshot (153)](https://user-images.githubusercontent.com/115921167/229330982-2d2cc164-6a0e-4fae-8aa5-ce44fff862e0.png)
Buat file baru dengan nama footer.php
![Screenshot (154)](https://user-images.githubusercontent.com/115921167/229331014-09a16d2b-1d74-4b88-9e5c-267ea95d774d.png)
Buat file baru dengan nama home.php
![Screenshot (155)](https://user-images.githubusercontent.com/115921167/229331088-14409799-2445-4b8e-b819-a3f2fdd6fed8.png)
Buat file baru dengan nama about.php
![Screenshot (156)](https://user-images.githubusercontent.com/115921167/229331144-507c4411-9525-42df-a965-2b4c5611902f.png)
# Membuat Routing
Routing digunakan untuk mempermudah akses halaman web agar SEO Friendly.
Langkah awal adalah menyiapkan file utama (index.php) yang berisi routing untuk mengakses banyak 
halaman. 

• Halaman Home ( http://localhost/Lab4Web/index.php?mod=home )
• Halaman About ( http://localhost/Lab4Web/index.php?mod=about )
Buat file baru dengan nama index.php
![Screenshot (157)](https://user-images.githubusercontent.com/115921167/229331259-e93938bd-87ab-411f-b336-7480e0c8fd05.png)
# Aktivasi mod_rewrite (.htaccess)
Mod_rewrite digunakan untuk mengubah URL dari query string menjadi SEO Friendly. 
Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada 
configurasi httpd.conf.
![Screenshot (158)](https://user-images.githubusercontent.com/115921167/229331311-4bf13702-fb1b-4952-b5e9-00013f9f1e8d.png)
Aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut, 
kemudian restart Apache2.
Langkah berikutnya adalah membuat file .htaccess
![Screenshot (159)](https://user-images.githubusercontent.com/115921167/229331334-65555da2-8b17-443e-9566-8a0524b9ac45.png)
Cara aksesnya menjadi:
• Halaman Home ( http://localhost/Lab4Web/home.php )
• Halaman About ( http://localhost/Lab4Web/about.php )

# lab11web_c1
Nama	:	RIZAL GUNAWAN
KELAS	:	ti19b1
Nim	:	311910798
Buka aplikasi xampp lalu untuk mengaktifkan ekstentsi tersebut, klik pada bagian Apache Config -> PHP.ini.
![image](https://user-images.githubusercontent.com/85833641/124523558-6c898f80-ddac-11eb-8585-e07e23db8074.png)
![image](https://user-images.githubusercontent.com/85833641/124523552-672c4500-ddac-11eb-832d-c5e35ae3806c.png)
Setelah itu Arahkan lokasi direktori pada (xampp/htdocs/lab11_ci/ci4/) kemudian tulis "php spark" untuk memanggil CLI Codeignite
![image](https://user-images.githubusercontent.com/85833641/124523568-78755180-ddac-11eb-99c1-cbaaabf11d63.png)
Kmudian untuk Mengaktifkan Mode Debugging untuk mengetahui pesan error apabila terjadi kesalahan dalam membuat kode program Secara default fitur ini belum aktif.
![image](https://user-images.githubusercontent.com/85833641/124523581-83c87d00-ddac-11eb-8216-4d8392ae8213.png)
![image](https://user-images.githubusercontent.com/85833641/124523587-888d3100-ddac-11eb-912c-6ddef0e8bb79.png)
Tambahkan kode
•	$routes->get('/about', 'Page::about');
•	$routes->get('/contact', 'Page::contact');
•	$routes->get('/faqs', 'Page::faqs'); di dalam Routes.php, lalu jalankan "php spark routes" 
![image](https://user-images.githubusercontent.com/85833641/124523596-93e05c80-ddac-11eb-838d-7329ad8fa63d.png)
![image](https://user-images.githubusercontent.com/85833641/124523602-98a51080-ddac-11eb-942f-152b02f85892.png)
![image](https://user-images.githubusercontent.com/85833641/124523604-9cd12e00-ddac-11eb-850f-968c155533b5.png)
![image](https://user-images.githubusercontent.com/85833641/124523607-a195e200-ddac-11eb-8a9f-50a7edcf4802.png)
![image](https://user-images.githubusercontent.com/85833641/124523610-a78bc300-ddac-11eb-82a2-0736fcf8a31a.png)
![image](https://user-images.githubusercontent.com/85833641/124523613-ac507700-ddac-11eb-9b35-d92775570812.png)
![image](https://user-images.githubusercontent.com/85833641/124523616-afe3fe00-ddac-11eb-86c4-366cad2e9170.png)
Langkah-langkah praktikum
jalankan terlebih dahulu MySQL Server melalui XAMPP
Buatlah database sebagai berikut untuk menampilkan tabel
![image](https://user-images.githubusercontent.com/85833641/124523632-c2f6ce00-ddac-11eb-8a01-06571610cd9b.png)
![image](https://user-images.githubusercontent.com/85833641/124523640-c7bb8200-ddac-11eb-9cc8-f1d22d125bdf.png)
![image](https://user-images.githubusercontent.com/85833641/124523646-cee29000-ddac-11eb-8dc8-5d424f175c6e.png)
![image](https://user-images.githubusercontent.com/85833641/124523642-cb4f0900-ddac-11eb-823d-a0d9d61cb91c.png)
![image](https://user-images.githubusercontent.com/85833641/124523654-d30ead80-ddac-11eb-8097-e79f2a65ea0a.png)
![image](https://user-images.githubusercontent.com/85833641/124523663-d6a23480-ddac-11eb-8d0e-490edc5b4ac5.png)
![image](https://user-images.githubusercontent.com/85833641/124523667-dace5200-ddac-11eb-852f-db7a82ca70c9.png)
![image](https://user-images.githubusercontent.com/85833641/124523672-defa6f80-ddac-11eb-8bbf-d898236090cc.png)
![image](https://user-images.githubusercontent.com/85833641/124523677-e457ba00-ddac-11eb-8a04-b40997afe58b.png)
![image](https://user-images.githubusercontent.com/85833641/124523686-ee79b880-ddac-11eb-9e0a-8ac4ea3c6154.png)
![image](https://user-images.githubusercontent.com/85833641/124523690-f20d3f80-ddac-11eb-841e-f7c422389f72.png)
![image](https://user-images.githubusercontent.com/85833641/124523693-f9344d80-ddac-11eb-89a9-874bc8741b1c.png)
![image](https://user-images.githubusercontent.com/85833641/124523701-ff2a2e80-ddac-11eb-87b4-a31d1e65bc37.png)
![image](https://user-images.githubusercontent.com/85833641/124523705-03eee280-ddad-11eb-84b8-bcbcdea84a58.png)
![image](https://user-images.githubusercontent.com/85833641/124523712-0bae8700-ddad-11eb-8ef6-cd67ecf3f0bb.png)
![image](https://user-images.githubusercontent.com/85833641/124523713-0f420e00-ddad-11eb-9da7-2ce8e0c963a8.png)
![image](https://user-images.githubusercontent.com/85833641/124523718-136e2b80-ddad-11eb-877e-9ea80ca8c83f.png)
![image](https://user-images.githubusercontent.com/85833641/124523723-179a4900-ddad-11eb-8a30-6d62bc6f019b.png)
![image](https://user-images.githubusercontent.com/85833641/124523730-208b1a80-ddad-11eb-84ff-b2b02abca09c.png)
![image](https://user-images.githubusercontent.com/85833641/124523737-2680fb80-ddad-11eb-8f4c-89ef20667844.png)
![image](https://user-images.githubusercontent.com/85833641/124523742-2aad1900-ddad-11eb-8ee4-463451024863.png)
![image](https://user-images.githubusercontent.com/85833641/124523753-2f71cd00-ddad-11eb-87d4-393b2eaee328.png)
![image](https://user-images.githubusercontent.com/85833641/124523758-34368100-ddad-11eb-9ade-aefe4611a0dd.png)
Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP untuk membuat modul login, kemudian buatlah tabel seperti berikut ini:
![image](https://user-images.githubusercontent.com/85833641/124523767-44e6f700-ddad-11eb-89fa-4a0eaeeb78b4.png)
![image](https://user-images.githubusercontent.com/85833641/124523768-49abab00-ddad-11eb-88f6-6d9060385217.png)
![image](https://user-images.githubusercontent.com/85833641/124523775-503a2280-ddad-11eb-883c-338860beb21d.png)
![image](https://user-images.githubusercontent.com/85833641/124523778-54fed680-ddad-11eb-9fa1-6c2359b6de78.png)
![image](https://user-images.githubusercontent.com/85833641/124523779-58925d80-ddad-11eb-986f-367a7185b134.png)
![image](https://user-images.githubusercontent.com/85833641/124523783-5d571180-ddad-11eb-949c-e26fadc99439.png)
![image](https://user-images.githubusercontent.com/85833641/124523792-61832f00-ddad-11eb-98e5-3e5f4ffb3d6d.png)

![image](https://user-images.githubusercontent.com/85833641/124523763-41537000-ddad-11eb-8757-c0af59fb8850.png)
![image](https://user-images.githubusercontent.com/85833641/124523810-75c72c00-ddad-11eb-9ece-8a38937d4e0f.png)
![image](https://user-images.githubusercontent.com/85833641/124523823-7eb7fd80-ddad-11eb-8442-c3bbb4ed6094.png)
![image](https://user-images.githubusercontent.com/85833641/124523817-7a8be000-ddad-11eb-9b12-265fcca7e45a.png)
![image](https://user-images.githubusercontent.com/85833641/124523826-81b2ee00-ddad-11eb-9823-813c1141ba94.png)
![image](https://user-images.githubusercontent.com/85833641/124523832-87a8cf00-ddad-11eb-9ace-64e0bfaaae9a.png)
![image](https://user-images.githubusercontent.com/85833641/124523840-8d9eb000-ddad-11eb-83b4-dcf672e52afb.png)
LANGKAH 1 - Membuat Pagination
![image](https://user-images.githubusercontent.com/85833641/124523858-9abb9f00-ddad-11eb-87c9-96acb056b89e.png)
![image](https://user-images.githubusercontent.com/85833641/124523862-9f805300-ddad-11eb-9379-3decce5881b3.png)
![image](https://user-images.githubusercontent.com/85833641/124523866-a4dd9d80-ddad-11eb-9c51-5c95da3637f6.png)
![image](https://user-images.githubusercontent.com/85833641/124523872-a9a25180-ddad-11eb-8d2f-7bb14ce03fd3.png)
![image](https://user-images.githubusercontent.com/85833641/124523874-aeff9c00-ddad-11eb-9568-260c2700e098.png)


## Aplikasi Toko Baju berbasis Website

Ketentuan UAS: 
| Fitur          |   | Ket.                                                                   |
| :------------- | :--- |  :---------------------------------------------------------------------: |
| Menggunakan Bootstrap  | ✅    | Sudah menggunakan Bootstrap baik di halaman utama maupun dashboard admin|
| Bisa CRUD Menggunakan Laravel  | ✅    | Sudah bisa CRUD Untuk bagian produk dan dapat ditampilkan di table product yang ada di laman admin maupun di laman utama |



Fitur Aplikasi: 
| Fitur          |   | Ket.                                                                   |
| :------------- | :--- |  :---------------------------------------------------------------------: |
| Halaman Utama  | ✅    | Sudah tersedia fitur laman utama, disana terdapat beberapa produk yang dirender berdasarkan data dari database |
| Fitur Login    |     | Fitur Belum Tersedia, cukup klik login atau ke route <b>/admin/dashboard</b> untuk ke menu admin |
| Halaman Admin  | ✅    | Terdapat menu Dashboard, Products, Orders, dan Users |
| Halaman User   |        | Fitur Belum Tersedia                                                  |
| CRUD Produk    | ✅    | Sudah bisa CRUD dan dapat tampil di halaman utama maupun tabel admin yang ada di <b>/admin/products</b> |
| CRUD User      | ✅    | (Sementara baru membuat Read, nantinya aplikasi ini akan dikembangkan) |


## Tools

| Tools          | Ket.  |
| :------------- | :---: | 
| PHP            | ✅    |
| Laravel        | ✅    |
| Bootstrap      | ✅    |
| Vite           | ✅    |

## Development

```bash
git clone https://github.com/riskykrnawan/uas-laravel.git
cd uas-laravel
composer upgrade
npm install
```     

Don't forget to add .env ❗


```bash
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan storage:link
npm run dev
```     

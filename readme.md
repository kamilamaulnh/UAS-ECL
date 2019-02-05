## Tentang UAS ECL

- Disini saya menggunakan Laravel ver. 5.7 dan PHP ver. 7.3.1

## Langkah Pengerjaan

- Saya menggunakan template AdminLTE 2, file dapat di download pada : https://codeload.github.com/almasaeed2010/AdminLTE/zip/v2.3.11

- Pertama saya membuat CRUD (Create, Read, Update, Delete) untuk data Kelas, dengan menggunakan tabel 't_kelas' dari hasil migrating.
- Dengan langkah yang hampir sama saya membuat CRUD untuk data siswa dengan merelasikan tabel 't_siswa' dengan tabel 't_kelas' dengan menggunakan _Eloquent Relation_.
- Selanjutnya saya membuat Autentikasi menggunakan fitur yang telah disediakan oleh Laravel, saya hanya memperbaharui nya sedikit untuk menyesuakan kebutuhan.
- Yang terakhir saya membuat fitur Upload foto (jpeg/png) untuk data siswa.
- Gunakan database yang telah disediakan dengan nama : 'db_laravel_siswa.sql'

Terima kasih, semoga bermanfaat :) 

Wafaa Kamilah Maulani - 10515171 (ECL-10)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).


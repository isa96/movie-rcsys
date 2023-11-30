# Movie Recommender System

## Project Overview
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada zaman sekarang, seperti yang kita ketahui terdapat banyak sekali pilihan dan kita harus memilih pilihan tersebut. Akibat banyaknya pilihan, setiap orang pernah memiliki masalah untuk memilih [1]. Contohnya pada saat kita ingin menonton film, banyak sekali film di dunia ini yang telah bermunculan dan kita menjadi kebingungan mengenai film apa yang sebaiknya kita nonton\.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Oleh karena itu, perusahaan film seperti *Netflix* pun mulai mengembangkan sistem rekomendasi untuk membantu penggunanya agar lebih mudah memilih film yang mereka inginkan. Sistem rekomendasi dapat membantu pengguna untuk memilih item-item (dalam studi kasus ini adalah film) dari banyaknya koleksi yang tersedia [2]\.

**Alasan mengapa masalah ini perlu diselesaikan**:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Karena masalah ini dapat membuat pengguna kebingungan dengan apa yang akan mereka pilih sehingga mereka membutuhkan waktu lama untuk memilih\.

## Business Understanding

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah:
- Bagaimana membantu pengguna untuk memilih film yang menarik bagi mereka, sehingga mereka tidak perlu membuang-buang waktu untuk mencari film yang menarik dan akan mereka nonton ?\.
- Bagaimana membuat perusahaan lebih menarik bagi pengguna, dikarenakan jika pengguna tidak menemukan film yang menarik maka pengguna akan merasa bosan dan tidak ingin lagi menonton film di *platform* tersebut\.

### Goals

Menjelaskan tujuan proyek yang menjawab pernyataan masalah:
- Membuat sistem rekomendasi film bagi pengguna agar pengguna bisa menemukan film yang mereka gemari, dan dapat membantu perusahaan agar tidak kehilangan penggunanya\.

## Data Understanding
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data di ambil dari *platform kaggle* yaitu [Movie Recommendation System](https://www.kaggle.com/datasets/dev0914sharma/dataset?select=Movie_Id_Titles.csv). Pada dataset ini ada 2 *files* yaitu: *Movie_Id_Titles.csv* dan *Dataset.csv*

Variabel-variabel pada *Movie_Id_Titles.csv* dataset adalah sebagai berikut:
- item_id : merupakan kunci dari dataset dan merupakan id dari tiap film\.
- title : merupakan judul film yang terdapat di dataset\.

Variabel-variabel pada *Dataset.csv* t adalah sebagai berikut:
- item_id : merupakan kunci dari dataset dan merupakan id dari tiap film\.
- user_id: merupakan id untuk setiap pengguna\.
- rating: merupakan penilaian pengguna terhadap sebuah film\.
- timestamp: merupakan waktu yang pengguna telah habiskan untuk menonton film tersebut\.

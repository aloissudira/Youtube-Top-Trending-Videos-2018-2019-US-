# Youtube-Top-Trending-Videos-2017-2018-US-
Trough this data i will give recommendations for youtube content creators, what common chararecteristics do top trending youtube videos have.

Analisis Top Trending Youtube ini memiliki batasan data dari 1 Januari 2017 hingga 6 Desember 2018. data diambil dari link berikut: (https://www.kaggle.com/datasets/datasnaek/youtube-new). berdasarkan data yang ada dilakukan pemahaman dan pembersihan data yang tidak relevan dan juga tidak masuk akal. sehingga dasar analisis akan dilakukan menurut data berikut
 1.   channel_title = tipe data object ini memiliki info nama channel  
 2.   category_id = tipe data integer ini memiliki info nomor kategori
 3.   category = tipe data object ini memiliki info jenis kategori yang menjelaskan integer category_id
 4.   publish_time = tipe data datetime ini memiliki info waktu upload video
 5.   day_post = tipe data datetime ini memiliki info hari upload video
 6.   hour_post  = tipe data datetime ini memiliki info jam upload video
 7.   trending_date  = tipe data datetime ini memiliki info waktu video trending
 8.   comments_disabled = tipe data boolean ini memiliki info apakah video melaukan disable terhadap comment
 9.   ratings_disabled = tipe data boolean ini memiliki info apakah video melaukan disable terhadap ratings
 10.  tags_count = tipe data integer ini memiliki info jumlah tags yang dimasukkan oleh uploader
 11.  views  = tipe data integer ini memiliki info jumlah views video
 12.  likes = tipe data integer ini memiliki info jumlah likes video 
 13.  dislikes  = tipe data integer ini memiliki info jumlah dislikes video
 14.  comment_count = tipe data integer ini memiliki info jumlah comment pada video
 15.  duration (days) = tipe data integer ini memiliki info durasi waktu dari video upload hingga video menjadi trending
 
 selanjutnya data data ini diolah berdsarkan outline berikut
 1.  Details Analysis
      * title analysis
      * channel_title analysis
      * category_analysis
 2.  Details Factor Analysis
      * comment_disabled dan ratings_disabled analysis
      * tags_count analysis
 3.  Feedback Analysis
      * Feedback correlation
      * view analysis
      * like and dislikes analysis
      * duration analysis
 4.  Posting Analysis
      * day_post analysis
      * hour_post analyis
      
lalu terakhir disertakan juga kesimpulan dan rekomendasi untuk konten kreator dalam melakukan upload video di youtube pada area US

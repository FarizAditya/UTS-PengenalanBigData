# UTS-PengenalanBigData
# 3 DBMS untuk mengelola Big Data
<b>1. Oracle<br><b>
  ![Optional Text](../master/images/oracle.png)<br>
  Oracle merupakan aplikasi pengolah database yang bersifat proprietary (komersial) yang dikembangkan oleh Oracle Corporation. Pengolah database ini terbagi dalam beberapa varian dengan segmen dan tujuan penggunaan yang berbeda-beda. Database jenis ini biasanya digunakan   oleh perusahaan yang besar karena database ini sangat mahal.<br><br>
<b>2. SQLServer<br><b>
![Optional Text](../master/images/SQLServer.png)<br>
  Microsoft SQL Server merupakan sebuah sistem manajemen basis data relasional (RDBMS) produk Microsoft. Bahasa query utamanya adalah Transact-SQL yang merupakan implementasi dari SQL standar ANSI/ISO yang digunakan oleh Microsoft dan Sybase. Pada umumnya SQL Server digunakan di dunia bisnis yang memiliki basis data berskala kecil sampai dengan menengah, tetapi kemudian berkembang dengan digunakannya SQL Server pada basisdata skala besar.<br><br>
<b>3. IBM DB 2<br><b>
![Optional Text](../master/images/DB2.png)<br>
  IBM DB2 merupakan aplikasi pengolah database yang dikembangkan IBM secara proprietary (komersial). DB2 terbagi menjadi 3 varian, yaitu DB2 untuk Linux – Unix – Windows, DB2 untuk z/OS (mainframe), dan DB2 untuk iSeries (OS/400).<br><b>
#  Instalasi SQLServer pada windows
  1. Pertama-tama anda harus mendownload installer SQL Server-nya terlebih dahulu. Disini saya masih menggunakan SQL Server 2017 yang versi Developer. Selain gratis, fiturnya juga cukup lengkap.<br>
  2. Pada jendela awal instalasi, pilih Custom.
  ![Optional Text](../master/images/sql1.png)<br>
  3. Untuk lokasi instalasinya biarkan default, kemudian pilih Install.
  ![Optional Text](../master/images/sql2.png)<br>
  4. SQL Server akan mendownload beberapa package dan file-file yang diperlukan. Proses ini membutuhkan koneksi internet dan agak lama juga karena file-file yang didownload lebih dari 1GB. Maka dari itu, disarankan bagi untuk terhubung ke jaringan WiFi.
  ![Optional Text](../master/images/sql3.png)<br>
  5. Jika proses downloading selesai. Masuk ke folder C:\SQL2017\Developer_ENU kemudian klik 2X SETUP.
  ![Optional Text](../master/images/sql4.png)<br>
  6. Selanjutnya pilih opsi Installation yang berada di sebelah kiri.
  ![Optional Text](../master/images/sql5.png)<br>
  7. Selanjutnya pilih opsi yang ditandai dengan kotak merah.
  ![Optional Text](../master/images/sql6.png)<br>
  8. Pilih Developer.
  ![Optional Text](../master/images/sql7.png)<br>
  9.Centang pada opsi I accept the license terms kemudian pilih Next. 
  ![Optional Text](../master/images/sql8.png)<br>
  10. Pilih Next lagi.
  ![Optional Text](../master/images/sql9.png)<br>
  11. Pastikan tidak ada rule yang failed. Kalau masih warning tidak masalah. Lanjut pilih Next.
  ![Optional Text](../master/images/sql10.png)<br>
  12. Centang Database Engine Services kemudian pilih Next.
  ![Optional Text](../master/images/sql11.png)<br>
  13. Beri nama untuk SQL Server anda. Kemudian pilih Next.
  ![Optional Text](../master/images/sql12.png)<br>
  14. Pilih Next lagi.
  ![Optional Text](../master/images/sq1l3.png)<br>
  15. Pilih Mixed mode kemudian beri password yang kuat namun mudah diingat. Pilih Add Current User kemudian pilih Next.
  ![Optional Text](../master/images/sq1l4.png)<br>
  16.Selanjutnya pilih Install.
  ![Optional Text](../master/images/sql15.png)<br>
  17. Tunggu proses instalasi hingga selesai.
  ![Optional Text](../master/images/sql16.png)<br>
  18. Pastikan tidak ada feature yang error pada kolom status. Jika mendapatkan notifikasi seperti ini, pilih OK.
  ![Optional Text](../master/images/sql17.png)<br>
  19. Instalasi SQL Server berhasil.
    ![Optional Text](../master/images/sql18.png)<br><br>
 # CRUD Operations in SQL Server
  CRUD adalah operasi dasar dalam RDBMS apa pun, dan tip ini akan memerinci operasi CRUD di SQL Server.
 # Apa itu CRUD?
  CRUD berarti Create, Read, Update, Delete dan itu bisa berarti hal yang berbeda dalam sistem yang berbeda, tetapi untuk SQL Server, umumnya dianggap memetakan ke operasi SQL berikut pada catatan tabel.
  
  
 # Apa itu SQL Server Big Data Cluster?
  Dimulai dengan SQL Server 2019 (15.x), SQL Server Big Data Clusters memungkinkan Anda untuk menyebarkan cluster SQL Server, Spark, dan wadah HDFS yang berjalan pada Kubernetes. Komponen-komponen ini berjalan berdampingan untuk memungkinkan Anda membaca, menulis, dan memproses data besar dari Transact-SQL atau Spark, memungkinkan Anda untuk dengan mudah menggabungkan dan menganalisis data relasional bernilai tinggi dengan data besar volume tinggi.<br>
SQL Server 2019 (15.x) memperkenalkan SQL Server Big Data Clusters.

Gunakan SQL Server Big Data Cluster untuk:

Menyebarkan cluster SQL Server, Spark, dan wadah HDFS yang berjalan pada Kubernetes.
1. Baca, tulis, dan proseskan data besar dari Transact-SQL atau Spark.
2. Mudah menggabungkan dan menganalisis data relasional bernilai tinggi dengan data besar volume tinggi.
3. Sumber data kueri eksternal.
4. Menyimpan data besar dalam HDFS yang dikelola oleh SQL Server.
5. Permintaan data dari berbagai sumber data eksternal melalui cluster.
6. Gunakan data untuk AI, pembelajaran mesin, dan tugas analisis lainnya.
7. Menyebarkan dan menjalankan aplikasi di Big Data Clusters.
8. Virtualisasikan data dengan PolyBase . Permintaan data dari SQL Server eksternal, Oracle, Teradata, MongoDB, dan sumber data ODBC dengan tabel eksternal.
9. Memberikan ketersediaan tinggi untuk contoh master SQL Server dan semua database dengan menggunakan teknologi grup ketersediaan Selalu Di.
# Skenario
SQL Server Big Data Cluster memberikan fleksibilitas dalam cara Anda berinteraksi dengan data besar Anda. Anda bisa meminta sumber data eksternal, menyimpan data besar dalam HDFS yang dikelola oleh SQL Server, atau meminta data dari berbagai sumber data eksternal melalui cluster. Anda kemudian dapat menggunakan data untuk AI, pembelajaran mesin, dan tugas analisis lainnya. Bagian berikut memberikan informasi lebih lanjut tentang skenario ini.
# Data virtualization
 ![Optional Text](../master/images/data-virtualization.png)<br><br>
Dengan memanfaatkan SQL Server PolyBase , SQL Server Big Data Cluster dapat meminta sumber data eksternal tanpa memindahkan atau menyalin data. SQL Server 2019 (15.x) memperkenalkan konektor baru ke sumber data.
 # Data lake
  ![Optional Text](../master/images/data-lake.png)<br><br>
 Sekumpulan Big Data SQL Server mencakup kumpulan penyimpanan HDFS yang dapat diskalakan . Ini dapat digunakan untuk menyimpan data besar, berpotensi dicerna dari berbagai sumber eksternal. Setelah data besar disimpan dalam HDFS di cluster data besar, Anda bisa menganalisis dan meminta data dan menggabungkannya dengan data relasional Anda.
# Scale-out data mart
 ![Optional Text](../master/images/data-mart.png)<br><br>
SQL Server Big Data Clusters menyediakan penghitungan dan penyimpanan skala-out untuk meningkatkan kinerja analisis data apa pun. Data dari berbagai sumber dapat dicerna dan didistribusikan di seluruh kumpulan data sebagai cache untuk analisis lebih lanjut.
# Integrated AI and Machine Learning
SQL Server Big Data Cluster memungkinkan tugas pembelajaran AI dan mesin pada data yang disimpan dalam kumpulan penyimpanan HDFS dan kumpulan data. Anda bisa menggunakan Spark serta alat AI bawaan di SQL Server, menggunakan R, Python, Scala, atau Java.
 ![Optional Text](../master/images/ai-ml-spark.png)<br><br>
# Management and Monitoring
disediakan melalui kombinasi alat baris perintah, API, portal, dan tampilan manajemen dinamis.

Anda bisa menggunakan Azure Data Studio untuk melakukan berbagai tugas di kluster data besar:

1. Cuplikan internal untuk tugas manajemen umum.
2. Kemampuan untuk menelusuri HDFS, mengunggah file, melihat file, dan membuat direktori.
3. Kemampuan untuk membuat, membuka, dan menjalankan notebook yang kompatibel dengan Jupyter.
4. Wisaya virtualisasi data untuk menyederhanakan pembuatan sumber data eksternal (diaktifkan oleh Ekstensi Virtualisasi Data ).
# Architecture
Kumpulan data besar SQL Server adalah sekelompok wadah Linux yang diatur oleh Kubernetes .

Konsep Kubernetes
Kubernetes adalah orkestra wadah sumber terbuka, yang dapat mengukur penyebaran kontainer sesuai kebutuhan. Tabel berikut mendefinisikan beberapa terminologi Kubernetes yang penting:

**Cluster**   Cluster Kubernetes adalah seperangkat mesin, yang dikenal sebagai node. Satu simpul mengontrol gugus dan ditunjuk sebagai simpul utama; simpul yang tersisa adalah simpul pekerja. Master Kubernetes bertanggung jawab untuk mendistribusikan pekerjaan di antara para pekerja, dan untuk memantau kesehatan cluster.<br>
**Node**    Sebuah node menjalankan aplikasi yang di kemas. Ini bisa berupa mesin fisik atau mesin virtual. Cluster Kubernetes dapat berisi campuran mesin fisik dan node mesin virtual.<br>
**Pod**	Pod adalah unit penyebaran atom Kubernet. Pod adalah grup logis dari satu atau lebih wadah - dan sumber daya terkait - yang diperlukan untuk menjalankan aplikasi. Setiap pod berjalan pada sebuah node; sebuah node dapat menjalankan satu atau lebih pod. Master Kubernetes secara otomatis memberikan pod ke node di cluster.<br>
 	
Dalam SQL Server Big Data Clusters, Kubernetes bertanggung jawab untuk keadaan SQL Server Big Data Clusters; Kubernet membangun dan mengkonfigurasi node cluster, memberikan pod ke node, dan memantau kesehatan cluster.<br>
# Big data clusters architecture
Diagram berikut menunjukkan komponen-komponen dari kumpulan data besar untuk SQL Server.
 ![Optional Text](../master/images/architecture-diagram-overview.png)<br><br>
# Controller
Pengontrol menyediakan manajemen dan keamanan untuk cluster. Ini berisi layanan kontrol, toko konfigurasi, dan layanan tingkat cluster lainnya seperti Kibana, Grafana, dan Pencarian Elastis.
# Compute pool
Compute pool menyediakan sumber daya komputasi untuk cluster. Ini berisi node yang menjalankan SQL Server di Linux pod. Pod di kumpulan komputasi dibagi menjadi instance SQL Compute untuk tugas pemrosesan tertentu.
# Data pool
Kumpulan data digunakan untuk persistensi dan caching data. Kumpulan data terdiri dari satu atau lebih pod yang menjalankan SQL Server di Linux. Ini digunakan untuk mencerna data dari query SQL atau pekerjaan Spark. SQL Server big data cluster data mart tetap di kumpulan data.
# Storage pool
Kumpulan penyimpanan terdiri dari kumpulan kumpulan penyimpanan yang terdiri dari SQL Server di Linux, Spark, dan HDFS. Semua node penyimpanan dalam SQL Server big data cluster adalah anggota dari cluster HDFS.

   
  

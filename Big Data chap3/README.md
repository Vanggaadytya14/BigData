# Big-Data
Tugas Minggu 5

## Chapter 3

### Python

<b> Acccumulator</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Code</b></td>
    <td><b style="font-size:30px">Output</b></td>
 </tr>
<tr>
    <td> https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/Accumulator/Accumulator.py</td>
    <td><img alt="Dark" src="https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/Accumulator/Accumulator.png"></td>
 </tr>
 <tr>
   <td colspan="2">
      <b style="font-size:30px"></b>
      <p>
         1. Sc =>  variabel yang merujuk pada objek SparkContext 
      </p>
      <p>
         2. Parallelize => fungsi dalam SparkContext yang   digunakan untuk membuat RDD (Resilient Distributed Datasets) dari koleksi 
      </p>
      <p>
      3. Accumulator => merupakan variabel yang dapat diakumulasikan, yaitu memiliki operasi “+” yang komutatif dan asosiatif. 
      </p>
      <p>
       4. Lambda => merupakan kata kunci yang digunakan untuk membuat fungsi anonim. Fungsi ini adalah fungsi satu baris kecil yang tidak memiliki nama.
      </p>
      <p>
          5. Value => nilai dari accumulator
      </p>
   </td>
 </tr>
</table>
<b> BroadCast</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Code</b></td>
    <td><b style="font-size:30px">Output</b></td>
 </tr>
 <tr>
    <td>https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/BroadCast/BroadCast.py</td>
    <td><img alt="Dark" src="https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/BroadCast/BroadCast.png"></td>
 </tr>
 <tr>
   <td colspan="2">
      <b style="font-size:30px">Penjelasan</b>
      <p>
         1. Broadcast =>  fungsi yang dapat digunakan untuk menunjukkan bahwa dataset cukup kecil dan harus disiarkan. Ini berarti bahwa dataset akan dikirim ke setiap node dalam cluster hanya sekali, daripada mengirimkan salinan dengan tugas. Ini dapat membantu mengurangi biaya komunikasi dan meningkatkan kinerja.
      </p>
      <p>
         2. List => digunakan untuk membuat objek daftar, yang merupakan koleksi item yang terurut.
      </p>
      <p>
         3. Range => digunakan untuk menghasilkan urutan angka.
      </p>
   </td>
 </tr>
</table>
<b>3. Log Analytics</b>
<table border="0">
 <tr>
    <td><b style="font-size:30px">Code</b></td>
    <td><b style="font-size:30px">Output</b></td>
 </tr>
 <tr>
    <td> https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/LogAnalytics/LogAnalytics.py</td>
    <td><img alt="Dark" src="https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/LogAnalytics/LogAnalytics.png"></td>
 </tr>
 <tr>
   <td colspan="2">
      <b style="font-size:30px">Penjelasan</b>
      <p>
         1. TextFile =>  fungsi yang digunakan untuk membaca file teks dan mengembalikan RDD yang mewakili data dalam file tersebut
      </p>
      <p>
         2. Filter => fungsi transformasi yang digunakan untuk mengembalikan RDD baru dengan subset data yang memenuhi kondisi tertentu
      </p>
      <p>
      3. Cache => fungsi transformasi yang dapat digunakan pada DataFrame, Dataset, atau RDD ketika Anda ingin melakukan lebih dari satu tindakan.  
      </p>
      <p>
       4. Count => fungsi aksi yang digunakan untuk menghitung jumlah baris dalam DataFrame, Dataset, atau RDD.
      </p>
   </td>
 </tr>
</table>
<b>Pair RDD</b>
    <table border="0">
 <tr>
    <td><b style="font-size:30px">Code</b></td>
    <td><b style="font-size:30px">Output</b></td>
 </tr>
 <tr>
    <td> https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/pairRDD/PairRDD.py</td>
    <td><img alt="Dark" src="https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/pairRDD/PairRDD.png"></td>
 </tr>
 <tr>
   <td colspan="2">
      <b style="font-size:30px">Penjelasan</b>
      <p>
         1. map => mengubah setiap elemen RDD menjadi elemen baru dengan menerapkan fungsi pada elemen tersebut
      </p>
      <p>
         2. collect => mengembalikan semua elemen RDD sebagai daftar ke driver
      </p>
      <p>
         3. len => mengembalikan panjang objek yang dapat diukur, seperti daftar atau string
      </p>
      <p>
         4. keys => mengembalikan daftar kunci dari kolom MapType di spark
      </p>
      <p>
         4. values => mengembalikan daftar nilai dari kolom MapType di spark
      </p>
   </td>
 </tr>
</table>
<b> Understanding RDDs</b>
    <table border="0">
 <tr>
    <td><b style="font-size:30px" width="20%">Code</b></td>
    <td><b style="font-size:30px">Output</b></td>
 </tr>
 <tr>
    <td>https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/UnderstandingRDDs/UnderstandingRDDs.py </td>
    <td><img alt="Dark" src="https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/UnderstandingRDDs/UnderstandingRDDs.png"></td>
 </tr>
 <tr>
   <td colspan="2">
      <b style="font-size:30px">Penjelasan</b>
      <p>
         1. defaultParallelism => digunakan untuk mendapatkan jumlah partisi yang digunakan oleh spark
      </p>
      <p>
         2. getNumPartitions => digunakan untuk mendapatkan jumlah partisi dari RDD
      </p>
      <p>
         3. mapPartitionsWithIndex => digunakan untuk mengubah setiap partisi RDD menjadi elemen baru dengan menerapkan fungsi pada partisi tersebut
      </p>
      <p>
         4. repartition => digunakan untuk mengubah jumlah partisi RDD
      </p>
      <p>
         5. coalesce => digunakan untuk mengubah jumlah partisi RDD dengan mempertahankan jumlah partisi yang ada
      </p>
      <p>
         6. toDebugString => digunakan untuk mendapatkan informasi tentang RDD
      </p>
   </td>
 </tr>
</table>
<b>Word Count </b>
    <table border="0">
 <tr>
    <td><b style="font-size:30px">Code</b></td>
    <td><b style="font-size:30px">Output</b></td>
 </tr>
 <tr>
    <td>https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/WordCount/WordCount.py </td>
    <td><img alt="Dark" src="https://github.com/Vanggaadytya14/BigData/blob/main/Big%20Data%20chap3/WordCount/wordcount.png"></td>
 </tr>
 <tr>
   <td colspan="2">
      <b style="font-size:30px">Penjelasan</b>
      <p>
         1. flatMap => digunakan untuk mengubah setiap elemen RDD menjadi elemen baru dengan menerapkan fungsi pada elemen tersebut
      </p>
      <p>
         2. reduceByKey => digunakan untuk menggabungkan semua elemen RDD dengan fungsi yang sama dengan kunci yang sama
      </p>
      <p>
         3. split => digunakan untuk memecah string menjadi daftar string
      </p>
   </td>
 </tr>
</table>

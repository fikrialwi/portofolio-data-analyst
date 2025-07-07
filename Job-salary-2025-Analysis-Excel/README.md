## Insight dari Analisis Gaji Data Global

Berikut adalah beberapa insight kunci yang dapat ditarik dari data gaji yang telah Anda olah:

-----

### 1\. Dinamika Gaji: Rata-rata Tinggi dengan Outlier Signifikan

```
Gaji Rata-rata ($ USD): 151.148,85
Median Gaji ($ USD):    138.900,00
```

  * **Insight**: Adanya perbedaan signifikan antara rata-rata dan median gaji menunjukkan **keberadaan *outlier* gaji yang sangat tinggi** yang menarik nilai rata-rata ke atas. Ini mengindikasikan bahwa beberapa individu atau peran tertentu mendapatkan kompensasi yang jauh di atas standar.

### 2\. Peran Kepemimpinan dan Spesialisasi Mendalam Mendulang Gaji Tertinggi

**Top 5 Pekerjaan Gaji Tertinggi (Per Individu)**


| Jobs Title        | Salary      | Employee Type | Company Location | Company Size |
| :---------------- | :---------- | :------------ | :--------------- | :----------- |
| Architect         | $800.000,00 | FT            | US               | M            |
| Software Engineer | $800.000,00 | FT            | US               | M            |
| AI Architect      | $800.000,00 | FT            | CA               | M            |
| Data Engineer     | $793.136,00 | FT            | AT               | M            |
| Data Analyst      | $774.000,00 | FT            | MX               | M            |


**Top 5 Pekerjaan dengan Rata-rata Gaji Tertinggi**

| Job Title                      | Average Salary  |
| :----------------------------- | :-------------- |
| Research Team Lead             | $450.000,00     |
| Analytics Engineering Manager  | $399.880,00     |
| Data Science Tech Lead         | $375.000,00     |
| Applied AI ML Lead             | $292.500,00     |
| IT Enterprise Data Architect   | $284.090,00     |

  * **Insight**: Peran yang paling banyak muncul di kategori "gaji tertinggi" (seperti Architect, Software Engineer) menunjukkan nilai individual yang ekstrem. Namun, ketika melihat **rata-rata gaji tertinggi**, peran **kepemimpinan** (`Lead`, `Manager`) dan **spesialisasi mendalam** (`Research`, `Analytics Engineering`, `Data Science Tech`) secara konsisten menawarkan kompensasi yang sangat tinggi.

-----

### 3\. Dominasi Geografis AS dan Konsentrasi Pekerjaan Data

**Top 5 Pekerjaan berdasarkan Jumlah Pekerja**


| Job Title          | Number of Employee  | Percentage | 
| :------------------| :------------------ | :--------- | 
| Data Scientist     | 6779                | 10,26%     | 
| Data Engineer      | 6653                | 10,07% |
| Data Analyst       | 6031                | 9,13% |
| Software Engineer  | 4564                | 6,91% |
| Engineer           | 4045                | 6,12% |


  * **Insight**: Peran **Data Scientist, Data Engineer, dan Data Analyst** adalah yang paling banyak di pasar kerja ini, menunjukkan tingginya permintaan untuk keahlian inti di bidang data.

**Top 5 Lokasi Perusahaan**


|Company Location |  Number of Company | Percentage |
| :----------- | :---------------- | :---------------- |
|US |               55439 |              83,92% |
|CA |               4084 |              6,18% |
|GB |               2605 |              3,94% |
|AU |               456  |              0,69% |
|DE |               351  |              0,53% |


  * **Insight**: **Amerika Serikat (US)** secara mutlak mendominasi sebagai pusat lokasi perusahaan, mengindikasikan bahwa sebagian besar peluang dan talenta terkonsentrasi di sana. Kanada (CA) dan Inggris (GB) juga memiliki kehadiran yang signifikan.

-----

### 4\. Gaji Remote Mirip Office, Hybrid Lebih Rendah

**Top 5 Tipe Pekerja (Remote, Semi-Remote, Office)**
 
|Type Work Employee | Employee Remote Ratio | Number of Employee | Percentage|
| :-----| :-----| :-----| :-----|
|Office|              0   |                   49604|               75,09%|
|Remote|              100|                    16140 |              24,43%|
|Hybrid|              50|                     319    |             0,48%|


**Rata-Rata Gaji Pekerja berdasarkan Remote Ratio**

|Type Work Employee|  Employee Remote Ratio|  Minimum Salary|  Maximum Salary|  Average Salary|
|:---- |:---- |:---- |:---- |:---- 
|Office|              0|                      $15.000,00|      $800.000,00|     $152.295,98|
|Remote|              100|                    $15.000,00|      $800.000,00|     $148.999,24|
|Hybrid|              50|                     $15.129,00|      $423.000,00|     $81.532,05|

  * **Insight**: Rata-rata gaji untuk **pekerja *remote* ($148.999,24)** dan **pekerja *office* ($152.295,98)** relatif **mirip**. Ini menunjukkan bahwa **fleksibilitas lokasi kerja mungkin tidak berdampak signifikan pada tingkat gaji** di pasar ini. Namun, **pekerja *hybrid* memiliki rata-rata gaji yang jauh lebih rendah ($81.532,05)**. Ini adalah poin menarik yang mungkin memerlukan penyelidikan lebih lanjut, apakah ini karena peran yang berbeda atau faktor lainnya.

-----

### 5\. Ukuran Perusahaan Menengah Menawarkan Gaji Kompetitif

**Jumlah Perusahaan berdasarkan Ukuran**

|Company Size  |Number of Company  |Percentage|
| :---: | :---: | :---: |
|M |            64319              |97,36%|
|L|             1529               |2,31%|
|S|             215                |0,33%|


**Rata-Rata Gaji berdasarkan Ukuran Perusahaan**

|Company Size  |Average Salary|
| :--- | :--- |
|M             |$151.682,35|
|L             |$137.591,24|
|S             |$87.963,96|

  * **Insight**: Mayoritas perusahaan berukuran **Menengah (M)**. Menariknya, **rata-rata gaji di perusahaan Menengah ($151.682,35) sedikit lebih tinggi** daripada di perusahaan Besar (L), sementara perusahaan Kecil (S) menawarkan gaji yang jauh lebih rendah. Ini bisa menyiratkan bahwa perusahaan menengah sangat kompetitif dalam menarik talenta.

-----

### 6\. Kombinasi Faktor Kunci Pendorong Gaji Sangat Tinggi
 
|Job Title                  |Company Location  |Remote Ratio  |Average Salary (USD)  |Number of Data Points|
| :------ | :------ | :------ | :------ | :------
| AI Architect               |CA                |100           |$800.000,00           |1|
| ML Infrastructure Engineer |GB                |0             |$465.625,00           |2|
| Research Team Lead         |US                |0             |$450.000,00           |2|
| AI Scientist               |IL                |0             |$417.937,00           |1|
| Head of Machine Learning   |US                |100           |$410.500,00           |2|

  * **Insight**: Ada kombinasi spesifik **peran yang sangat terspesialisasi** (seperti AI Architect, ML Infrastructure Engineer), **lokasi perusahaan tertentu** (CA, GB, IL), dan **rasio *remote*** (baik `0`/Office maupun `100`/Remote) yang secara konsisten menghasilkan **gaji rata-rata yang sangat tinggi**.
  * **Pentingnya Jumlah Data Poin**: Perhatikan `Number of Data Points`. Beberapa kombinasi gaji tertinggi hanya didasarkan pada 1 atau 2 data poin, yang berarti ini bisa jadi **kasus *outlier*** dan bukan tren yang luas. Kombinasi dengan lebih banyak data poin akan memberikan insight yang lebih kuat.
  * Link:
   * [link data publication](https://docs.google.com/spreadsheets/d/e/2PACX-1vQq1zXuAQ94VNhsxOgBNM9M7UztHK2ameJ-UsR0m3o8re3HjqdPzRZxQuYa-Dw_IfzzPYx7-n2SPib9/pubhtml)
   * [Link google sheet](https://docs.google.com/spreadsheets/d/1SHdpkeOmu76o1wSw8qoqguJDuj68anSagxsyzfxXnV4/edit?usp=sharing)

  * *Note*: data ini diproses menggunaan google sheet. Jadi apabila ada error dalam penggunaan formula bisa disebabkan karena ada perbedaan kapabilitas antara ms Excel dan google Sheet

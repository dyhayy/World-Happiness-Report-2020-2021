# __World Happiness Analysis 2020-2021__
----
## A. OVERVIEW
Happiness adalah kondisi emosional yang tergambar oleh perasaan senang, kepuasan, dan kepuasan diri. Meskipun ada banyak definisi kebahagiaan, itu sering dianggap sebagai sesuatu yang melibatkan perasaan positif dan kepuasan dalam kehidupan.

The World Happiness Report adalah survei penting mengenai kondisi kebahagiaan global dari tahun 2015 hingga 2019. Laporan ini telah mendapatkan pengakuan global karena pemerintah, organisasi, dan masyarakat sipil semakin banyak menggunakan indikator kebahagiaan untuk menginformasikan keputusan pembuatan kebijakan mereka. Para ahli terkemuka di berbagai bidang ekonomi, psikologi, analisis survei, statistik nasional, kesehatan, kebijakan publik, dan banyak lagi menjelaskan bagaimana pengukuran kesejahteraan dapat digunakan secara efektif untuk menilai kemajuan suatu negara. Laporan ini membahas kondisi Happiness di dunia saat ini dan menunjukkan bagaimana ilmu pengetahuan baru tentang kebahagiaan secara personal dan nasional.

Proyek ini menganalisis dataset Laporan Kebahagiaan Dunia pada tahun 2020-2021 dengan menggunakan library Python untuk ilmu data seperti Pandas, Matplotlib, dan Seaborn, dengan tujuan memvisualisasikan data melalui plot dan grafik guna membantu pemahaman data dan memberikan wawasan yang lebih mendalam tentang faktor-faktor yang memengaruhi kebahagiaan secara global.

## B. DATASET
------
Project ini menggunakan dataset World Happiness Report 2020-2021, yang dapat ditemukan di situs web resmi. Dataset ini 
berisi 20 kolom dan 301 baris, dengan setiap baris mewakili sebuah negara dan setiap kolom mewakili variabel yang terkait 
dengan kebahagiaan.

dataset : https://www.kaggle.com/datasets/mathurinache/world-happiness-report/?select=2020.csv <br>
dengan variabel sebagai berikut :
| Plugin | README |
| ------ | ------ |
|`Country name`|Nama Negara|
|`Regional indicator`|Wilayah tempat Negara berada|
|`Ladder score`|Skor Kebahagiaan untuk Negara|
|`Standard error of ladder score`|Std Err untuk Skor Kebahagiaan|
|`upperwhisker`|nilai tertinggi yang tidak terlalu ekstrem||
|`lowerwhisker`|nilai terendah yang tidak terlalu ekstrem|
|`Logged GDP per capita`|Pendapatan Domestik Bruto (PDB) per kapita yang telah disesuaikan dengan Purchasing Power Parity (PPP) atau daya beli.|
|`Social support`|Dukungan sosial (memiliki seseorang yang dapat diandalkan)|
|`Healthy life expectancy` |Angka Harapan Hidup Sehat (HLE), menggambarkan berapa lama seseorang diharapkan hidup dalam kondisi sehat.|
|`Freedom to make life choices`|Kebebasan untuk menentukan pilihan hidup|
|`Generosity`|Kemurahan hati, tergambar dari pertanyaan GWP "Apakah Anda pernah menyumbangkan uang untuk kegiatan amal dalam satu bulan terakhir?" pada PDB per kapita.|
|`Perceptions of corruption` |Ukurannya rata-rata nasional dari tanggapan survei terhadap dua pertanyaan dalam GWP: "Apakah korupsi tersebar luas di seluruh pemerintahan atau tidak" dan "Apakah korupsi tersebar luas di dunia usaha atau tidak?"|
|`Ladder score in Dystopia` |Skor Kebahagiaan untuk negara fiksi Dystopia. Dystopia digunakan sebagai garis dasar, skor terendah karena memiliki penduduk paling tidak bahagia di dunia.|

## ✨ C. INSIGHT✨
----
1. Rata rata **Ladder Score** atau heppiness score in the world pada tahun 2020- 2021 adalah __5.5__.
2. **GDP** atau Pendapatan Domestik Bruto paling **rendah** yang diperoleh suatu negara yaitu sebesar __6.49__
3. **Healthy life expectancy** atau Angka Harapan Hidup Sehat memiliki nilai rata-rata yang cukup tinggi yaitu __64.7__
4. Tingkat Kebahagian dipengaruhi oleh <br> - Pendapaatan Domestik Bruto <br> - Social Support <br> - Angka Harapan Hidup Sehat <br> - Kebebasan Berpendapat disuatu negara<br> - Kasus Korupsi.
5. 10 negara dengan `Ladder score` **paling tinggi**, yaitu Finland, Denmark, Switzerland, Iceland, Netherlands, 
Norway, Sweden, New Zealand, Austria, dan Luxembourg. Dan 10 negara dengan `Ladder score` **paling rendah** yaitu, Yemen, Lesotho, Malawi, Tanzania, Central African Republic, Botswana, Rwanda, Zimbabwe, South Sudan, dan Afghanistan 
6. Regional yang memiliki rata-rata `Ladder score` __tertinggi__ terdapat pada region North America and ANZ dan Western Europev, sedangkan regional yang memiliki rata-rata `Ladder score` __terendah__ terdapat pada region South Asia dan Sub-Saharan Africa.
7. Region dengan rata-rata `GDP` __paling tinggi__ didunia terletak pada __North America and ANZ dan Western Europe__, yaitu memiliki GDP sebesar 11,2% dari total GDP dunia. Dan __Sub-Saharan Africa__ memiliki rata-rata `GDB` yang paling rendah, yaitu sebesar 8,3% dari total GDP dunia
8. Berdasarkan diagram diatas, Logged GDP per capita berkorelasi positif dengan Healthy life expectancy, artinya semakin naik angka GDP maka semakin naik juga Angka Harapan Hidup Sehat. Namun tidak mempengaruhi Leadder score in Dystopia.
9. Tingkat kebahagian pada regional **Western Europev** memiliki angka yang **sangat tinggi** karena region ini memiliki 
Pendapatan Domestik Bruto yang tinggi, angka social support yang tinggi, angka Harapan Hidup Sehat yang tinggi, memiliki Kebabasan berpendapat yang besar, dan memiliki kasus korupsi yang rendah. 
10. Sedangkan, pada regional **Sub-Saharan African** memiliki angka yang **sangat rendah** karena pada region ini memiliki Pendapatan Domestik Bruto yang rendah, angka social support yang rendah, angka Harapan Hidup Sehat yang rendah, memiliki Kebabasan berpendapat yang kurang, dan memiliki kasus korupsi yang tinggi. 

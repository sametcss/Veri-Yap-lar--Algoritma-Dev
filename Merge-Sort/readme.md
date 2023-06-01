<h1>Merge Sort Proje</h1>

<h2>Soru 1</h2>

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

<h3>Cevap 1</h3>

[16,12,11] - [8,12,22] - ilk başda 3 er gruplara ayırıyoruz

[16] - [21,11] - [8,12] -  [22] - daha sonra 16 ve 22 tek diğerleri çift gruplara ayırıyoruz

[16] - [21] - [11] - [8] - [12] -  [22] - hepsini tekerli gruplara ayırana kadar bu işlemimiz devam ediyor

[16] - [11,21] - [8,12] -  [22] - yine ilk ve son değerler tekli gruplara bırakılarak diğer gruplar küçük değerden büyüğe gruplanıyor

[11,16,21] - [8,12,22] - tekli gruplar da küçükten büyüğe şeklinde gruplara dahil ediliyor

[8,11,12,16,21,22] - en sonda küçükten büyüğe sıralanıp bitiriliyor.

<h2>Soru 2</h2>

Big-O gösterimini yazınız.

<h3>Cevap 2</h3>

2^x=n = O(nlogn)
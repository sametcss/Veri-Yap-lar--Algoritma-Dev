<h1>Insertion Sort Proje</h1>

<h2>Soru 1</h2>

[22,27,16,2,18,6] -> Insertion Sort

<ol>
    <li>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    <li>Big-O gösterimini yazınız.
    <li>Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
</li>
    
<h3>Cevap 1</h3>

ilk başta dizinin en küçük elamanı bulunur ve n-1 olarak sırası ile devam eder ---> [2,27,16,22,18,6] - [2,6,16,22,18,27] - [2,6,16,18,22,27] 

Final sıralamamız böyle olur ---> [2,6,16,18,22,27]

n(n+1)/2 ---> o(n^2)

[2,6,16,18,22,27] ---> 18 sayısı burada ortada olduğu için Avarage case yapısına girer

Average case: Aradığımız sayının ortada olması

<h2>Soru 2</h2>

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

<h3>Cevap 2</h3>

Adım 1 ---> [2,3,5,8,7,9,4,15,6] - ilk adımda 2 en küçük değer olduğu için başa gelir ve 7 de 2 nin yerine gider

Adım 2 ---> [2,3,4,8,7,9,5,15,6] - ikinci adımda ise 4 ile 5 yer değiştirir 3 rakamı 2 den sonra olan en küçük değer olduğu için yeri sabittir

Adım 3 ---> [2,3,4,5,7,9,8,15,6] - üçüncü adımda 5 ve 8 yer değiştirir

Adım 4 ---> [2,3,4,5,6,9,8,15,7] - dördüncü adımda 7 ve 6 yer değiştirir
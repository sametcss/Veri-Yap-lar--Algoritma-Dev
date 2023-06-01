<h1>Binary Search Tree Projesi</h1>

<h2>Soru 1</h2>

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

<h3>Cevap 1</h3>

burada rootumuz 6 yı alarak ağacımızı oluşturalım

            6            ---> Root düğümümüz 6
          /   \
         3     8          
        / \   / \
       1   5 7   9
      / \   /
     0   2 4

kendisinden büyük olan değerler sağ düğüme küçük olanlar ise sol düğümden bulunur.

'3' değeri '6' dan küçük olduğu için sol düğüme girilmiştir
'8' değeri '6' dan büyük olduğu için sağ düğüme girilmiştir
geri kalan değerlerde aynı durum geçerlidir. '7' değeri '8' den küçük olduğu için 8 'in sol düğümüne yazılmıştır.
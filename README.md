[16, 21, 11, 8, 12, 22] -> Merge Sort:

1.Adım: Diziyi ikiye bölerek alt dizilere ayırıyoruz. Sol taraf [16, 21, 11] ve sağ taraf [8, 12, 22] olacak şekilde ayırıyoruz.

2.Adım: Sol tarafa ait alt dizi, yine ikiye bölerek [16], [21, 11] şeklinde ikiye ayrılıyor.

3.Adım: Sol tarafa ait alt dizi, yine ikiye bölerek [16], [21, 11] şeklinde ikiye ayrılıyor.

4.Adım: Sağ tarafa ait alt dizi, yine ikiye bölerek [8], [12, 22] şeklinde ikiye ayrılıyor.

5.Adım: Sol taraftaki en küçük alt dizi olan [16] ve [11, 21] birleştirilerek [11, 16, 21] oluşturuluyor.

6.Adım: Sağ taraftaki alt dizi olan [8] ve [12, 22] birleştirilerek [8, 12, 22] oluşturuluyor.

7.Adım: Sol taraf olan [11, 16, 21] ve sağ taraf olan [8, 12, 22] birleştirilerek [8, 11, 12, 16, 21, 22] oluşturuluyor.
Bu şekilde Merge Sort tamamlanır.

Big-O gösterimi: O(n log n)

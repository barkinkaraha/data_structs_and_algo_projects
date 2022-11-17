[22,27,16,2,18,6] -> Insertion Sort

--  --  --  --  --  --  --  --

Yukarıdaki dizinin aşamalarının sort türlerine göre gösterilişleri :

1) [22,27,16,2,18,6] => n # n eleman taranıp aralarından en küçük olanın en soldaki elemanla yeri değiştirilir.

2) [2,27,16,22,18,6] => (n-1) # Bu sefer en soldaki eleman dışarıda bırakılarak kalan (n-1) eleman arasından en küçük olanının en solda olanlarıyla yeri değiştirilir.
 
3) [2,6,16,22,18,27] => (n-2) # İşlem bu sefer en soldaki 2 eleman dışarıda bırakılacak şekilde yapılır fakat kalan (n-2) elemandan en kücük olanı zaten en solda olduğu için herhangi bir yer değişikliği yapılmaz.

4) [2,6,16,22,18,27] => (n-3) # Kalan (n-3) sayıdaki eleman arasından en küçük olanıyla aralarından en soldakinin yeri değiştirilir.

5) [2,6,16,18,22,27] => (n-4) # Önceki adımlardaki gibi, bu sefer kalan (n-4) eleman kendi aralarında kıyaslanır fakat en küçük eleman zaten en solda olduğu için herhangi bir yer değişikliği yapılmaz.

6) [2,6,16,18,22,27] => 1 # İşlemimiz tamamlanmıştır.

--  --  --  --  --  --  --  --

Big O gösterilişi :

(Average Case) O(n²)

--  --  --  --  --  --  --  --

Time Complexity: Dizi sıralandıktan sonra 18 sayısı Average Case'e girer. Açıklamasıysa 4.adımda kalan 3 değerden en küçükleri olan (aradığımız değer) 18 ortadaki eleman olduğu için Average Case kapsamına giriyor.

--  --  --  --  --  --  --  --

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1) [2,3,5,8,7,9,4,15,6] # 2 ve 7 yer değiştirdi.

2) [2,3,4,8,7,9,5,15,6] # 4 ve 5 yer değiştirdi.

3) [2,3,4,5,7,9,8,15,6] # 5 ve 8 yer değiştirdi.

4) [2,3,4,5,6,9,8,15,7] # 6 ve 7 yer değiştirdi.
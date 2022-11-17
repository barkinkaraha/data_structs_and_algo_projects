[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları :

--  --  --  --  --  --  --  --

1) Referans node'umuz dizinin ilk elemanı olan 7 olarak belirlenip elemanlar sırayla kendilerinden önceki node'larla kıyaslanarak küçük olan elemanlar sol alt dallara, büyük elemanlar sağ alt dallara dağıtılır. Bu şekilde Binary-Search-Tree'miz oluşturulmuş olur.

--  --  --  --  --  --  --  --

# Örnek olarak 7'den sonraki eleman olan 5, 7'den küçük olduğu için 7'nin sol alt dalına yerleştirilir. Aynı mantık izlenerek bir sonraki eleman olan 1 7'den ve 5'ten küçük olduğu için 5'in sol altına yerleştirilirken 4. eleman olan 8 7'nin sağ alt dalına yerleştirilir. Netleştirmek için son bir örnek olarak da 5. eleman olan 3, 7 ve 5'ten küçük olduğundan bu ikisinin sol alt dallarından ilerletilip 1'den büyük olduğu için 1'in sağ alt dalına yerleştiriliyor.

--  --  --  --  --  --  --  --

             7    
         /       \ 
        5         8
      /   \        \
     1     6        9
   /   \       
  0      3       
      /    \
     2      4

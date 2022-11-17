[16,21,11,8,12,22] -> Merge Sort

--  --  --  --  --  --  --  --

Yukarıda verilen dizinin sort türüne göre aşamaları :

1)                [16,21,11,8,12,22]               
                                                 
2)              [16,21,11]    [8,12,22]            
                                                 
3)      [16,21]    [11]        [8]    [12,22]     
                                                  
4)    [16]  [21]    [11]          [8]    [12]  [22]
                                                 
5)      [16,21]    [11]        [8]    [12,22]    
                                                 
6)              [11,16,21]    [8,12,22]           

7)                [8,11,12,16,21,22]

# 1. adımdan 4. adıma kadar dizin her bir eleman yalnız kalıncaya kadar ikiye ayırılır. Sonraki adımlarda ise soldan başlanarak karşılıklı elemanlar kıyaslanıp küçük olan daha sola konulacak şekilde dizinler birleştirilerek sıralama sağlanmış olur.

--  --  --  --  --  --  --  --

Big O gösterimi :

O(nlogn)

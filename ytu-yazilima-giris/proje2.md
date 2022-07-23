proje2.md
             [16,21,11,8,12,22] diziyi ikiye ayırıyoruz
     [16,21,11]                [8,12,22] tek eleman olana kadar diziyi bölüyor
   [16]   [21,11]           [8]   [12,22] tekrar ayırma işlemi yapıyoruz
   [16]  [21]  [11]         [8]  [12]  [22]   tüm elemanlar tek tek ayırıyoruz.
   [16]   [11,21]             [8]   [12,22] 
    [11,16,21]                 [8,12,22]
    [8,11,12,16,21,22]
    Big O bulmak için gerekli formül O(n*logn)
    dizimiz 6 elemanlı oldugu için n yerine 6 yazacagız 
    O(6*log6)'dır.
1 soru
[22,27,16,2,18,6] diziyi insertion sort yöntemiyle çözmek için önce küçükten büyüge sıralamamız lazım
dizi içindeki en küçük elemanı yani 2 ile dizinin ilk elemanı olan 22 ile yerini degiştirmeliyiz
[2,27,16,22,18,6] sonraki en küçük eleman yani 6 ile dizinin ikinci elemanının yerini degiştiriyoruz
[2,6,16,22,18,27] sonraki en küçük eleman 16 oldugu için yeri degişmiyor
[2,6,16,18,22,27] sonraki en küçük eleman 18 oldugundan 22 ile yer degiştiriyor
dizimiz artık küçükten büyüge sıralanmıştır.
2 soru
Big O gösterimi n elemanlı bir dizi için hesaplamak istersek sırasıyla n ,n-1,n-2, sonuncu elemana kadar yani 1 olana kadar bu işlem devam ettigi için 1 den n kadar sayıların toplamı formülünden
 n*(n+1)\2 elde edilir ama burada dominant yani büyük katsayıyı alırız o zaman insertion sort için Big O (n^2) esittir 
 bizim dizimiz 6 elemanlı oldugu için Big O (6^2)'dir
4 soru
[2,6,16,18,22,27]  dizimizin sıralanmış hali budur aradıgımız eleman 18 ortada oldugundan Average casedir.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazmamız istenmiş
1 adım [2,3,5,8,7,9,4,15,6] 2 ve 7 nin yerini degiştirdik
2 adım [2,3,5,8,7,9,4,15,6] 2'den sonraki en küçük sayı 3 oldugu için yer degişimi olmaz 
3 adım [2,3,4,8,7,9,5,15,6] sonraki en küçük sayı 4 ile 5 yeri degişir
4 adım [2,3,4,5,7,9,8,15,6] 5 ve 8 yerini degiştirdik


Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.



************************************************************************************************************************************

 # ÇÖZÜMLER

 Adım 1: [22,27,16,2,18,6] --> (22, 27'den küçüktür. Aydnı kalır.)
 Adım 2: [16,22,27,2,18,6] --> (16, 22'den küçüktür soluna geçer.)
 Adım 3: [2,16,22,27,18,6] --> (2, 16'dan küçüktür soluna geçer.)
 Adım 4: [2,16,18,22,27,6] --> (18, 22'den küçük soluna geçer. 16'dan büyük sağına geçer.)
 Adım 5: [2,6,16,18,22,27] --> (6, 16'dan küçük soluna geçer. 2'den büyük sağına geçer ve sıralama işlemi tamamlanır.)

 Big-O gösterimi: O(n^2)'dir.

 18 sayısı ortada olduğu için Average case: Aradığımız sayının ortada olması kapsamına girer.




Adım 1: [2,3,5,8,7,9,4,15,6] --> (En küçük eleman olan 2 bulunup, 7 ile yer değiştirir.)
Adım 2: [2,3,5,8,7,9,4,15,6] --> (İkinci en küçük eleman olan 3 olması gereken yerde.)
Adım 3: [2,3,4,8,7,9,5,15,6] --> (Üçüncü en küçük eleman olan 4 bulunup, 5 ile yer değiştirir.)
Adım 4: [2,3,4,5,7,9,8,15,6] --> (Dördüncü en küçük eleman olan 5 bulunup, 8 ile yer değiştirir.)
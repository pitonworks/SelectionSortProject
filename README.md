Dizi: [22,27,16,2,18,6]

Insertion Sort, sıralı bir alt dizi oluşturarak ve her yeni elemanı bu sıralı alt diziye uygun yere yerleştirerek çalışır. İşte adım adım işlemi:

Başlangıç: [22,27,16,2,18,6]

İlk eleman olan 22, kendi başına sıralı bir alt dizi olarak kabul edilir.
İkinci Adım: [22,27,16,2,18,6]

27, 22'den büyük olduğu için, sıralı alt diziye eklenir. [22, 27]
Üçüncü Adım: [16,22,27,2,18,6]

16, sıralı alt dizinin başına yerleştirilir çünkü 16 < 22 ve 16 < 27. Sonuç: [16,22,27]
Dördüncü Adım: [2,16,22,27,18,6]

2, sıralı alt dizinin başına yerleştirilir. Sonuç: [2,16,22,27]
Beşinci Adım: [2,16,18,22,27,6]

18, sıralı alt diziye doğru yerleştirilir. Sonuç: [2,16,18,22,27]
Altıncı Adım: [2,6,16,18,22,27]

6, sıralı alt diziye yerleştirilir. Sonuç: [2,6,16,18,22,27]
Big-O Gösterimi:

Worst Case (En Kötü Durum): O(n^2), çünkü her yeni elemanı sıralı alt dizide uygun yere yerleştirmek için her elemanı karşılaştırmak gerekebilir.
Best Case (En İyi Durum): O(n), çünkü dizi zaten sıralıysa, her elemanı sadece bir kez kontrol etmek yeterlidir.
Average Case (Ortalama Durum): O(n^2), genellikle her yeni elemanı sıralı alt diziye yerleştirmek için ortalama n/2 karşılaştırma gerektirir.
Time Complexity için 18 Sayısının Durumu:

18 sayısı, dizinin sıralandıktan sonra ortasında bir yerde olacak ve dizinin ortasında bir eleman olarak kabul edilecektir. Bu nedenle, "Average case: Aradığımız sayının ortada olması" kapsamına girer.
Selection Sort İlk 4 Adım
Dizi: [7,3,5,8,2,9,4,15,6]

Selection Sort, her adımda dizinin geri kalanında en küçük elemanı bulur ve bu elemanı sıralı alt dizinin sonuna ekler.

İlk Adım:

Dizideki en küçük eleman 2'dir.
2, dizinin ilk elemanı olan 7 ile yer değiştirir.
Sonuç: [2,3,5,8,7,9,4,15,6]
İkinci Adım:

Geriye kalan dizide (3,5,8,7,9,4,15,6) en küçük eleman 3'tür.
3 zaten sıralı pozisyonda, dolayısıyla dizi değişmez.
Sonuç: [2,3,5,8,7,9,4,15,6]
Üçüncü Adım:

Geriye kalan dizide (5,8,7,9,4,15,6) en küçük eleman 4'tür.
4, 5 ile yer değiştirir.
Sonuç: [2,3,4,8,7,9,5,15,6]
Dördüncü Adım:

Geriye kalan dizide (8,7,9,5,15,6) en küçük eleman 5'tir.
5, 8 ile yer değiştirir.
Sonuç: [2,3,4,5,7,9,8,15,6]
Bu adımlar Selection Sort'un ilk dört aşamasını gösterir.

Proje 1 (Insertion Sort)

Insertion Sort Aşamaları:

[22,27,16,2,18,6] dizisinin insertion sort yöntemi ile aşamaları şu şekildedir,

İlk aşamada Insertion sort yönteminde dizinin en küçük elemanı ilk eleman olarak atanır.
Yani [6|22,27,16,2,18] şeklinde bir başlangıç yapılır.

Daha sonrasında ise sıralanmamış kısımdaki elemanlar kontrol edilir ve en küçük eleman sıralanmış elemanlar içerisindeki en son pozisyona atanır. Yani sayı dizisi, [6,16|22,27,2,18] şeklinde düzenlenir.

Bu işlem sıralanmamış eleman kalmayana kadar devam eder.

Big-Oh Gösterimi

Big-Oh gösterimi worst case senoryaya bakılarak yapılır. Örnek kapsamında Worst Case senaryo dizinin tersten sıralanmış olarak verilmesi durumudur. Yani Worst Case durumunda dizimiz [27,22,18,16,6,2] şeklinde verilmiş olurdu. Bu durumda en küçük sayı en başa getirilene kadar işlem yapılacaktır.

Dolayısıyla (n.(n+1))/2 = O(n^2)

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı:

1.adım: [2|3,5,8,7,9,4,15,6], sıralanmamış dizinde 2 en küçük elaman olduğu için en başa gelir.

2.adım: [2,3|5,8,7,9,4,15,6], sıralanmamış dizinde 3 en küçük eleman olduğu için değiştirmeye gerek yoktur.

3.adım: [2,3,4|5,8,7,9,15,6], sıralanmamış dizinde 4 en küçük eleman olduğu için 4 sıralanmış dizinde en sola gelir.

4.adım: [2,3,4,5|8,7,9,15,6], sıralanmamış dizinde 5 en küçük eleman olduğu için değiştirmeye gerek yoktur.
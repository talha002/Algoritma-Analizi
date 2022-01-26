Proje 2 (Merge Sort)

Merge Sort Aşamaları:

[16,21,11,8,12,22] dizisinin Merge sort yöntemi ile aşamaları şu şekildedir,

İlk aşamada verilen dizi ortadan iki ayrılmaya çalışılır. Örneğimizdeki dizi çift sayıda eleman içerdiği için [16,21,11]   -   [8,12,22] şeklinde bir ayrım yapılır.

İknci aşamada ikiye ayrılmış elemanlar bir kez daha ayrıma tabi tutulur. Bu sefer elimizdeki sayı dizilerin elemen sayısı tek sayıda olduğu için ayrım +1 farkla yapılır. Yani, [16]   -   [21,11] ve [8]   -   [12,22] şeklinde bir ayrım yapılır.

Üçüncü aşamada artık sayı dizilerinden en az biri ikiye ayrılamayacak hale geldiği için daha fazla ayrım yapılmaz ve bunun yerine sayı dizilerin kendi içerilerindeki sıralamarı yapılır. Yani sayı dizileri [16]   -   [11,21] ve [8]   -   [12,22] şeklinde düzenlenir.

Dördüncü aşamada ise sayı dizileri aralarında karşılaştırmalar yapılarak ayrılmış diziler birleştirilir. Yani diziler [11,16,21] ve [8,12,22] şeklinde düzenlenir.

Beşinci aşamada birleştirem işlemi aynı şekilde devam eder. Yani diziler [8,11,12,16,21,22] şeklinde düzenlenir ve birleştirlecek biri dizi kalmadığı için ilk başda sıralanmamış dizinin sıralanmış halini elde etmiş oluruz.

Big-O gösterimi:

Her adımda adım sayısı yarıya düştüğü için 2^x = n den logn elde edilir. Bu işlem n kez gerçekleşeceği için de O (nlogn) şeklinde gösterim yapılır.
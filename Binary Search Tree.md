Proje 3 (Binary Search Tree Projesi)

Binary Search Tree aşamaları:

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary Search Tree yöntemi ile aşamaları şu şekildedir,

Birinci aşamada kökü 5 seçtik. 

İkinci aşamada 7, kökten büyük olduğu için kökün sağına geçer. 

Üçüncü aşamada 1, kökten küçük olduğu için kökün soluna geçer. 

Dördüncü aşamada 8, kökten ve 7'den büyük olduğu için 7'nin sağına geçer. 

Beşinci aşamada 3 kökten küçük olduğu için ve 1'den büyük olduğu için 1'in sağına geçer. 

Altıncı aşamada 6, kökten büyük olduğu için ve 7'den küçük olduğu için 7'nin soluna geçer. 

Yedinci aşamada 0, kökten ve 1'den küçük olduğu için 1'in soluna geçer. 

Sekizinci aşamada 9, kökten büyük olduğu için, 7'den ve 8'den büyük olduğu için 8'in sağına geçer. 

Dokuzuncu aşamada 4, kökten, 1'den ve 3'ten büyük olduğu için 3'ün sağına geçer. 

Son aşamada da 2, kökten ve 1'den büyük, 3'ten küçük olduğu için 3'ün soluna geçer.

Günün sonunda aşağıdaki ağacı elde etmiş oluruz:

                    5
                  /   \
                1       7
               / \     / \
              0   3   6   8
                 / \       \
                2   4       9 
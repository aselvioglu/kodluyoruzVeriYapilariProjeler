# Proje 1

Soru: [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.

.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Insertion Sort : [22,27,16,2,18,6]
| Aşama | Dizi |
|:---: | :------: |
|1. İterasyon| 22, 27, 16, 2, 18,6|
|2. İterasyon| 22, 16, 27, 2, 18,6 |
|2. İterasyon | 22, 16, 2, 27, 18, 6 |
|2. İterasyon | 22, 16, 2, 18, 27, 6 |
|2. İterasyon | 22, 16, 2, 18, 6, 27 |
|3. İterasyon | 16, 22, 2, 18, 6, 27 |
|3. İterasyon | 16, 2, 22, 18, 6, 27 |
|3. İterasyon | 16, 2, 18, 22, 6, 27 |
|3. İterasyon | 16, 2, 18, 6, 22, 27 |
|4. İterasyon | 2, 16, 18, 6, 22, 27 |
|5. İterasyon | 2, 16, 6, 18, 22, 27 |
|6. İterasyon | 2, 6, 16, 18, 22, 27 |

O(n^2): worst case
18 için average case, dizinin ortasında olduğu için


## Selection Sort: [7,3,5,8,2,9,4,15,6] 
| Aşama | Dizi |
|:---: | :------: |
|1. İterasyon| 2,3,5,8,7,9,4,15,6|
|2. İterasyon| 2,3,4,8,7,9,5,15,6|
|3. İterasyon| 2,3,4,5,7,9,8,15,6|
|4. İterasyon| 2,3,4,5,6,9,8,15,7|
|5. İterasyon| 2,3,4,5,6,7,8,15,9|
|6. İterasyon| 2,3,4,5,6,7,8,9,15|


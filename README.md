# insertion-
## [22,27,16,2,18,6] -> Insertion Sort <br>
```
[22,27,16,2,18,6] (27>22 oldugu için işlem gerçekleştirilmez) <br>
[16,22,27,2,18,6] (16 küçük oldugu için önce 27 sonra 22 ile yer değiştirerek başa geçer ) <br>
[2,16,22,27,18,6] (2'de 3 hamle ile başa geçer) <br>
[2,16,18,22,27,6] (18, 2 hamle ile sola kaydırılarak, 16<18 olduğu için sola kaydırma işlemi sona erdirilir) <br>
[2,6,16,18,22,27] (bir önceki gibi 6'da öncekilerden küçük olmayacak konuma gelene kadar sola kaydırılır) <br>
```
>> Insertion Sort Worstcase: [n*(n+1)]/2 -> Big O(n²)

## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? <br>

>> Insertion sıralaması sonucunda '18' değeri dizinin ortasında bulunacağı için time complexity'si 'Average Case' olarak değerlendirilir. <br>

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6] (7 ile devamındaki en küçük değerin (2) yeri değiştirilir) <br>
2. [2,3,5,8,7,9,4,15,6] (3'den itibaren daha küçük bir sayı bulunmadığından dolayı hiç bir işlem gerçekleştirilmez) <br>
3. [2,3,4,8,7,9,5,15,6] (5 ile devamındaki en küçük değerin (4) yeri değiştirilir) <br>
4. [2,3,4,5,7,9,8,15,6] (8 ile devamındaki en küçük değerin (5) yeri değiştirilir) <br>
>> 4. adımında ardından dizi elemanları bu şekilde sıralanır -> [2,3,4,5,7,9,8,15,6]

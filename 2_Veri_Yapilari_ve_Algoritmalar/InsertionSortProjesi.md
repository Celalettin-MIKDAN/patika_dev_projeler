# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

- 1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- 2-Big-O gösterimini yazınız.
- 3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1. Insertion Sort Aşamaları
```
- [22,27,16,2,18,6] 
- [2,27,16,22,18,6] 
- [2,6,16,22,18,27] 
- [2,6,16,18,22,27] 
```

## 2. Big-O Gösterimi
```
Big-O(n²)
```

## 3. Time Complexity
Best case: Aradığımız sayının dizinin içerisinde sıralı küçükten büyüğe sıralı olması durumu.
```Best case : O(n)```

Average case: Aradığımız sayının ortada olması durumu.
```Average case : O(n²)```

Worst case: Aradığımız sayının her aşamada en sonda olması durumu.
```Worst case : O(n²)```

## 4. 18 sayısı 
```18 sayısı dizinin ortasında olduğundan Average case kapsamına girer```

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
```
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
```

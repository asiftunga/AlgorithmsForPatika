# Patika.dev Veri Yapilari ve Algoritmalar
Bu repo patika.dev **veri yapilari ve algoritmalar** dersinin odevleri icin olusturulmustur
___

## Insertion Sort

[22,27,16,2,18,6] 

_**Yukarı verilen dizinin insortion sort türüne göre aşamalarını yazınız.**_

```
[22, 27, 16, 2, 18, 6]
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27]
```
_**Big-O gösterimini yazınız.**_
```
Her döngü için, karşılaştırma ve yer değiştirme işlemleri için O(n) zaman gerekir 
her eleman icin bu islem tekrarlanacagindan dolayi
O(n) x O(n) = O(n^2) zaman gereklidir. 
```

_**Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?**_
```
18 sayısı ortada olduğu için avarage case kapsamına girer.
```

## Selection Sort

[7,3,5,8,2,9,4,15,6]

_**Yukaridaki dizinin Selection Sort'a göre ilk 4 adımını yazınız.**_

```
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 6, 9, 8, 15, 7]
```
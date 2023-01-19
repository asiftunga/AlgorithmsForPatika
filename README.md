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
___

## Selection Sort

[7,3,5,8,2,9,4,15,6]

_**Yukaridaki dizinin Selection Sort'a göre ilk 4 adımını yazınız.**_

```
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 6, 9, 8, 15, 7]
```
___

## Merge Sort

[16,21,11,8,12,22]

_**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**_

```
[16, 21, 11, 8, 12, 22]
[16, 21, 11], [8, 12, 22]
[16], [21, 11], [8], [12, 22]
[16], [21], [11], [8], [12], [22]
[21, 16], [11, 21], [8, 12], [22, 12]
[21, 16, 11], [8, 12, 22]
[8, 12, 21, 16, 11, 22]
[8, 12, 11, 16, 21, 22]
[8, 11, 12, 16, 21, 22]
[8, 11, 12, 16, 21, 22]
```

_**Big-O gösterimini yazınız.**_

```
2^x=n
x=log(n) 
n*log(n)
O(nlogn)
```
___

## Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

_**dizisinin Binary-Search-Tree aşamalarını yazınız.**_
_**Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.**_

```
Root'u 7 olarak seciyoruz
Sonrasinda 5 sayisini aliyoruz ve 7 den kucuk oldugu icin 7 nin soluna yerlestiriyoruz
sonraki elemanimiz 1, 7 den ve 5 den kucuk oldugu icin 5 in sol tarafina eklenir
siradaki eleman 8, 7 den buyuk oldugu icin 7 nin sag tarafina eklenir
3 ise 7 ve 5 den küçük 1den büyük olduğu için 1 in sağına eklenir
6 7den küçük, 5ten büyük oldugu icin 5in sağına eklenir
0 7den küçük, 5ten küçük, 1 den küçük olduğundan 1in soluna eklenir
9 7 den ve 8 den buyuk oldugu icin 8 in sagina eklenir
4 7den küçük, 5ten küçük, 1den büyük, 3ten büyük olduğu için 3 un sagina eklenir
2 7 ve 5 den kucuk, 1 den büyük, 3ten küçük oldugundan dolayi 3 un soluna eklenir

              7  
            /   \
           5     8      
          / \     \
         1   6     9
        / \    
       0   3 
          / \
         2   4
```
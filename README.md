# Veri Yapilari ve Algoritmalar Kursu Bitirme Projesi

## Insertion Sort Projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## CEVAPLAR

1. Insertion Sort Aşamaları?

* Adim 1: listedeki en kücük sayiya bakiyoruz. "2". Bu sayi ile ilk sayinin yerini degistiriyoruz. [2,27,16,22,18,6]
* Adim 2: Listedeki en kücük ikinci sayiya bakiyoruz. "6". Bu sayi ile ikinci sayinin yerini degistiriyoruz. [2,6,16,22,18,27]
* Adim 3: Listedeki en kücük ücüncü sayiya bakiyoruz. "16". Bu sayi zaten ücüncü sayi oldugu icin yerini degistirmiyoruz. [2,6,16,22,18,27]
* Adim 4: Listedeki en kücük dördüncü sayiya bakiyoruz. "18". Bu sayi ile dördüncü sayinin yerini degistiriyoruz. [2,6,16,18,22,27]
* Adim 5: Listedeki en kücük besinci sayiya bakiyoruz. "22". Bu sayi zaten besinci sayi oldugu icin yerini degistirmiyoruz. Bu da son asama oluyor. [2,6,16,18,22,27]

2. Big-O Gösterimi?

O(n^2)

3. Time Complexity?

- Worst case: Aradigimiz sayinin sonda olmasi,
- Average case: Aradigimiz sayinin ortada olmasi, 
- Best case: Aradigimiz sayinin dizinin en basinda olmasi

4. Dizi siralandiktan sonra 18 Sayisi hangi case kapsamina girer?

Dizinin son halinde "18" sayisi ortada oldugundan dolayi Average Case kapsamindadir: [2,6,16,18,22,27]

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız?

* [2,3,5,8,7,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]

[www.patika.dev](https://www.patika.dev/) 

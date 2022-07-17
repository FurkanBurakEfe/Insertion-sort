# Insertion-sort
Patika.dev Veri Yapıları ve Algoritmaları dersinin projesidir.

# 1- Insertion Sort aşamaları

[22,27,16,2,18,6]

[2|,27,16,22,18,6] -- n

[2,6|,16,22,18,27] -- n-1

[2,6,16|,22,18,27] -- n-2

[2,6,16,18|,22,27] -- n-3

[2,6,16,18,22|,27] -- n-4

[2,6,16,18,22,27] -- n-5
# 2- Big-O Notation Gösterimi
Worst Case : O(n^2)

Avarage Case : O(n^2)

Best Case : O(n)

# 3- Time Complexity
Best Case : [2,27,16,22,18,6]

Average case : [22,27,16,2,18,6]

Worst Case : [22,27,16,6,18,2]

# 4- 18 Sayısı hangi Case?
Dizi sıralanınca [2,6,16,18,22,27] bu sıraya gelir. Bu durumda 18 sayısı ortadaki iki sayıdan biridir. 18 sayısını orta olarak kabul edersek, 18 sayısının durumu Average Case kapsamına girer.
# 5- [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı
[2|,3,5,8,7,9,4,15,6] -- 1.adım
[2,3|,5,8,7,9,4,15,6] -- 2.adım
[2,3,4|,8,7,9,5,15,6] -- 3.adım
[2,3,4,5|,7,9,8,15,6] -- 4.adım

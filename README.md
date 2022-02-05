# Insertion-Sort
Dizide insertion sort kullanımı :<br>
Dizideki en küçük elemanı bul ve dizinin başındaki elemanla yerini değiştir. Dizi küçükten büyüğe sıralana kadar bu işlemi devam ettir.<br>

[22,27,16,2,18,6] dizisi için,<br>
[2,27,16,22,18,6]<br>
[2,6,16,22,18,27]<br>
[2,6,16,18,22,27]<br>
O(n^2) , 18 sayısı dizinin ortasında olduğu için time complexity si average casedir.<br>

[7,3,5,8,2,9,4,15,6] dizisi için, <br>
[2,3,5,8,7,9,4,15,6]<br>
[2,3,4,8,7,9,5,15,6]<br>
[2,3,4,5,7,9,8,15,6]<br>
[2,3,4,5,6,9,8,15,7]<br>
[2,3,4,5,6,7,8,15,9]<br>
[2,3,4,5,6,7,8,9,15]<br>
O(n^2) , 15 sayısını baz alalım.Dizinin sonunda olduğu için time complexity si worst casedir.

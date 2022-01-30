# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. Root = 6
2. 6'dan büyük olan sayılar 6'nın sağına, küçük olanlar ise soluna yazılır.
3. 7 > 6 sağa yazılacak. 
4. 5 < 6 sola yazılacak .
5. 1 < 6 sola yazılacak . 5'in de solunda olacaktır.
6. 8 > 6 sağa yazılacak. 7'nin de sağında olacak.
7. 3 < 6 sola yazılacak. 3 < 5 sola yazılacak.  3 >1 sağa yazılacak
8. 0 < 6 sola yazılacak. 0 < 1 sola . 
9. 9 > 6 sağa yazılacak. 9 > 8 sağa.
10. 4 < 6 sola yazılacak. 4 < 5 sola yazılacak. 4 > 1 sağa yazılacak. 4 > 3 sağa yazılacak.
11. 2 < 6 sola yazılacak. 2 < 5 sola yazılacak. 2 < 3 sola yazılacak 


![resim](https://user-images.githubusercontent.com/63648396/151709316-019d3c50-df8c-4049-a67b-9da6ea7b975b.png)

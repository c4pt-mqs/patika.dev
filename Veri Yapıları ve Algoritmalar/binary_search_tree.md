**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız:

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

**root = 5** olarak kabul edelim;
1)  5 > 1 => 1, 5'in soluna <br>
2)  5 < 7 => 7, 5'in sağına <br>
3)  8 > 7 ve 5 => 8, 7'nin sağına <br>
4)  5 > 3, 1 < 3 => 3, 1'in sağına <br>
5)  5 < 6 => 7, 7'in soluna <br>
6)  5 > 0, 7 > 0 => 0, 1'in soluna <br>
7)  5 < 9, 8 < 9 => 9, 8'in sağına <br>
8)  5 > 4, 1 < 4 , 3 < 4 => 4, 3'ün sağına <br>
9)  5 > 2, 1 < 2 , 3 < 2 => 2, 3'ün soluna yazılır.
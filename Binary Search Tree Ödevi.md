### Binary Search Tree Ödevi

---

[Patika](https://app.patika.dev/) | [Ödev Linki](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)| [Benim Patikam](https://app.patika.dev/suna)

---



**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

* İlk değer olan 7 root seçilir

  1. *5*

     `5<7; 7'nin soluna yaz`

  2. *1*

     `1<7,1<5; 5'in soluna yaz`

  3. *8*

     `8>7, 7'nin sağına yaz`

  4. *3*

     `3<7,3<5,3>1; 1'in sağına yaz`

  5. *6*

     `6<7,6>5;`

  6. *0*

     `0<7,0<5,0<1; 1'in soluna yaz`

  7. *9*

     `9>7,9>8; 8'in sağına yaz`

  8. *4*

     `4<7,4<5,4>1,4>3; 3'ün sağına yaz`

  9. *2*

     `2<7,2<5,2>1,2<3; 3'ün soluna yaz`



{ } { } { } { } { } { } { **7** } 

{ } { } { } { } { } { / } { } {\ }

{ } { } { } { } { **5** } { } { } { } {**8** }

{ } { } { } { / } { } { \ }{ } { } { } { \ } { }

{ } { } { **1** } { } { } { } { **6**  } { } { } { } { **9** }

{ } { / } { } {  \ } { } { } { } { }

{ **0** } { } { } { } { **3** } { } { } { }

{ } { } { } { } { / } { } { \ } { }

{ } { } { } { **2** } { } { } { } { **4** }

**Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

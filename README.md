# Insertion-Sort



[22, 27, 16, 2, 18, 6] 

 **Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.**

  1. aşama - >     [2, 27, 16, 22, 18, 6]
  2.  aşama ->     [2, 6, 16, 22, 18, 27]
  3.  aşama ->     [2, 6, 16, 18, 22, 27]      olmak üzere toplam 3 aşamada sort edebiliriz.



   **Big-O gösterimini yapınız.**

  n + (n-1) + (n-2)   ..... +1 = n(n+1) /2  - > katsayılar dikkate alınmaz ve dominant olan terim alınır. Dolayısıyla burdaki dominant terim **n^2** olacaktır. 

  Bu durumda Big-O gösterimi ise şu şekilde olacaktır : **O(n^2) **

   **Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**

  ***[2, 6, 16, 18, 22, 27]***  Dizisi sıralandıktan sonra, 18 sayısına (**n-3)**. adımda (3. adımda) ulaşıyoruz. Bu durumda dizi **Avarage case** kapsamına girecektir.


 **[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
3. [2,3,4,5,6,9,8,15,7]

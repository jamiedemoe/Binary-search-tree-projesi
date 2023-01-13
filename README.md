# Binary search tree projesi
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.







             5
            / \
           3   7
          / \  / \
         2  4  6   8
       /           \
      1              9
     /
    0
          
- 5 root olarak alındı.
- 3<5 olduğu için sol tarafa, 7>5 olduğu için sağ tarafa yazılır.
- 2<3 olduğu için sol tarafa, 4>3 olduğu için sağ tarafa yazılır.
- 1<2 ve 0<1 durumu olduğu için alt alta sol tarafa yazılır.

- 7>5 olduğu için sağ tarafa yazılır.
- 6<7 olduğu için sola, 8>7 olduğu için sağa yazılır.
- 9>8 olduğu için sağ tarafa yazılır.

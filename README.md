# Binary-Search-Tree-Projesi
https://app.patika.dev/zeyneepeergin

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
# ÇÖZÜM
[7,5,1,8,3,6,0,9,4,2] dizisi soldan okunmaya başlanır. Dizinin en başındaki sayı root olarak seçilir. Root'dan büyük sayılar sağına, root'dan küçük sayılar soluna yazılır.

Root: 7
              7
             /
            5
            
            
              7
             /
            5
           /
          1
         
        
             7
            / \
           5   8
          /
         1   
         
         
             7
            / \
           5   8
          /
         1
          \
           3
           
           
              7
             / \
            5   8
           / \
          1   6
           \
            3
            
            
              7
             / \
            5   8
           / \
          1   6
         / \
        0   3
        
        
              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
        
        
               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
              \
               4


               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
            / \
           2   4

# Proje-3 Binary Search Tree Projesi

[Patika.dev](https://www.patika.dev/tr)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree Aşamaları.

root = 7   

   5<7 old. için soluna eklendi.
     
   1<5 old. için soluna eklendi.
   
   8>7 old. için sağına eklendi.
  
   6>5 ve 6<7 old. için 5 in sağına eklendi.
  
 
          7
         / \ 
        5   8    3 1'in sağına eklendi. 0 ise soluna eklendi.
       / \      
      1   6
     / \ 
    0   3
    
          7
         / \ 
        5   8      9 8'in sağına eklendi.
       / \    \    
      1   6    9
     / \ 
    0   3
    
    
                                 7
                                /  \
                               5     8
                              / \      \
                             1   6       9    2 3'ün soluna 4 sağına eklendi.
                            /  \
                           0    3
                               /  \
                              2    4

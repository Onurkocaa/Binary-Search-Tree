# Binary-Search-Tree
Binary Search Tree Projesi

## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamaları

* İlk değer olan **7**, root seçilir.
*  **5**     
   5<7; 7'nin Soluna;
*  **1**     
   1<7, 1<5; 5'in Soluna;
*  **8**     
   8>7; 7'nin Sağına ;
*  **3**     
   3<7, 3<5, 3>1; 1'in Sağına;
*  **6**     
   6<7, 6>5; 5'in Sağına;
*  **0**     
   0<7, 0<5, 0<1; 1'in Soluna;
*  **9**     
   9>7, 9>8; 8in Sağına;
*  **4**     
   4<7, 4<5, 4>1, 4>3; 3'ün Sağına;
*  **2**     
   2<7, 2<5, 2>1, 2<3; 3'ün Soluna yazılır.


|  |  |  |  |  |  | 7|  |  |  |  |  
|--|--|- |- |- |- |- |- |- |- |- |
|  |  |  |  |  | /|  |\ |  |  |  | 
|  |  |  |  | 5|  |  |  |8 |  |  | 
|  |  |  | /|  |\ |  |  |  |\ |  | 
|  |  |1 |  |  |  |6 |  |  |  | 9|
|  | /|  |\ |  |  |  |  |  |  |  |
| 0|  |  |  | 3|  |  |  |  |  |  |
|  |  |  | /|  |\ |  |  |  |  |  |
|  |  | 2|  |  |  |4 |  |  |  |  |

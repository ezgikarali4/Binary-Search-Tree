# Binary-Search-Tree
Patika Dev Profile: https://app.patika.dev/ezgikarali4

### Project 3 ###
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### ANSWER ###
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizi içerisinde soldan sağa doğru sıra ile gidiyoruz. (We are going in order, from left to right in the array.)

#### 1. step
Root is 7.

         **7**
       
#### 2. step
5 is smaller than 7. So its on the left side of the root.

         7
       /   
     **5**     

#### 3. step
1 is smaller than 7 and 5.

         7
       /   
      5     
     /      
   **1**         
    
#### 4. step
8 is greater than 7. So its on the right side of the root.

         7
       /   \
      5   **8**
     /      
    1    
    
#### 5. step
3 is smaller than 7 and 5 but greater than 1.

         7
       /   \
      5     8
     /      
    1  
      \
     **3**
       
#### 6. step
6 is smaller than 7 but greater than 5.      
       
         7
       /   \
      5     8
     /  \    
    1  **6**
      \
       3
       
#### 7. step
0 is smaller than 7, 5 and 1.

         7
       /   \
      5     8
     / \     
    1   6       
   /  \
 **0** 3
  
#### 8. step
9 is greater than 7 and 8.

         7
       /   \
      5     8
     / \     \
    1   6   **9**  
   /  \
  0    3
  
#### 9. step
4 is smaller than 7 and 5 but greater than 3.

         7
       /   \
      5     8
     / \     \
    1   6     9  
   /  \
  0    3
         \
        **4**
          
#### Final step
And finally 2 is smaller than 7 and 5 but greater than 1. Also smaller than 3.

         7
       /   \
      5     8
     / \     \
    1   6     9  
   /  \
  0    3
      /  \
   **2**  4

    Data Structures & Algorithms - Project II
    
 
- **[16,21,11,8,12,22]** → Merge Sort
    - Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    - Big-O gösterimini yazınız.
    
    
- **[16,21,11,8,12,22]**  (n)

→ [16, 21, 11]  - [8, 12,  22]

→ [16]  [21, 11]  [8, 12]  [22]

→ [16] [21] [11] [8] [12] [22]

→ [16] [11, 21] [8, 12] [22]

→ [11, 16, 21]  [8, 12, 22]

→ **[8, 11, 12, 16, 21, 22]**

---

- O(nlogn)
    
    When we apply Merge Sort recursively, each recursive call divides the list into two halves. The number of recursive calls is log(n) where "n" is the number of elements in the input list. 
    In each recursive call, the Merge operation needs to merge all the sub-lists, and the cost of the merge operation is proportional to the length of the lists being merged.
    
    


          Data Structures & Algorithms - Project 1 

- **[22,27,16,2,18,6]** → Selection Sort
    - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    - Big-O gösterimini yazınız.
    - Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
        1. Average case: Aradığımız sayının ortada olması
        2. Worst case: Aradığımız sayının sonda olması
        3. Best case: Aradığımız sayının dizinin en başında olma

- **[22,27,16,2,18,6]** (n)
    
    → [2, 27, 16, 22, 18, 6] (n -1)
    
    → [2, 6, 16, 22, 18, 27] (n-2)
    
    → **[2, 6, 16, 18, 22, 27]** (n-3)
    

- **O(n^2)**
    
    In each iteration, selection sort finds the smallest element in the unsorted portion of the list, which requires n comparisons in the worst case scenario. Since the algorithm performs this operation n times the total number of comparisons is proportional to n^2.
    

- It’d be average case as the number 18 is in the middle after the sorting process

---

- **[7,3,5,8,2,9,4,15,6**] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[**7,3,5,8,2,9,4,15,6**] (n)

→ [2, 3, 5, 8, 7, 9, 4, 15, 6]

→ [2, 3, 4, 8, 7, 9, 5, 15, 6]

→ [2, 3, 4, 5, 7, 9, 8, 15, 6]

→ **[2, 3, 4, 5, 6, 9, 8, 15, 7]**

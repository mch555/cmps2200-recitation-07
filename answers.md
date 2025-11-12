# CMPS 2200 Recitation 10## Answers

**Name:**___Maeren Hay______________________
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
O(n+m)
- **4)**
n
- **5)**
O(n+m)
- **7)**
 
The work of reachable would change, because the new work would be O(n^2).

In the adjacenecy list representation, finding a nodes neighbors takes time that is proportional to its degree, so the work O(n+m).
With a adjacenct matrix of size n*n, finding all neighbors of a visited node requires us to iterate over an entire row, taking O(n) time.
Because the algo visits O(n) nodes, the total work increases to O(n*n)= O(n^2)

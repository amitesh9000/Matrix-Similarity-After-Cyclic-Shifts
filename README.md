You are given an m x n integer matrix mat and an integer k. The matrix rows are 0-indexed.

The following proccess happens k times:

Even-indexed rows (0, 2, 4, ...) are cyclically shifted to the left.
<img width="577" height="180" alt="image" src="https://github.com/user-attachments/assets/b2bea425-4a4b-427e-8da8-f4b0d415830d" />
Odd-indexed rows (1, 3, 5, ...) are cyclically shifted to the right.
<img width="565" height="180" alt="image" src="https://github.com/user-attachments/assets/57d74b41-c231-4f41-ab81-d3331085661c" />
Return true if the final modified matrix after k steps is identical to the original matrix, and false otherwise.

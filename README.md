# vector-class-implementation

created a vector class using c++

## Vector class Member functions Description:
- `elem_at_rank(int r)`: returns the element at rank r. The best and worst run time is O(1).
- `replace_at_rank(int r, const char& elem)`: replaces a element in the array at r with elem. The best run time O(1) and the worst run time is O(n).
- `insert_at_rank(int r, const char& elem)`: insert a new element at r with elem and resize the array by double. if the capacity of the array is full. The best and worst run time is O(nlogn).
- `remove_at_rank(int r)`: remove a element at r. The best and worst run time is O(1).
- `find_max_index(const My_vec& v,int size)`: find the max index of the largest element in the given size of array. The best run time is O(1) and worst run time is O(n).
- `sort_max(My_vec& vec)`: sort the array from smallest to largest using the function find_max_index. The best run time is O(n) and worst run time is O(n^2).


<b>Merge Sort</b></br>
This sorting algorithm breaks everything into arrays of one, and then compares two values to each other and puts them in their own sorted array. Then it compares two arrays, and makes a new sorted array from them, and onwards until completed.

Time complexity is O(n log(n)) because it takes n comparisons for log n number of steps. Space complexity is O(n) since we we are making new arrays as we go through.

Possible to use in place merge sort to avoid added space complexity.

<b>Merge Sort Quiz Answer:</b></br>
[21, 4, 1, 3, 9, 20, 25] (Original Array)<br>
[21, 1, 4, 3, 9, 20, 25] (1) <br>
[1, 4, 21, 3, 9, 20, 25] (2) <br>
[1, 3, 4, 9, 20, 21, 25] (3) <br>

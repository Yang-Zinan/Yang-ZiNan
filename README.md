- 👋 Hi, I’m Yang-Zinan From Hanzhong in Shaanxi, I am a student in Class 2 of Digital Media Technology, Grade 23.
- 👀 I’m interested in Digital Media Technology and I am eager to be a member of 414 Lab 
- 🌱  I hope to learn modeling,editing, PS and other professional skills in 414,and I also want to complete projects together with seniors to refine myself.

<!---
Yang-Zinan/Yang-Zinan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
![微信图片_20230930231754](https://github.com/Yang-Zinan/Yang-Zinan/assets/146302983/4e28d4e4-a512-4629-88a1-f40df3001a58)

1. Text description:-Starting from the first element of the array, compare the adjacent two elements in sequence.-If the previous element is greater than the latter element, swap their positions; Otherwise, it remains unchanged.-Continue to compare and exchange the next set of adjacent elements in the array until reaching the penultimate element of the array.-Repeat the above steps until no swapping operation occurs, i.e. the array is completely ordered.
2.  Flowchart:first round|5 | 8 | 3 | 9 | 2 | 4 | 7 | 1|
              Second round|5 | 3 | 8 | 2 | 4 | 7 | 1 | 9|
              Third round|3 | 5 | 2 | 4 | 7 | 1 | 8 | 9|
              Fourth round|3 | 2 | 4 | 5 | 1 | 7 | 8 | 9|
              Fifth round|2 | 3 | 4 | 1 | 5 | 7 | 8 | 9|
              Sixth round|2 | 3 | 1 | 4 | 5 | 7 | 8 | 9|
              Seventh round|2 | 1 | 3 | 4 | 5 | 7 | 8 | 9|
              Eighth round|1 | 2 | 3 | 4 | 5 | 7 | 8 | 9|
              After eight rounds of exchange, the array has been ordered
   3. Pseudocode Description
      function bubbleSort(array):
    n = array.length
    for i = 0 to n - 1:
        for j = 0 to n - i - 1:
            if array[j] > array[j + 1]:
                swap(array[j], array[j + 1])
    return array
The specific process of bubble sorting is to follow the steps described in the flowchart and pseudocode above, by continuously comparing and exchanging adjacent elements, gradually "bubble" the larger elements to the end of the array, thereby achieving an ascending arrangement of the array.

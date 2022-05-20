# arraystructures_algorithm
Project 1) [22,27,16,2,18,6] dizisinin insertion sorta göre aşamaları:
1st step - [2,27,16,22,18,6]
2nd step - [2,6,16,22,18,27]
3rd step - [2,6,16,18,22,27]

-Big O gösterimi : n+(n-1)+(n-2)+...+1 --> (n^2+n)/2 --> O(n^2)

Time complexity: -Worse case: n^2, -average case:n^2, best case: n.

18 is in the middle of the array then it is an average case.

[7,3,5,8,2,9,4,15,6] insertion sorta göre ilk dört adımı:
1st: [2,3,5,8,7,9,4,15,6]
2nd: [2,3,4,8,7,9,5,15,6]
3rd: [2,3,4,5,7,9,8,15,6]
4th: [2,3,4,5,6,9,8,15,7]

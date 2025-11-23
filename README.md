# algorithm
algorithm
Text-Segment- Count(A)
1. Use a table T[0..n]; T[0].count = 1; and T[i].count = 0 for i = 1, . . . ,n;
2.    for i = 1 to n do
3.            for j = 0 to i − 1 do
4.                     if IsWord(A[j + 1, i]) then
5.                           T[i].count += T[j].count;
6. return T[n].count; 

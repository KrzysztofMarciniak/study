# Big O Notation
Watch in this order.
if you watch all these videos and pay close attention you will learn it extremely quickly. I suggest taking a break after 2 videos.

* [Learn Big O notation in 6 minutes 📈](https://www.youtube.com/watch?v=XMUe3zFhM5c)
* [Big-O Notation - For Coding Interviews](https://www.youtube.com/watch?v=BgLTDT03QtU)
* [Big O Notation - Full Course (algorithm examples)](https://youtu.be/Mo4vesaut8g)
* [How to Prove or Disprove Big-O - Introduction to Computer Science (note: far more math focused)](https://youtu.be/7NC-iyZ7vpQ)
* [10. Understanding Program Efficiency, Part 1](https://youtu.be/o9nW0uBqvEo)

examples:
T(n) = T(n−1) + 1 → O(n)
T(n) = T(n/2) + 1 → O(log n)
T(n) = 2T(n/2) + n → O(n log n)

```c
for (i = 0; i < n; i++)
  for (j = i; j < n; j++)
    print(i + j);
```

* O(n²)


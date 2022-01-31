# Assignment2-Nagamalla
Its my second Assignment
# Yashaswi Nagamalla
###### Bahar
It's a restaurant which famous for **Biryani**. People from all over the world comes to this place to have **tasty and delicious food**.
***
# Description of Bahar restaurant
1. Kansas airport is the nearest airport to Bahar restaurant.
    1. From Kansas airport take a left and go straight for 2 miles.
    2. Then take a right and go straight, there you can find a small chruch.
    3. From there take a right and go straight for 0.5 miles.
    4. After that take a left and just beside McD you can find Bahar restaurant.
* Food Items
    * Chicken Biryani
    * Fish fry
    * Prawns Biryani
    * Chicken 65 

<https://github.com/yashaswi1996/Assignment2-Nagamalla/blob/main/Aboutme.md>

***
# Table
This table represents the sports which used to play regularly.

|   Sport  |   Place  | Price |
| -------- |  ------  | ----- |
|  Hockey  |  Outdoor | $500  |
| -------- |  ------- | ----- |
|  Cricket |  Outdoor | $1000 |
| -------- |  ------  | ----- |
|  Carrom  |  Indoor  | $200  |
| -------- |  ------- | ----- |
|   Ludo   |  Online  | $100  |

***
# Quotes
> "Integrity is doing the right thing, even when no one is watching" - *C.S. LEWIS*
>
> "We are all broken, that's how the light gets in" — *Ernest Hemingway*

***
# Code Fencing
> Fibonacci numbers are special kinds of numbers that form a special sequence. This sequence is one of the famous formulas in mathematics. You can find Fibonacci numbers in plant and animal structures. These numbers are also called nature's universal rule, and nature's secret code. Fibonacci numbers are a sequence of whole numbers arranged as 0, 1, 1, 2, 3, 5, 8, 13, 21, 34,...

<https://www.cuemath.com/algebra/fibonacci-numbers/>

```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}
```
<https://cp-algorithms.com/algebra/fibonacci-numbers.html>
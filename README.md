# assignment2-garugu
WA Assignment 2<br>
# Sai Shanmukh Garugu
###### Goa
Goa is widely known as India's party district, and is visited by thousands of **sun-seeking** tourists each year. It has a variety number of beaches covering the coastal length of about 99 miles. The **Dudhsagar Water Falls** is one of the famous water falls in India.

---

# Ordered List
1. Maryville to Kansas city Airport.
2. Take a flight to Delhi, India.
3. After getting off the flight, take a cab to nearest tourist agency.
4. Plan your trip and enjoy.

* Carry a camera to capture your memories.
* Bring a pair of trekking shoes.
* Sun glasses.
* Swimwear.
* Shorts and Cotton Trousers which Keeps you cool in hot sun.

---

# Recommended Foods/drinks
The below tables gives the information about the recommended foods/drinks in Hyderabad.
 
| Food/Drink | Location | Price |
|------------|--------|------|
|   Briyani  | Paradise   | $10 |
|   Haleem   | Pista House| $12 |
|   Dosa     | Ram ki bandi | $5 |
|   Oreo     | Cream Stome | $7 |

---

# Quotes

> Money is a tool, so I don't have to be. – Eddie Mumford
> 
> It's always darkest before you're blinded by the light. – josh stern

---

# Fibonacci Series

> The Fibonacci sequence is a set of numbers that starts with a one or a zero, followed by a one, and proceeds based on the rule that each number (called a Fibonacci number) is equal to the sum of the preceding two numbers.  To read more click on this link <https://whatis.techtarget.com/definition/Fibonacci-sequence>

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

For complete code click on the link <https://cp-algorithms.com/geometry/grahams-scan-convex-hull.html>


[About me](AboutMe.md)

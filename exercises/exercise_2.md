# Exercise 2 - control structures

In this exercise, you get to familiarize yourself with the control structures in python, namely

- if-statements
- for statements
- while statements

This exercise covers lectures 05 in the course.

## 0. Check sign (\*)

Ask the user to input a number and check if this number is **positive**, **negative** or **zero** and print it out.

## 1. Smallest (\*)

Ask the user to input two numbers and check which one is the smallest and print it out.

---

## 2. Medicine (\*)

The information in the following table is stated in a medicine package. Also it is stated that for children weight is more important than age.

<table >
<thead>
    <tr>
        <th></th>
        <th>Age</th>
        <th>Number of pills</th>
    </tr>
</thead>

<tbody>
  <tr>
    <td>Adults & adolescent <br>over 40 kg</td>
    <td>over 12 years</td>
    <td>1-2</td>
  </tr>

  <tr>
    <td>Children 26-40 kg</td>
    <td>7-12 years</td>
    <td>1/2-1</td>
  </tr>

  <tr>
    <td>Children 15-25 kg</td>
    <td>3-7 years</td>
    <td>1/2</td>
  </tr>
</tbody>
</table>

Let the user input age and weight, and then the program should give out a dose

## 3. Divisible (\*)

Let the user input a number. Check if the number is

<ol type="a">
  <li>even or odd</li>
  <li>is divisible by 5</li>
  <li>is divisble by 5 and odd</li>
</ol>

## 4. Luggage size (\*)

The maximum allowed luggage size for boarding an airplane is:

- weight: 8kg
- dimensions: 55x40x23cm (length x width x height)

Let the user input weight, length, width and height of the luggage. The program should check if the luggage is allowed or not.

## 5. Count numbers (\*)

Use a **for** statement to count from:

a) &nbsp; -10 to 10 with one increment (\*)

b) &nbsp; -10 to 10 with two increment (\*)

## 5. Arithmetic sum (\*)

Use a **while** statement to compute the following sums:

a) &nbsp; $\text{sum} = 1 + 2 + \ldots + 99+ 100$

b) &nbsp; $\text{sum} = 1 + 3 + 5 + \ldots + 97 + 99$

Repeat these using a **for** statement

## 6. Multiplication game (\*)

a) Create a multiplication game following this flow chart:

<img src="https://github.com/kokchun/assets/blob/main/python/Multiplication_game.png?raw=true">

## 7. Multiplication table (\*)

Use **for** statement(s) to:

&nbsp; a) &nbsp; print out the 6th multiplication table from 0 to 10 (\*)

&nbsp; b) &nbsp; let the user input the **table**, **start** and **end** of the table. (\*)

&nbsp; c) &nbsp; print out a full multiplication table from 0 to 10. (\*\*)

**Hint:** Use nested for-loops, which means a for-loop in a for-loop. To format the table nicely, use **f-string**:

```python
print(f"{number :4}", end = "")
```

output:

```
   0   0   0   0   0   0   0   0   0   0   0
   0   1   2   3   4   5   6   7   8   9  10
   0   2   4   6   8  10  12  14  16  18  20
   0   3   6   9  12  15  18  21  24  27  30
   0   4   8  12  16  20  24  28  32  36  40
   0   5  10  15  20  25  30  35  40  45  50
   0   6  12  18  24  30  36  42  48  54  60
   0   7  14  21  28  35  42  49  56  63  70
   0   8  16  24  32  40  48  56  64  72  80
   0   9  18  27  36  45  54  63  72  81  90
   0  10  20  30  40  50  60  70  80  90 100
```

## 8. Rice on chessboard (\*)

In first square of the chessboard there is one grain of rice, in the second square there is two grains, in the third square there is four grains and so on. How many grains are there in the whole chessboard when all squares are filled using this pattern?

<img src="https://github.com/kokchun/assets/blob/main/python/chessboard.png?raw=true">

## 9. Check convergence (\*\*)

Use a while statement to compute the following sums:

a) &nbsp; $\text{sum} = 1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$

b) &nbsp; $\text{sum} = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots + \frac{(-1)^n}{2n+1}$

Try different values on $n$ to see which value it converges to.

Repeat these using a **for** statement

## 10. Theory

a) When is it better to use while statement and when is it better to use for statement

b) What is the difference between = and == in Python?

c) Explain how an if-elif-else block works in Python. What happens if multiple conditions are true?

d) What does the continue statement do in a loop? How is it different from break?

e) Explain the meaning of truthy and falsy values and give a few example of both

f) Can you nest control structures in Python (e.g., a loop inside an if)? Give a brief example.

g) Every expression can be part of a statement, but not all statements are expressions. True or false?

## Glossary

Fill in this table either by copying this into your own markdown file or copy it into a spreadsheet if you feel that is easier to work with.

| terminology           | explanation |
| --------------------- | ----------- |
| control structures    |             |
| conditional statement |             |
| if                    |             |
| elif                  |             |
| else                  |             |
| for                   |             |
| while                 |             |
| break                 |             |
| continue              |             |
| boolean expression    |             |
| loop                  |             |
| nested loop           |             |
| nested if statement   |             |
| expression            |             |
| statement             |             |
| control flow          |             |

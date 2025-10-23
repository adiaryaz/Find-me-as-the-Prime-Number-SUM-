# Find me as the Prime Number (SUM)

A program to find and sum all prime numbers from a series of user inputs.

## 📝 Description

This program repeatedly asks the user if they want to enter a number. If the user agrees (by entering 'y'), they provide an integer. The program must check if this integer is a prime number. When the user decides to stop (by entering 'n'), the program calculates and displays the total sum of all the prime numbers that were entered.

-----

## 🎯 Problem Statement

### Input:

  * A sequence of 'y' (yes) or 'n' (no) prompts to control the loop.
  * An integer input from the user following each 'y' prompt.

### Output:

  * The total sum of all entered numbers that are identified as prime.
  * "NoProceed" if an invalid input (like a negative number) is entered.

### Rules:

1.  The program runs in a loop, asking for input. 'y' continues the loop, 'n' stops it.
2.  A **prime number** is a natural number **greater than 1** that has no positive divisors other than 1 and itself (e.g., 2, 3, 5, 7, 11...).
3.  Numbers 0, 1, and any non-prime positive numbers (like 4, 6, 10) are counted as 0 towards the sum.
4.  Based on Sample 5, entering a **negative number** is considered an invalid input, and the program should output "NoProceed".

-----

## 💡 Examples

### Example 1

**Input:**

```
y
2
y
10
n
```

**Output:**

```
2
```

**Explanation:** `2` is a prime number. `10` is not a prime number. The total sum is **2**.

### Example 2

**Input:**

```
y
2
y
3
y
5
n
```

**Output:**

```
10
```

**Explanation:** `2`, `3`, and `5` are all prime numbers. The sum is `2 + 3 + 5 = 10`.

### Example 3

**Input:**

```
y
4
y
8
n
```

**Output:**

```
0
```

**Explanation:** Neither `4` nor `8` is a prime number. The total sum is **0**.

### Example 4

**Input:**

```
n
```

**Output:**

```
0
```

**Explanation:** No numbers were entered, so the sum is **0**.

### Example 5

**Input:**

```
y
3
y
-5
```

**Output:**

```
NoProceed
```

**Explanation:** The input `-5` is a negative number, which is not a valid input for this problem.

-----

## 🚀 How to Use

1.  **Clone this repository**

    ```bash
    git clone https://github.com/adiaryaz/sum-of-primes.git
    cd sum-of-primes
    ```

2.  **Run the program** (assuming the file is `main.py`):

    ```bash
    python main.py
    ```

    Follow the 'y/n' prompts to enter numbers and see the result.

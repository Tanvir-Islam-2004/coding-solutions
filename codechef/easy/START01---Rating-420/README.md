# START01 - Rating 420

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Number Mirror

Write a program that takes a number $N$ as the input, and prints it to the output.

### Input Format

The only line of input contains a single integer.

### Output Format

Output the answer in a single line.

### Constraints
- $0 \leq N \leq 10^5$
### Sample 1:
Input
Output

```
123
```

```
123
```

### Explanation:

The input is 123. So the output is also 123.

### Sample 2:
Input
Output

```
15
```

```
15
```

### Explanation:

The input is 15. So the output is also 15.

## Solution

**Language:** Java  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-18T09:46:18.612Z  

```java
import java.util.Scanner;

class Codechef {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();
        System.out.println(n);
        scanner.close();
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/START01)
# 📐 Mathematics Reference Guide
## Intermediate Algebra (MAT-119) - Study Notes

This guide provides clear explanations of important mathematics topics for Intermediate Algebra. Each topic includes definitions, formulas, and examples.

---

## 📑 Table of Contents
1. [Linear Equations](#linear-equations)
2. [Systems of Equations](#systems-of-equations)
3. [Polynomials](#polynomials)
4. [Factoring](#factoring)
5. [Rational Expressions](#rational-expressions)
6. [Quadratic Equations](#quadratic-equations)
7. [Exponents and Radicals](#exponents-and-radicals)
8. [Functions](#functions)
9. [Graphing](#graphing)
10. [Word Problems](#word-problems)

---

## Linear Equations

### What is a Linear Equation?
A linear equation is an equation where the highest power of the variable is 1. It forms a straight line when graphed.

**Standard Form:** `ax + b = c`

### Solving Linear Equations
**Steps:**
1. Simplify both sides (distribute, combine like terms)
2. Move variables to one side, constants to the other
3. Isolate the variable
4. Check your solution

**Example:**
```
Solve: 3x + 5 = 14
Step 1: 3x + 5 - 5 = 14 - 5
Step 2: 3x = 9
Step 3: x = 3
Check: 3(3) + 5 = 9 + 5 = 14 ✓
```

### Slope-Intercept Form
**Formula:** `y = mx + b`
- `m` = slope (rise/run)
- `b` = y-intercept (where line crosses y-axis)

**Example:**
```
y = 2x + 3
Slope = 2 (goes up 2, right 1)
Y-intercept = 3 (crosses y-axis at (0,3))
```

---

## Systems of Equations

### What is a System of Equations?
Two or more equations working together. The solution is where the equations intersect.

### Methods to Solve:

#### 1. Substitution Method
**Steps:**
1. Solve one equation for one variable
2. Substitute into the other equation
3. Solve for remaining variable
4. Substitute back to find the other variable

**Example:**
```
Solve: y = x + 2
       2x + y = 8

Step 1: Already have y = x + 2
Step 2: Substitute: 2x + (x + 2) = 8
Step 3: 3x + 2 = 8
        3x = 6
        x = 2
Step 4: y = 2 + 2 = 4
Solution: (2, 4)
```

#### 2. Elimination Method
**Steps:**
1. Line up equations
2. Multiply to make coefficients opposites
3. Add equations to eliminate one variable
4. Solve and substitute back

**Example:**
```
Solve: 2x + 3y = 13
       x - y = -1

Multiply second by 3: 3x - 3y = -3
Add to first:         2x + 3y = 13
                      3x - 3y = -3
                      ___________
                      5x = 10
                      x = 2
Substitute: 2 - y = -1
            y = 3
Solution: (2, 3)
```

---

## Polynomials

### What is a Polynomial?
An expression with variables and coefficients using addition, subtraction, and multiplication.

**Examples:**
- `3x² + 2x - 5` (trinomial)
- `4x³ - x` (binomial)
- `7` (monomial)

### Adding/Subtracting Polynomials
**Rule:** Combine like terms (same variable and exponent)

**Example:**
```
(3x² + 2x - 5) + (x² - 4x + 3)
= 3x² + x² + 2x - 4x - 5 + 3
= 4x² - 2x - 2
```

### Multiplying Polynomials

#### FOIL Method (for binomials)
**F**irst, **O**uter, **I**nner, **L**ast

**Example:**
```
(x + 3)(x + 5)
F: x · x = x²
O: x · 5 = 5x
I: 3 · x = 3x
L: 3 · 5 = 15
Result: x² + 5x + 3x + 15 = x² + 8x + 15
```

#### Distributive Property
**Example:**
```
2x(x² + 3x - 4)
= 2x³ + 6x² - 8x
```

---

## Factoring

### Greatest Common Factor (GCF)
**Steps:**
1. Find the GCF of all terms
2. Factor it out

**Example:**
```
6x³ + 9x² - 15x
GCF = 3x
= 3x(2x² + 3x - 5)
```

### Factoring Trinomials (x² + bx + c)
**Method:** Find two numbers that multiply to `c` and add to `b`

**Example:**
```
x² + 7x + 12
Find: ___ × ___ = 12 and ___ + ___ = 7
Answer: 3 and 4
Result: (x + 3)(x + 4)
```

### Factoring by Grouping
**Example:**
```
x³ + 3x² + 2x + 6
= (x³ + 3x²) + (2x + 6)
= x²(x + 3) + 2(x + 3)
= (x + 3)(x² + 2)
```

### Difference of Squares
**Formula:** `a² - b² = (a + b)(a - b)`

**Example:**
```
x² - 9 = x² - 3²
= (x + 3)(x - 3)
```

---

## Rational Expressions

### What is a Rational Expression?
A fraction with polynomials in numerator and/or denominator.

**Example:** `(x + 2)/(x - 3)`

### Simplifying Rational Expressions
**Steps:**
1. Factor numerator and denominator
2. Cancel common factors

**Example:**
```
(x² - 4)/(x² + 4x + 4)
= (x + 2)(x - 2)/(x + 2)(x + 2)
= (x - 2)/(x + 2)
```

### Adding/Subtracting Rational Expressions
**Steps:**
1. Find common denominator
2. Convert fractions
3. Add/subtract numerators
4. Simplify

**Example:**
```
2/x + 3/(x+1)
= 2(x+1)/[x(x+1)] + 3x/[x(x+1)]
= [2(x+1) + 3x]/[x(x+1)]
= (2x + 2 + 3x)/(x² + x)
= (5x + 2)/(x² + x)
```

---

## Quadratic Equations

### What is a Quadratic Equation?
An equation where the highest power is 2.

**Standard Form:** `ax² + bx + c = 0`

### Methods to Solve:

#### 1. Factoring
**Example:**
```
x² + 5x + 6 = 0
(x + 2)(x + 3) = 0
x + 2 = 0  or  x + 3 = 0
x = -2  or  x = -3
```

#### 2. Quadratic Formula
**Formula:** `x = [-b ± √(b² - 4ac)] / (2a)`

**Example:**
```
Solve: 2x² + 5x - 3 = 0
a = 2, b = 5, c = -3

x = [-5 ± √(25 - 4(2)(-3))] / (2·2)
x = [-5 ± √(25 + 24)] / 4
x = [-5 ± √49] / 4
x = [-5 ± 7] / 4

x = (-5 + 7)/4 = 2/4 = 1/2
or
x = (-5 - 7)/4 = -12/4 = -3
```

#### 3. Completing the Square
**Steps:**
1. Move constant to right side
2. Make coefficient of x² equal to 1
3. Add (b/2)² to both sides
4. Factor left side
5. Take square root of both sides

**Example:**
```
x² + 6x - 7 = 0
x² + 6x = 7
x² + 6x + 9 = 7 + 9
(x + 3)² = 16
x + 3 = ±4
x = -3 + 4 = 1  or  x = -3 - 4 = -7
```

---

## Exponents and Radicals

### Exponent Rules

1. **Product Rule:** `x^a · x^b = x^(a+b)`
   - Example: `x³ · x² = x⁵`

2. **Quotient Rule:** `x^a / x^b = x^(a-b)`
   - Example: `x⁵ / x² = x³`

3. **Power Rule:** `(x^a)^b = x^(ab)`
   - Example: `(x²)³ = x⁶`

4. **Zero Exponent:** `x⁰ = 1` (if x ≠ 0)

5. **Negative Exponent:** `x^(-a) = 1/x^a`
   - Example: `x^(-2) = 1/x²`

### Radical Rules

1. **Product Rule:** `√(ab) = √a · √b`
   - Example: `√12 = √(4·3) = √4 · √3 = 2√3`

2. **Quotient Rule:** `√(a/b) = √a / √b`
   - Example: `√(16/4) = √16 / √4 = 4/2 = 2`

3. **Simplifying Radicals:**
   - Find perfect square factors
   - Example: `√50 = √(25·2) = 5√2`

### Rationalizing the Denominator
**Goal:** Remove radicals from denominator

**Example:**
```
3/√5
= 3/√5 · √5/√5
= 3√5/5
```

---

## Functions

### What is a Function?
A relationship where each input has exactly one output.

**Notation:** `f(x)` means "function of x"

### Evaluating Functions
**Example:**
```
If f(x) = 2x² - 3x + 1, find f(3)

f(3) = 2(3)² - 3(3) + 1
     = 2(9) - 9 + 1
     = 18 - 9 + 1
     = 10
```

### Domain and Range
- **Domain:** All possible input values (x-values)
- **Range:** All possible output values (y-values)

**Example:**
```
f(x) = √x
Domain: x ≥ 0 (can't take square root of negative)
Range: y ≥ 0 (square root is always non-negative)
```

### Types of Functions

1. **Linear:** `f(x) = mx + b` (straight line)
2. **Quadratic:** `f(x) = ax² + bx + c` (parabola)
3. **Absolute Value:** `f(x) = |x|` (V-shape)
4. **Square Root:** `f(x) = √x` (half parabola)

---

## Graphing

### Graphing Linear Equations

**Method 1: Using Slope-Intercept Form (y = mx + b)**
1. Plot y-intercept (0, b)
2. Use slope to find next point
3. Draw line through points

**Example:**
```
y = 2x + 1
Start at (0, 1)
Slope = 2 = 2/1 (up 2, right 1)
Next point: (1, 3)
```

**Method 2: Using x and y Intercepts**
1. Set y = 0, solve for x (x-intercept)
2. Set x = 0, solve for y (y-intercept)
3. Plot both points and draw line

### Graphing Quadratic Equations (Parabolas)

**Key Features:**
- **Vertex:** Highest or lowest point
- **Axis of Symmetry:** Vertical line through vertex: `x = -b/(2a)`
- **Opens Up** if a > 0, **Opens Down** if a < 0

**Example:**
```
y = x² - 4x + 3

Axis of symmetry: x = -(-4)/(2·1) = 2
Vertex: When x = 2, y = 4 - 8 + 3 = -1
Vertex: (2, -1)
Y-intercept: (0, 3)
X-intercepts: Factor: (x-1)(x-3) = 0, so x = 1, 3
```

### Graphing Inequalities

**Steps:**
1. Graph the boundary line (use dashed line for < or >, solid for ≤ or ≥)
2. Test a point (often (0,0))
3. Shade the correct region

**Example:**
```
y < 2x + 1
1. Graph y = 2x + 1 (dashed line)
2. Test (0,0): 0 < 2(0) + 1 → 0 < 1 ✓
3. Shade below the line
```

---

## Word Problems

### General Strategy
1. **Read carefully** - understand what's being asked
2. **Identify variables** - what are you solving for?
3. **Write equations** - translate words to math
4. **Solve** - use appropriate method
5. **Check** - does the answer make sense?

### Common Types:

#### 1. Age Problems
**Example:**
```
Sarah is 3 years older than Tom. In 5 years, Sarah will be twice as old as Tom is now. How old are they now?

Let t = Tom's age now
Then s = t + 3 = Sarah's age now

In 5 years: s + 5 = 2t
Substitute: (t + 3) + 5 = 2t
           t + 8 = 2t
           8 = t
Tom is 8, Sarah is 11
```

#### 2. Distance/Rate/Time Problems
**Formula:** `Distance = Rate × Time` or `d = rt`

**Example:**
```
Two cars leave at the same time from cities 300 miles apart, traveling toward each other. One travels at 45 mph, the other at 55 mph. When will they meet?

Let t = time until they meet
Car 1 distance: 45t
Car 2 distance: 55t
Total: 45t + 55t = 300
      100t = 300
      t = 3 hours
```

#### 3. Money/Cost Problems
**Example:**
```
Adult tickets cost $10, child tickets cost $6. If 50 tickets were sold for $420, how many of each were sold?

Let a = adult tickets
Let c = child tickets

a + c = 50
10a + 6c = 420

From first: c = 50 - a
Substitute: 10a + 6(50 - a) = 420
           10a + 300 - 6a = 420
           4a = 120
           a = 30
           c = 20
Answer: 30 adult, 20 child tickets
```

#### 4. Mixture Problems
**Example:**
```
How much water must be added to 10 liters of 20% acid solution to make it 10% acid?

Let x = liters of water to add
Acid in original: 0.20(10) = 2 liters
Acid stays same: 2 liters
New total: 10 + x liters
New concentration: 2/(10 + x) = 0.10

2 = 0.10(10 + x)
2 = 1 + 0.10x
1 = 0.10x
x = 10 liters
```

---

## 📝 Study Tips

### For Success in Algebra:
1. **Practice daily** - Even 15-30 minutes helps
2. **Show all work** - Helps catch mistakes
3. **Check answers** - Substitute back into original
4. **Learn formulas** - Make flashcards
5. **Ask questions** - Don't wait until confused
6. **Review mistakes** - Learn from errors
7. **Work examples** - Don't just read them
8. **Use resources** - Textbook, Khan Academy, professor office hours

### Common Mistakes to Avoid:
- Forgetting to distribute negative signs
- Not finding common denominators
- Sign errors when multiplying negatives
- Forgetting to check solutions (especially for rational equations)
- Rushing through word problems

---

## 📚 Additional Resources

### Online Resources:
- **Khan Academy** - Free video lessons and practice
- **Paul's Online Math Notes** - Detailed explanations
- **Wolfram Alpha** - Check your work
- **Desmos** - Free graphing calculator

### Remember:
✨ *"Math is not about being fast, it's about being accurate and understanding the process."*

---

*Created for MAT-119 Intermediate Algebra Study Reference*
*Keep learning, keep growing! 🌙*

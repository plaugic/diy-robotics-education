## Day 1: Arithmetic and Fundamental Algebraic Operations

### Focus

Refresh the building blocks of mathematics—these underpin all later topics. You need to be fluent with basic numerical operations and algebraic notation to succeed in higher math.

Day 1 is about building *automaticity*: you should be able to compute, convert, and simplify without hesitation. Calculus (and even precalculus) becomes dramatically easier when you aren’t spending effort fighting fractions, signs, or order-of-operations mistakes.

A useful standard for “ready” at the end of Day 1:
- You can add/subtract common fractions quickly and correctly.
- You can convert between decimals, fractions, and percentages reliably.
- You rarely make sign errors with negative numbers.
- You consistently apply order of operations, including tricky exponent/sign cases.
- You can substitute values for variables and evaluate expressions cleanly.

---

## Topics to Master

### 1) Fractions and Decimals

#### A. Fraction basics (what the parts mean)
A fraction \(\frac{a}{b}\) represents **division**:  
\[
\frac{a}{b} = a \div b
\]
- \(a\) is the numerator (how many parts)
- \(b\) is the denominator (size/number of equal parts)
- A fraction is undefined if \(b = 0\)

#### B. Converting fractions to decimals
Compute:
\[
\frac{a}{b} = a \div b
\]
Example:
\[
\frac{3}{8} = 3 \div 8 = 0.375
\]
Tips:
- If the denominator is a factor of \(10^n\) (like \(2, 4, 5, 8, 20, 25, 40, 125\)), decimals often terminate.
- Otherwise, decimals may repeat (e.g., \(\frac{2}{3} = 0.\overline{6}\)).

#### C. Converting decimals to fractions
Use place value:
- If \(0.375\), it is \(375\) thousandths:
\[
0.375 = \frac{375}{1000}
\]
Then reduce:
\[
\frac{375}{1000} = \frac{3}{8}
\]
Reduction rule:
\[
\frac{a}{b} = \frac{a \div d}{b \div d}
\quad\text{where \(d\) is a common factor of \(a\) and \(b\)}
\]

#### D. Adding and subtracting fractions
You must use a **common denominator**:
\[
\frac{a}{b} + \frac{c}{d} = \frac{ad + bc}{bd}
\]
Example:
\[
\frac{3}{4} + \frac{2}{3}
= \frac{3\cdot 3}{4\cdot 3} + \frac{2\cdot 4}{3\cdot 4}
= \frac{9}{12} + \frac{8}{12}
= \frac{17}{12}
\]
Convert improper fractions if needed:
\[
\frac{17}{12} = 1\frac{5}{12}
\]

Common pitfalls:
- Adding numerators and denominators separately (incorrect):
\[
\frac{1}{2} + \frac{1}{3} \ne \frac{2}{5}
\]
- Forgetting to distribute negatives:
\[
\frac{3}{4} - \frac{2}{3}
= \frac{9}{12} - \frac{8}{12}
= \frac{1}{12}
\]

#### E. Multiplying fractions
Multiply straight across:
\[
\frac{a}{b}\cdot \frac{c}{d} = \frac{ac}{bd}
\]
Example:
\[
\frac{3}{4}\cdot \frac{2}{3} = \frac{6}{12} = \frac{1}{2}
\]
Best practice: **reduce before multiplying** if possible (cross-cancel factors).

#### F. Dividing fractions
Divide by multiplying by the reciprocal:
\[
\frac{a}{b} \div \frac{c}{d} = \frac{a}{b}\cdot \frac{d}{c}
\quad (c \ne 0)
\]
Example:
\[
\frac{3}{5} \div \frac{2}{7} = \frac{3}{5}\cdot \frac{7}{2} = \frac{21}{10}
\]

#### G. Decimal operations (place value discipline)
When adding/subtracting decimals, align decimal points:
\[
12.30 + 0.045 = 12.345
\]
When multiplying decimals, multiply as integers then place decimal based on total decimal places:
\[
0.12 \cdot 0.3 = 0.036
\]
(\(2\) decimal places + \(1\) decimal place = \(3\) total)

When dividing by powers of 10:
\[
45.6 \div 10 = 4.56,\quad 45.6 \div 100 = 0.456
\]

---

### 2) Percentages

**Percent** means “per 100”:
\[
p\% = \frac{p}{100}
\]
So:
\[
20\% = \frac{20}{100} = 0.20
\]

#### A. Percent to decimal / fraction
- Percent to decimal: divide by \(100\)
\[
15\% = 0.15
\]
- Percent to fraction:
\[
15\% = \frac{15}{100} = \frac{3}{20}
\]

#### B. Decimal to percent
Multiply by \(100\) and add \(\%\):
\[
0.375 = 37.5\%
\]

#### C. Finding a percent of a number
\[
p\% \text{ of } N = \frac{p}{100}\cdot N
\]
Example:
\[
15\% \text{ of } 200 = 0.15\cdot 200 = 30
\]

#### D. Expressing one number as a percent of another
\[
\text{Percent} = \frac{\text{part}}{\text{whole}}\cdot 100\%
\]
Example:
\[
\frac{45}{60}\cdot 100\% = 75\%
\]

#### E. Quick sanity checks
- \(50\%\) is half, \(25\%\) is a quarter, \(10\%\) is one tenth.
- If the percent is greater than \(100\%\), the result is bigger than the original.
- If the percent is less than \(1\%\), the result is small relative to the original.

---

### 3) Negative Numbers and Absolute Value

#### A. Number line intuition
- Positive numbers are to the right of \(0\)
- Negative numbers are to the left of \(0\)

#### B. Adding and subtracting negatives
Core rules:
- Adding a negative moves left:
\[
5 + (-2) = 3
\]
- Subtracting a number is adding its opposite:
\[
5 - 2 = 5 + (-2)
\]
- Subtracting a negative becomes addition:
\[
5 - (-2) = 5 + 2 = 7
\]

Common patterns to practice:
\[
-3 + 7 = 4,\quad -3 - 7 = -10,\quad -3 - (-7) = 4
\]

#### C. Multiplication and division sign rules
- Same signs → positive
- Different signs → negative
\[
(-2)(-5)=10,\quad (-2)(5)=-10,\quad (2)(-5)=-10
\]
\[
\frac{-12}{3}=-4,\quad \frac{-12}{-3}=4
\]

#### D. Absolute value
Absolute value is distance from zero:
\[
|x| \ge 0
\]
Examples:
\[
|-5| = 5,\quad |5| = 5,\quad |0|=0
\]
Expression example:
\[
|5 - 8| = |-3| = 3
\]
Key idea: evaluate inside first, then take the non-negative distance.

---

### 4) Order of Operations (PEMDAS)

Order:
1. Parentheses (and grouping symbols)
2. Exponents
3. Multiplication/Division left-to-right
4. Addition/Subtraction left-to-right

#### A. Critical exponent/sign pitfall
The expression:
\[
-2^2
\]
means:
\[
-(2^2) = -4
\]
because exponents apply before the leading negative sign unless parentheses change it.

But:
\[
(-2)^2 = 4
\]
because the negative is included in the base due to parentheses.

#### B. Example: evaluate correctly
Evaluate:
\[
-2^2 + (3 - 5)
\]
Steps:
- Exponent first:
\[
-2^2 = -(2^2) = -4
\]
- Parentheses:
\[
(3 - 5) = -2
\]
- Add:
\[
-4 + (-2) = -6
\]

#### C. Mixed operations example
Simplify:
\[
-2^2 + \frac{10}{(5 - 3)}
\]
Steps:
- Parentheses:
\[
(5-3)=2
\]
- Exponent:
\[
-2^2 = -4
\]
- Division:
\[
\frac{10}{2}=5
\]
- Addition:
\[
-4 + 5 = 1
\]

---

### 5) Basic Variable Notation

A variable (like \(x\)) is a placeholder for a number. Substitution means replacing the variable with a given value.

Example:
If \(x=3\), evaluate:
\[
2x + 5
\]
Substitute:
\[
2(3) + 5 = 6 + 5 = 11
\]

#### A. Evaluate carefully with negatives
If \(x=-3\), evaluate:
\[
2x + 5 = 2(-3)+5 = -6+5 = -1
\]

If \(x=-2\), evaluate:
\[
x^2 - 4x = (-2)^2 - 4(-2) = 4 + 8 = 12
\]
Notice the parentheses are essential when squaring a negative:
\[
(-2)^2 \ne -2^2
\]

#### B. Treat variables like numbers with operations
Examples:
- \(3x + 2x = 5x\)
- \(x + x + x = 3x\)
- \(2(x + 5) = 2x + 10\)

(You’ll lean on these constantly later in algebra and calculus.)

---

## Learning Resources

### Khan Academy – Arithmetic (videos and exercises)

Use it to refresh and drill:
- Fractions: finding common denominators, simplifying, add/subtract/multiply/divide
- Decimals: place value, operations, conversions
- Percents: percent-of problems, conversions, word problems
- Negative numbers and absolute value: number line reasoning, operations, distance idea

Suggested approach:
1. Watch a short video for the concept (5–10 minutes).
2. Do a small set of problems immediately after.
3. If you miss any, re-do similar problems until the correct method feels routine.

### Purplemath – Fractions and Absolute Value (online lessons)

Use it to fix conceptual “gotchas,” especially:
- Why common denominators are required for addition/subtraction
- Typical sign mistakes with negatives
- The meaning of absolute value as distance (not “make it positive” without thinking)

---

## Practice

After reviewing, solidify your skills by doing practice problems. Khan Academy’s arithmetic practice sets are very effective—try exercises on adding and subtracting fractions, converting decimals to fractions (and vice versa), and negative number operations.

Aim to comfortably handle problems like:

- Compute:
  \[
  \frac{3}{4} + \frac{2}{3}
  \]
  (find a common denominator and add)

- Convert:
  \[
  0.375 \text{ to a fraction}
  \]
  and convert:
  \[
  \frac{3}{8} \text{ to a decimal}
  \]

- Find:
  \[
  15\% \text{ of } 200
  \]

- Evaluate:
  \[
  |5 - 8|
  \]

- Simplify:
  \[
  -2^2 + \frac{10}{(5 - 3)}
  \]
  by correctly applying the order of operations

#### Extra “skill-check” drills (recommended)
These are the kinds of quick computations that prevent calculus errors later:

1. Common fraction sums:
   \[
   \frac{1}{6} + \frac{1}{4},\quad \frac{5}{8} - \frac{1}{3}
   \]

2. Multiplication/division with negatives:
   \[
   (-6)\cdot 7,\quad \frac{24}{-8},\quad (-3)(-11)
   \]

3. Absolute value with expressions:
   \[
   |2 - 9|,\quad |-4 + 1|,\quad |-(3)|,\quad |0-(-5)|
   \]

4. Exponent sign traps:
   \[
   -3^2,\quad (-3)^2,\quad -(-2)^2,\quad (-2)^3
   \]

5. Substitute and evaluate:
   If \(x=2\):
   \[
   3x^2 - 4x + 1
   \]
   If \(x=-1\):
   \[
   2(x-5) - x^2
   \]

---

## Why This Matters

Much of calculus involves manipulating algebraic expressions and numbers. If you can’t confidently handle fractions or negative numbers, even a simple calculus problem can trip you up—especially because calculus often combines multiple skills at once (fractions inside parentheses, negatives in exponents, substitution into formulas, and multi-step simplification).

Mastery of Day 1 material means you can perform basic calculations smoothly and devote your mental energy to the *new* concepts in calculus (limits, derivatives, integrals), rather than getting bogged down by arithmetic mistakes. By investing time now to reinforce these fundamentals, you’ll prevent small algebraic errors from derailing you when the math gets more complex.
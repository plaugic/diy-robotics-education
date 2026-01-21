# Day 8: Introduction to Calculus – Limits and Continuity

## Focus

Congratulations — you’re now stepping into calculus itself! The first fundamental concept is the **limit**. Limits describe how a function’s output behaves as the input approaches some value, and they underpin the definitions of **derivatives** and **integrals**. Today you will learn what limits are, how to evaluate basic limits, and the concept of **continuity**. This will bridge your algebra/pre-calculus knowledge into the new realm of calculus ideas.

---

## Topics to Master

### 1. Concept of a Limit
Understand informally that  

\[
\lim_{x \to a} f(x) = L
\]

means that \( f(x) \) gets arbitrarily close to \( L \) as \( x \) approaches \( a \) (from both sides).

**Key insight:**  
The value of \( f(a) \) (if it even exists) is *not* directly relevant to the limit — what matters is the trend of \( f(x) \) around \( a \). For example, you can have a situation where \( f(a) \) is undefined or different from the limit, yet the limit exists (like a removable hole in the graph). Grasp this through examples (see below).

---

### 2. Computing Limits Numerically / Graphically
Practice finding limits by creating small tables of values.

**Example:**  
Estimate  
\[
\lim_{x \to 2} \frac{x^2 - 4}{x - 2}
\]

by plugging in values such as:
- \( x = 1.9, 1.99 \)
- \( x = 2.01, 2.1 \)

You’ll see the values approaching **4**.

**Graphical approach:**  
Look at the graph and observe what \( y \)-value the function approaches as \( x \) approaches the target. This builds intuition.

---

### 3. Basic Algebraic Limit Techniques

#### a. Direct Substitution
If \( f \) is a “nice” (continuous) function at \( a \), then:

\[
\lim_{x \to a} f(x) = f(a)
\]

This works for polynomials, simple trig, exponential, and logarithmic functions where plugging in \( a \) is valid.

**Example:**
\[
\lim_{x \to 3} (x^2 - 1) = 3^2 - 1 = 8
\]

---

#### b. Indeterminate Form \( \frac{0}{0} \)
Many interesting limits produce \( \frac{0}{0} \) when plugging in directly. Use algebraic manipulation:

- Factoring and canceling  
- Rationalizing  
- Using conjugates  

**Example:**
\[
\lim_{x \to 2} \frac{x^2 - 4}{x - 2}
\]

Direct substitution gives \( 0/0 \). Factor:
\[
x^2 - 4 = (x - 2)(x + 2)
\]

Cancel \( (x - 2) \):
\[
\lim_{x \to 2} (x + 2) = 4
\]

**Another example:**
\[
\lim_{h \to 0} \frac{\sqrt{1+h} - 1}{h}
\]

Rationalize:
\[
\frac{(\sqrt{1+h}-1)(\sqrt{1+h}+1)}{h(\sqrt{1+h}+1)}
= \frac{1+h-1}{h(\sqrt{1+h}+1)}
= \frac{1}{\sqrt{1+h}+1}
\]

Now plug in \( h \to 0 \):
\[
\frac{1}{2}
\]

Practice a few of these manipulations.

---

### 4. Limits at Infinity
Understand how functions behave as \( x \to \infty \) or \( x \to -\infty \).

For rational functions:
- Same degree (top and bottom): limit = ratio of leading coefficients  
- Denominator degree > numerator degree: limit = 0  
- Numerator degree > denominator degree: limit diverges (\( \pm\infty \))

**Example:**
\[
\lim_{x \to \infty} \frac{5x^2 - 1}{2x^2 + 3x} = \frac{5}{2}
\]

These ideas are important later for improper integrals and series.

---

### 5. Continuity
A function \( f(x) \) is **continuous** at \( x = a \) if:

\[
\lim_{x \to a} f(x) = f(a)
\]

In words: the limit exists and equals the function’s value.

- Polynomials, \( \sin x \), \( e^x \), etc., are continuous everywhere.
- \( f(x) = \frac{x^2 - 4}{x - 2} \) is **not** continuous at \( x = 2 \) (there’s a hole).
- Piecewise functions can have **jump discontinuities** if left- and right-hand limits differ.

You should be able to identify:
- Removable discontinuities (holes)
- Jump discontinuities
- Infinite discontinuities (vertical asymptotes)

This matters because many theorems in calculus (e.g., the Intermediate Value Theorem) apply only to continuous functions.

---

### 6. Tricky Limits (Optional but Important)
Be aware of these special limits:

\[
\lim_{x \to 0} \frac{\sin x}{x} = 1
\]

\[
\lim_{x \to 0} \frac{e^x - 1}{x} = 1
\]

(Equivalently, \( \lim_{n \to \infty} (1 + \frac{1}{n})^n = e \).)

If time permits, read why \( \sin x \sim x \) near 0. At minimum, **memorize these results** — they appear constantly in Calc I and II.

---

## Learning Resources

- **Khan Academy – Limits Intro**  
  Start with “Introduction to limits.” Focus on left-hand vs right-hand limits and algebraic evaluation (factoring, rationalizing).

- **3Blue1Brown – Essence of Calculus (Chapter 2)**  
  “The paradox of the derivative” introduces limits through instantaneous rate of change. Highly visual and intuitive. Even the first 10 minutes is valuable.

- **Paul’s Online Math Notes – Calculus I (Limits section)**  
  Excellent step-by-step explanations of \( 0/0 \) cases, one-sided limits, and continuity. Pay attention to limit properties summaries.

---

## Practice

### 1. Understanding the Definition
In your own words, describe what  
\[
\lim_{x \to a} f(x) = L
\]
means.

Example:
\[
f(x) = \frac{x^2 - 1}{x - 1}
\]

Simplify:
\[
f(x) = x + 1 \quad (x \neq 1)
\]

- \( f(1) \) is undefined  
- \( \lim_{x \to 1} f(x) = 2 \)

Explain why the limit exists even though \( f(1) \) does not.

---

### 2. Numerical Limits
Let:
\[
g(x) = \frac{|x|}{x}
\]

Make a table approaching 0 from both sides:
- Left: \( x = -0.1, -0.01, \dots \)
- Right: \( x = 0.1, 0.01, \dots \)

You’ll find:
- Left-hand limit = −1  
- Right-hand limit = +1  

Therefore:
\[
\lim_{x \to 0} g(x) \text{ does not exist (DNE)}
\]

---

### 3. Algebraic Evaluation
Solve the following limits:

1. \(\lim_{x \to 3} (2x^3 - x)\)
2. \(\lim_{x \to -2} \frac{x^2 - 4}{x + 2}\)
3. \(\lim_{t \to 0} \frac{\sqrt{4+t} - 2}{t}\) (answer: \( \frac{1}{4} \))
4. \(\lim_{x \to 5^+} \frac{1}{5 - x}\) (answer: \( -\infty \))
5. \(\lim_{x \to \infty} \frac{3x^2 + 1}{4x^2 - x + 9}\)
6. \(\lim_{x \to 0} \frac{\sin x}{x}\)

Check answers using reasoning or numerical approximation.

---

### 4. Continuity Check
Consider:
\[
h(x) =
\begin{cases}
x^2 & x < 1 \\
3 & x = 1 \\
2x - 1 & x > 1
\end{cases}
\]

- \( \lim_{x \to 1^-} h(x) = 1 \)
- \( \lim_{x \to 1^+} h(x) = 1 \)
- \( h(1) = 3 \)

The limit exists but does not equal the function value → **not continuous** at \( x = 1 \).  
If we redefined \( h(1) = 1 \), the discontinuity would be removable.

---

## Why This Matters

Limits are the foundation of calculus:

- **Derivatives** are defined as limits (slopes as points get infinitely close).
- **Integrals** are defined as limits (summing infinitely many slices).
- **Sequences and series** in Calculus II rely entirely on limits.

Understanding limits makes derivatives and integrals feel natural instead of mysterious. Continuity also underpins powerful results like the Intermediate Value Theorem and convergence tests for improper integrals.

By completing Day 8, you’re officially thinking like a calculus student — comfortable with approaching values, infinity, and “what happens as…”. This mindset will carry you through both Calculus I and II.
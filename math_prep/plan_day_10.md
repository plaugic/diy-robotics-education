# Day 10: Integration – Antiderivatives and the Fundamental Theorem of Calculus

## Focus

In the final stretch, you’ll tackle the basics of **integration**, which is the other fundamental operation in calculus (roughly the inverse of differentiation). Calculus II will delve deep into integration techniques and applications, so today we establish a strong base: understanding integrals as **antiderivatives and area**, learning to compute **basic integrals**, and appreciating the **Fundamental Theorem of Calculus (FTC)**, which links derivatives and integrals.

By the end, you should be able to integrate standard functions and understand how integration will expand in Calculus II.

---

## Topics to Master

### Antiderivatives

- Recognize that integration (indefinite integrals) is about finding a function \( F(x) \) whose derivative is the given function \( f(x) \).
- Example: An antiderivative of \( 2x \) is \( x^2 \), since \( (x^2)' = 2x \).
- Always include the **constant of integration** \( +C \) for indefinite integrals.
- Practice by asking: *“What differentiates to…?”*
  - Example:  
    \[
    \int 3x^2 \, dx = x^3 + C \quad \text{since } (x^3)' = 3x^2
    \]
- This is essentially **reversing differentiation rules**.

---

### Basic Integration Rules

#### Power Rule (Integral Form)

\[
\int x^n \, dx = \frac{x^{n+1}}{n+1} + C \quad \text{for } n \neq -1
\]

- Example:
  \[
  \int x^4 \, dx = \frac{x^5}{5} + C
  \]
- This is the inverse of the derivative power rule.

#### Logarithmic Case

\[
\int \frac{1}{x} \, dx = \ln |x| + C
\]

- This is the special case where \( n = -1 \).

#### Exponential and Inverse Trig Integrals

- \( \int e^x \, dx = e^x + C \)
- \( \int a^x \, dx = \frac{a^x}{\ln a} + C \) for \( a > 0 \)
- \( \int \frac{1}{1+x^2} \, dx = \arctan x + C \)
- \( \int \frac{1}{\sqrt{1-x^2}} \, dx = \arcsin x + C \)

> It’s okay if inverse trig integrals aren’t memorized yet—just know they exist.

---

### Trigonometric Integrals (Memorize These)

- \( \int \sin x \, dx = -\cos x + C \)
- \( \int \cos x \, dx = \sin x + C \)
- \( \int \sec^2 x \, dx = \tan x + C \)
- \( \int \csc^2 x \, dx = -\cot x + C \)

Also useful (but slightly less critical):

- \( \int \sec x \tan x \, dx = \sec x + C \)

---

### Linearity of Integrals

\[
\int [a f(x) + b g(x)] \, dx = a \int f(x) \, dx + b \int g(x) \, dx
\]

- Integrate **term by term**.

---

### Reverse Chain Rule (Substitution Intuition)

Recognize simple \( u \)-substitution patterns.

**Example 1:**
\[
\int 2x(1+x^2)^3 \, dx
\]

- Derivative of \( 1+x^2 \) is \( 2x \)
- Let \( u = 1+x^2 \), \( du = 2x\,dx \)
- Integral becomes:
  \[
  \int u^3 \, du = \frac{u^4}{4} + C = \frac{(1+x^2)^4}{4} + C
  \]

**Example 2:**
\[
\int \cos(3x) \, dx = \frac{1}{3}\sin(3x) + C
\]

General idea:
\[
\int f'(g(x))g'(x)\,dx = f(g(x)) + C
\]

This is the **chain rule in reverse**, and it is a *huge* part of Calculus II.

---

### Definite Integrals and Area

- The definite integral
  \[
  \int_a^b f(x)\,dx
  \]
  represents **net area** under the curve from \( a \) to \( b \).
- Area above the x-axis is positive; below is negative.
- If \( f(x) \ge 0 \) on \([a,b]\), it equals geometric area.

Using the **Fundamental Theorem of Calculus (FTC)**:
\[
\int_a^b f(x)\,dx = F(b) - F(a)
\quad \text{where } F'(x) = f(x)
\]

**Example:**
\[
\int_0^2 3x^2 \, dx
\]

- Antiderivative: \( x^3 \)
- Evaluate:
  \[
  2^3 - 0^3 = 8
  \]

---

### Fundamental Theorem of Calculus (Conceptual)

- **FTC Part 1**:
  \[
  \frac{d}{dx}\int_a^x f(t)\,dt = f(x)
  \]
  The derivative of accumulated area returns the original function.
- **FTC Part 2**:
  \[
  \int_a^b f(x)\,dx = F(b) - F(a)
  \]

**Big idea:** Differentiation and integration are **opposites**.

---

### Basic Integral Applications

#### Interpretation

- If \( v(t) \) is velocity:
  \[
  \int_{t_1}^{t_2} v(t)\,dt
  \]
  gives **displacement**.
- If \( f'(x) \) is a rate:
  \[
  \int f'(x)\,dx = f(x) + C
  \]

Derivatives measure **instantaneous change**; integrals **accumulate change**.

#### Area Example

- Area between \( y = x \) and the x-axis from \( x=0 \) to \( x=3 \):
  \[
  \int_0^3 x\,dx = \left[\frac{x^2}{2}\right]_0^3 = \frac{9}{2}
  \]

---

## Learning Resources

- **Khan Academy – Integration Intro**
  - Antiderivatives and indefinite integrals
  - Definite integrals and signed area
  - Fundamental Theorem of Calculus
- **Paul’s Online Math Notes – Calculus I**
  - Indefinite integrals
  - Tables of common antiderivatives
  - Clear explanations of the FTC
- **Reference Tables**
  - Tables of integrals (OpenStax, appendices, etc.)

---

## Practice

### Antiderivatives

- Given \( f'(x) = 7x^6 \), find \( f(x) \):
  \[
  f(x) = x^7 + C
  \]

- If
  \[
  \frac{d}{dx}[\text{something}] = \sec^2 x
  \]
  then:
  \[
  \int \sec^2 x\,dx = \tan x + C
  \]

---

### Practice 10 Indefinite Integrals

1. $$\int (5x^4 - 2x + 3)\,dx$$

2. $$\int \frac{1}{x^3}\,dx$$

3. $$\int \sin x\,dx$$

4. $$\int \sec^2 x\,dx$$

5. $$\int e^{5x}\,dx$$

6. $$\int \frac{1}{2x}\,dx$$

7. $$\int (3x + 2)^5\,dx$$

8. $$\int \frac{\cos(3x)}{5}\,dx$$

9. $$\int \frac{2x}{x^2 + 1}\,dx$$

10. $$\int (\sec x \tan x)\,dx$$

> Check a few by differentiating your answers.

---

### Definite Integrals

- \( \int_1^4 3x^2\,dx = 63 \)
- \( \int_0^\pi \sin x\,dx = 2 \)
- \( \int_{-1}^1 5x^3\,dx = 0 \)
- \( \int_0^2 (x^2 - 4)\,dx = -\frac{16}{3} \)

---

### FTC Understanding

- If:
  \[
  F(x) = \int_0^x \cos t\,dt
  \]
  then:
  \[
  F'(x) = \cos x
  \]

- Advanced example:
  \[
  G(x) = \int_2^{x^2} \sqrt{1+t^2}\,dt
  \]
  \[
  G'(x) = \sqrt{1+x^4}\cdot 2x
  \]

---

## Review and Wrap-Up

At this point, you should clearly recognize that **integration and differentiation are inverse processes**. Consider creating a **one-page summary sheet** of:

- Derivative rules
- Integral rules
- FTC concepts

This will be extremely useful as you move into Calculus II.

---

## Why This Matters

Integration is the **core of Calculus II**. You will study:

- Integration by parts  
- Trigonometric integrals  
- Partial fractions  
- Improper integrals  
- Series and power series  

All of these rely on the fundamentals covered today. Calc II assumes you can integrate:

- Polynomials
- Trigonometric functions
- Exponentials
- Basic rational functions

The **Fundamental Theorem of Calculus** is the bridge between theory and computation. Mastering these ideas now will allow you to approach advanced Calc II topics—especially series and applications of integration—with confidence.
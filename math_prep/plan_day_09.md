# Day 9: Differentiation – The Concept of the Derivative and Basic Rules

## Focus

Time to learn about the **derivative**, the central idea of Calculus I (and heavily used in Calculus II for series tests, etc.). The derivative measures **instantaneous rate of change**—essentially, it gives the **slope of the tangent line** to a function’s graph.

Today, you’ll:
- Grasp what a derivative *is*
- Learn how to compute derivatives using standard rules (power, product, quotient, chain)
- See basic applications of derivatives

This is a **packed but critical day**. By the end, you should be able to differentiate most algebraic functions you encounter.

---

## Topics to Master

### Definition of the Derivative

Understand the derivative \( f'(x) \) as:

\[
f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}
\]

This formula represents:
- The slope of a **secant line** between two nearby points
- Letting those points move infinitely close to become a **tangent line**

Key interpretations:
- \( f'(a) \) is the slope of \( f \) at \( x = a \)
- If \( f \) is **position**, then \( f' \) is **velocity**
- If \( f \) is a **curve**, then \( f' \) gives its **slope** at each point

To cement understanding, derive a derivative *from first principles*:
- Example:  
  \( f(x) = x^2 \Rightarrow f'(x) = 2x \) via the limit definition

This shows **where differentiation rules come from**, not just how to apply them.

---

### Basic Differentiation Rules

#### Power Rule
\[
\frac{d}{dx}x^n = nx^{n-1}
\]

Examples:
- \( \frac{d}{dx}(x^5) = 5x^4 \)
- \( \frac{d}{dx}(1/x) = -1/x^2 \) (since \( x^{-1} \))

#### Constant & Coefficient Rules
- \( \frac{d}{dx}(c) = 0 \)
- \( \frac{d}{dx}[c f(x)] = c f'(x) \)

#### Sum / Difference Rule
- Derivative of a sum is the sum of derivatives
- Derivative of a difference is the difference of derivatives

---

### Product Rule

If \( u(x) \) and \( v(x) \) are functions:

\[
(uv)' = u'v + uv'
\]

Example:
- \( f(x) = x^2 \sin x \)

---

### Quotient Rule

\[
\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}, \quad v \neq 0
\]

Example:
- \( f(x) = \frac{x}{x^2 + 1} \)

Mnemonic:
> *“Low d-high minus high d-low over low-low”*

---

### Chain Rule

For composite functions:

\[
\frac{d}{dx} f(g(x)) = f'(g(x)) \cdot g'(x)
\]

Examples:
- \( \sin(x^2) \Rightarrow \cos(x^2)\cdot 2x \)
- \( e^{3x} \Rightarrow 3e^{3x} \)

This rule is **crucial for Calc II**, especially for integration via *u-substitution*.

---

### Derivatives of Common Functions

- \( (\sin x)' = \cos x \)
- \( (\cos x)' = -\sin x \)
- \( (\tan x)' = \sec^2 x \)
- \( (e^x)' = e^x \)
- \( (\ln x)' = \frac{1}{x} \)
- \( (a^x)' = a^x \ln a \)
- \( (\log_a x)' = \frac{1}{x \ln a} \)

These **must be memorized**.

---

## Practice Differentiation

### Example Tasks

- **Polynomial**  
  \[
  \frac{d}{dx}(x^3 + 5x - 4) = 3x^2 + 5
  \]

- **Product Rule**  
  \[
  h(x) = x^2 e^x \Rightarrow h'(x) = e^x(2x + x^2)
  \]

- **Quotient Rule**  
  \[
  k(x) = \frac{\sin x}{x} \Rightarrow k'(x) = \frac{x\cos x - \sin x}{x^2}
  \]

- **Chain Rule**  
  \[
  m(x) = (3x^2 + 1)^5 \Rightarrow m'(x) = 5(3x^2 + 1)^4 \cdot 6x
  \]

---

### Higher-Order Derivatives

- \( f''(x) \): second derivative  
- Interpretation:
  - Position → velocity → acceleration

Example:
- \( y = x^3 \)
- \( y' = 3x^2 \)
- \( y'' = 6x \)

---

## Using Derivatives

### Tangent Lines

Equation at \( x = a \):

\[
y - f(a) = f'(a)(x - a)
\]

Example:
- \( f(x) = x^2 \) at \( x = 1 \)
- Slope \( = 2 \)
- Line: \( y - 1 = 2(x - 1) \)

---

### Critical Points

- Occur when \( f'(x) = 0 \) or undefined
- Often correspond to maxima or minima
- Important in optimization and series endpoints

---

### Velocity & Acceleration

Example:
- \( s(t) = t^3 - 5t^2 \)
- \( v(t) = s'(t) \)
- \( a(t) = v'(t) \)

If:
- \( s(t) = t^2 \)
- \( v(t) = 2t \)
- \( a(t) = 2 \)

---

## Learning Resources

### Khan Academy – Basic Derivatives
- Derivative as slope of curve
- Power, product, quotient, and chain rules
- Excellent step-by-step practice

### Paul’s Online Math Notes – Calculus I
- Clear formula lists
- Extensive worked examples
- Includes **implicit differentiation**
  - Example:
    \[
    x^2 + y^2 = 25 \Rightarrow \frac{dy}{dx} = -\frac{x}{y}
    \]

### 3Blue1Brown – *Essence of Calculus*
- Chapters 2–3
- Visual intuition for derivatives
- Optional but excellent for conceptual depth

---

## Practice Set (Do ~10)

1. \( f(x) = 4x^3 - 3x + 7 \)
2. \( g(x) = \frac{5}{x^4} \)
3. \( h(x) = (2x^2 + 1)(x^3 - x) \)
4. \( p(x) = \frac{x^2 + 1}{x^3} \)
5. \( q(x) = (3x + 5)^7 \)
6. \( r(x) = \sin(4x) \), \( s(x) = \cos^3 x \)
7. \( t(x) = e^{2x^2} \)
8. Implicit: \( x^2 + y^2 = 25 \)
9. Log diff (optional):  
   \[
   y = x^x \Rightarrow y' = x^x(\ln x + 1)
   \]
10. Verify results using a CAS

Also:
- Find tangent lines
- Find critical points (e.g. \( f(x) = x^3 - 3x \))

---

## Why This Matters

Differentiation is **non-negotiable** for Calculus II.

You’ll use derivatives for:
- Taylor and power series
- Optimization problems
- Differential equations
- Parametric curves
- Integration (as reverse differentiation)

Example:
- Knowing \( \frac{d}{dx}(\tan^{-1}x) = \frac{1}{1+x^2} \)
- Makes \( \int \frac{1}{1+x^2}dx = \tan^{-1}x + C \) immediate

The stronger your differentiation skills, the easier **integration and series analysis** become.

**Accuracy first. Speed follows.**
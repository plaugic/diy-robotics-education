## Day 6: Exponential and Logarithmic Functions

### Focus
Today you will tackle exponentials and logarithms in depth. These functions feature prominently in Calculus (for example, \( e^x \) is its own derivative, and log functions often appear in integration results). A solid handle on their properties and algebra is essential. Calculus II especially involves exponential growth/decay models and logarithmic integrals, so we must not skip these core concepts.

---

### Topics to Master

#### 1. Exponential Functions
- Understand \( a^x \) for various bases \( a \).
- Special focus on base \( e \) (the natural exponential, \( e \approx 2.71828 \)) since \( e^x \) is ubiquitous in calculus.
- Know the general shape of \( y = a^x \):
  - Always positive
  - Growth if \( a > 1 \)
  - Decay if \( 0 < a < 1 \)
- Properties to know:
  - \( a^{m+n} = a^m a^n \)
  - \( a^{-k} = \frac{1}{a^k} \)
  - \( (a^m)^n = a^{mn} \)
- Practice simplifying expressions with exponents, including those with different bases  
  (e.g., compare growth of \( 2^x \) vs. \( 3^x \)).

#### 2. Logarithmic Functions
- Understand that \( \log_a x \) is the inverse of \( a^x \).
- In particular, the natural logarithm \( \ln x \) is the inverse of \( e^x \).
- Learn basic log properties:
  - \( \log(ab) = \log a + \log b \)
  - \( \log\!\left(\frac{a}{b}\right) = \log a - \log b \)
  - \( \log(a^r) = r \log a \)
- Key identities:
  - \( \ln(e^x) = x \)
  - \( e^{\ln x} = x \)
- Practice converting between exponential and logarithmic form:  
  \( a^b = c \iff \log_a c = b \).

#### 3. Laws of Exponents and Logs
- Work through examples using the laws:
  - Simplify: \( 5e^3 \cdot 2e^{-1} \)
  - Solve: \( 3^{x} = 17 \) (by taking logs)
- Practice expanding/condensing logs:
  - Example:
    \[
    \ln\!\left(\frac{x^5 \sqrt{y}}{z^2}\right)
    = 5\ln x + \tfrac{1}{2}\ln y - 2\ln z
    \]
- These manipulations are especially useful when integrating or differentiating log expressions.

#### 4. Solving Equations Involving Exponentials and Logs
- Exponential equations:
  - \( 2^{x} = 7 \Rightarrow x = \frac{\ln 7}{\ln 2} \)
  - \( e^{2x} = 5 \Rightarrow 2x = \ln 5,\; x = \tfrac{1}{2}\ln 5 \)
- Logarithmic equations:
  - \( \log_3(x) = 4 \Rightarrow x = 3^4 = 81 \)
  - \( \ln(2x - 1) = 3 \Rightarrow 2x - 1 = e^3 \)
- These skills are directly used when solving for time in growth/decay models or determining when an exponential function reaches a certain value.

#### 5. Applications Insight (Optional)
- Conceptual meanings:
  - \( e^x \): continuously compounded growth
  - \( \ln x \): area under \( 1/t \) from 1 to \( x \)
- Deep understanding isn’t required yet, but it’s helpful to know these connections exist.

---

### Learning Resources

- **Khan Academy – Exponentials & Logarithms**
  - Use the *Exponential growth & decay* and *Intro to logarithms* modules.
  - Complete exercises on converting forms, using log properties, and solving equations (e.g., solving \( 10^{3x} = 7 \)).
  - Take the quizzes to test fluency.

- **Paul’s Online Math Notes – Algebra Review: Exponentials and Logarithms**
  - Review *Basic Exponential Functions* and *Basic Logarithm Functions*.
  - Covers log properties and solving equations with concise examples.
  - Manipulating exponents and logs is assumed knowledge for calculus—be comfortable here.

- **Purplemath – Logarithms**
  - Excellent step-by-step explanations of *why* log rules work.
  - Strong for solving log equations and simplifying expressions, especially if logs feel rusty.

- **Interactive Visualization**
  - Use Desmos (or similar) to graph:
    - \( y = 2^x \), \( y = 3^x \), \( y = e^x \)
    - \( y = \ln x \)
  - Observe how \( \ln x \) is the mirror image of \( e^x \) across the line \( y = x \).

---

### Practice

- **Memorization & Verification**
  - Write out the three most important log identities and exponent rules from memory.
  - Verify numerically (e.g., check \( \ln(10) \) vs. \( \ln 2 + \ln 5 \)).

- **Simplification**
  - \( 3^{2x} \cdot 3^{-x} = 3^x \)
  - \( \frac{e^{4x}}{e^{x}} = e^{3x} \)
  - \( \log_{5}(25x) = 2 + \log_{5}x \)

- **Solve 5 Exponential and 5 Log Equations**

  **Exponential**
  1. \( 4^{x} = 50 \)
  2. \( e^{x} - 5 = 0 \)
  3. \( 10 \cdot 2^{3x} = 160 \)
  4. \( 5^{2x+1} = 125 \)
  5. \( e^{-x} = 7 \)

  **Logarithmic**
  1. \( \ln x = 2 \)
  2. \( \log_{3}(x) = -1 \)
  3. \( \ln(2x) = 4 \)
  4. \( \log_{10}(x + 1) = 2 \)
  5. \( 3 + \ln x = 5 \)

- Express solutions exactly when possible (e.g., \( x = \ln 7 \)) or as decimals if needed.
- Be clear on when to take logs vs. when to exponentiate.

- **Log Manipulation Practice**
  - Simplify:
    \[
    \frac{\ln(a^3 \sqrt{b})}{\ln(a b)}
    \]

- By the end of practice, manipulating and solving exponentials/logs should feel routine.  
  If not, do more problems—this material is foundational.

---

### Why This Matters
In Calculus II, you will constantly encounter \( e^x \) and \( \ln x \):

- \( \displaystyle \int \frac{1}{x}\,dx = \ln|x| + C \)
- Growth/decay models use \( e^{kt} \)
- Improper integrals often involve logarithms
- Series expansions like \( e^x \) and \( \ln(1+x) \) are common topics

If you are fluent with exponent and log rules, you can focus on calculus concepts instead of getting stuck on algebra. These functions are so fundamental that a calculus student must be completely comfortable with them. Aim to reach the point where seeing \( e^x \) or \( \ln x \) feels familiar—not intimidating.
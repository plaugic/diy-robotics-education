## Day 7: Trigonometry Essentials

### Focus
Trigonometry is often the topic that troubles Calculus students the most—yet it’s essential. Calculus II, in particular, delves into integrals of trig functions and techniques like **trigonometric substitution**. Today’s mission is to grasp the **core trig concepts**: the unit circle, fundamental trig functions (sine, cosine, etc.), basic identities, and simple trig equations.

Given the time crunch, we’ll prioritize what’s absolutely essential for calculus:
- Evaluating trig functions  
- Using identities to simplify expressions  
- Understanding trig function behavior  

---

## Topics to Master

### 1. Angles and the Unit Circle
- Understand **radians** (the standard measure in calculus) versus degrees.
- Know common angle measures:
  - Radians: \( 0, \frac{\pi}{6}, \frac{\pi}{4}, \frac{\pi}{3}, \frac{\pi}{2} \)
  - Degrees: \( 0^\circ, 30^\circ, 45^\circ, 60^\circ, 90^\circ \)
  - Continue through \( 120^\circ, 135^\circ, \dots, 360^\circ \) (or \( 2\pi \)).
- Be able to find **coordinates on the unit circle** for these angles.
  - Examples:
    - \( \sin(\pi/6) = \tfrac{1}{2} \)
    - \( \cos(\pi/3) = \tfrac{1}{2} \)
- Practice by drawing a unit circle and labeling sine and cosine values for key angles.
- Use an interactive unit circle to verify your memory.

---

### 2. Definition of Trig Functions
- For an angle \( \theta \) on the unit circle:
  - \( \cos\theta \) = *x-coordinate*
  - \( \sin\theta \) = *y-coordinate*
  - \( \tan\theta = \frac{\sin\theta}{\cos\theta} \)
- Know the basic shapes:
  - **Sine** starts at 0 and increases
  - **Cosine** starts at 1 when \( \theta = 0 \)
- Key values to recall:
  - \( \sin(0)=0 \), \( \cos(0)=1 \)
  - \( \sin(\pi/2)=1 \), \( \cos(\pi/2)=0 \)
- Understanding these helps evaluate **limits and integrals** involving trig.

---

### 3. Key Trigonometric Identities
- **Pythagorean Identity** (must-know):
  \[
  \sin^2\theta + \cos^2\theta = 1
  \]
  Rearrangements:
  \[
  \cos^2\theta = 1 - \sin^2\theta, \quad \sin^2\theta = 1 - \cos^2\theta
  \]

- **Co-function identities**:
  \[
  \sin\!\left(\tfrac{\pi}{2} - \theta\right) = \cos\theta
  \]

- **Even/Odd properties**:
  - \( \cos(-\theta) = \cos\theta \) (even)
  - \( \sin(-\theta) = -\sin\theta \) (odd)

- **Angle sum identities** (good to recognize):
  \[
  \sin(\alpha+\beta) = \sin\alpha\cos\beta + \cos\alpha\sin\beta
  \]

- **Double-angle formulas**:
  \[
  \sin(2x) = 2\sin x\cos x
  \]
  \[
  \cos(2x) = 1 - 2\sin^2 x
  \]
  Especially useful in Calc II:
  \[
  \cos^2 x = \frac{1+\cos(2x)}{2}
  \]

> At minimum, have **Pythagorean identities** and **double-angle formulas** available (memorized or easily accessible).

---

### 4. Evaluating Trig Expressions
Practice simplifying using identities:

- Example:
  \[
  \frac{\sin^2 x}{1-\cos^2 x} = 1
  \]
  (since \( 1-\cos^2 x = \sin^2 x \))

- Example:
  \[
  \cos^2 x - \sin^2 x = \cos(2x)
  \]

Comfort with these manipulations is critical for integration techniques.

---

### 5. Basic Trigonometric Equations
Solve simple equations on \( [0,2\pi) \):

- \( \sin\theta = \tfrac{\sqrt{2}}{2} \)
  - Solutions: \( \theta = \tfrac{\pi}{4}, \tfrac{3\pi}{4} \)

- \( \cos\theta = -\tfrac{1}{2} \)
  - Solutions: \( \theta = \tfrac{2\pi}{3}, \tfrac{4\pi}{3} \)

Understanding where trig functions take values is crucial in calculus (e.g., finding where derivatives equal zero).

---

### 6. Inverse Trigonometric Functions (If Time)
- Be aware of:
  - \( \arcsin x \), \( \arccos x \), \( \arctan x \)
- These are inverses with **restricted ranges**.
- Common calculus result:
  \[
  \int \frac{1}{\sqrt{1-x^2}}\,dx = \arcsin x + C
  \]
- Know:
  - \( \arcsin x \) gives an angle whose sine is \( x \)
  - \( \arctan x \in (-\tfrac{\pi}{2}, \tfrac{\pi}{2}) \)

---

## Learning Resources

### Khan Academy – Trigonometry
- Focus on:
  - *Unit circle definition of trig functions*
  - *Trigonometric identities*
  - *Graphs of* \( \sin x \) *and* \( \cos x \)
- Excellent for degree–radian conversion and identity practice.

### MathIsFun – Unit Circle Interactive
- Use the **Interactive Unit Circle** to explore angles and values.
- Reinforces quadrant signs and common values.
- Example check:
  - “What is \( \sin(150^\circ) \)?” → should be \( 0.5 \)

### Professor Leonard (Optional)
- Search: *“Professor Leonard Trigonometry crash course”*
- Very thorough; may be more than needed.
- Short summary videos (e.g. *“All Trig Identities in 10 Minutes”*) may be more efficient.

### Paul’s Online Math Notes – Trig Review
- Covers:
  - Evaluating trig functions
  - Trig identities
  - Solving trig equations
  - Inverse trig
- Excellent reference to bookmark for calculus.

---

## Practice

### Unit Circle Recall
- Draw a blank unit circle.
- Fill in:
  - Angles (multiples of \( \pi/6, \pi/4, \pi/3 \))
  - Coordinates \( (\cos\theta, \sin\theta) \)
- Check and repeat until confident.

### Identity Usage
Do 5 quick simplifications/verifications:
- Prove:
  \[
  \frac{1-\cos(2x)}{2} = \sin^2 x
  \]
- Simplify:
  \[
  \frac{\sin x \cos x}{\sin^2 x}
  \]
- Verify:
  \[
  \tan^2 x + 1 = \sec^2 x
  \]

### Evaluate Trig Values (No Calculator)
- \( \sin 300^\circ \)
- \( \cos\!\left(\tfrac{5\pi}{6}\right) \)
- \( \tan\!\left(\tfrac{\pi}{4}\right) \)
- Negative angles:
  - \( \sin(-\tfrac{\pi}{3}) \)
  - \( \cos(-\tfrac{\pi}{3}) \)

### Solve Trig Equations
- \( \sin x = 0 \), \( x \in [0,2\pi) \)
  - \( x = 0, \pi, 2\pi \)
- \( \cos x = \tfrac{\sqrt{2}}{2} \), \( x \in [0,2\pi) \)
  - \( x = \tfrac{\pi}{4}, \tfrac{7\pi}{4} \)
- \( \tan x = \sqrt{3} \), \( x \in [0,\pi) \)
  - \( x = \tfrac{\pi}{3} \)
  - General solution: \( x = \tfrac{\pi}{3} + k\pi \)

### Inverse Trig (If Done)
- \( \arcsin(\tfrac{1}{2}) = \tfrac{\pi}{6} \)
- \( \arctan(1) = \tfrac{\pi}{4} \)

> Trig is dense—prioritize **unit circle values** and **Pythagorean + double-angle identities**. It’s okay to look up less common identities; the essentials should be second nature.

---

## Why This Matters
In Calculus II, trig appears everywhere:

- Integrals like:
  \[
  \int \sin^2 x\,dx, \quad \int \frac{dx}{1+x^2} = \arctan x
  \]
- **Trig substitution** relies on identities like:
  \[
  1 - \sin^2\theta = \cos^2\theta
  \]
- Weak trig knowledge is a major reason students struggle with Calc II.

By solidifying trig now, you set yourself up to handle integration techniques, inverse trig results, and periodic behavior in series. Trigonometry is to **Calculus II** what algebra was to **Calculus I**: absolutely required background.

After today, keep a **unit circle + identities sheet** handy. You’ll reference it often—until it becomes second nature.
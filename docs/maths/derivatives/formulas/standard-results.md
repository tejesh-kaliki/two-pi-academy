---
title: Standard Results
description: Derivatives of some standard functions, and algebraic rules
---

# Standard results for derivatives

## Algebraic derivative rules

**Constant Multiple Rule:**
$\frac{d}{dx}(c \cdot f(x)) = c \cdot \frac{d}{dx}(f(x))$

**Sum Rule:**
$(u + v)' = u' + v'$

**Difference Rule:**
$(u - v)' = u' - v'$

**Product Rule:**
$(uv)' = u'v + uv'$

**Quotient Rule:**

$$\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$$

**Chain Rule:**

If $y = f(u)$ and $u = g(x)$, then

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

Alternatively, if $h(x) = f(g(x))$, then

$$h'(x) = f'(g(x)) \cdot g'(x)$$

## Standard derivatives

### Constant rule

$$\frac{d}{dx}(c) = 0$$

### Power rule

$$\frac{d}{dx}(x^n) = nx^{n-1}$$

### Trigonometric functions

$$
\begin{align*}
& \frac{d}{dx}(\sin x) = \cos x \\
& \frac{d}{dx}(\cos x) = -\sin x \\
& \frac{d}{dx}(\tan x) = \sec^2 x \\
& \frac{d}{dx}(\csc x) = -\csc x \cot x \\
& \frac{d}{dx}(\sec x) = \sec x \tan x \\
& \frac{d}{dx}(\cot x) = -\csc^2 x
\end{align*}
$$

### Inverse trigonometric functions

$$
\begin{align*}
& \frac{d}{dx}(\sin^{-1} x) = \frac{1}{\sqrt{1 - x^2}} \\
& \frac{d}{dx}(\cos^{-1} x) = -\frac{1}{\sqrt{1 - x^2}} \\
& \frac{d}{dx}(\tan^{-1} x) = \frac{1}{1 + x^2} \\
& \frac{d}{dx}(\csc^{-1} x) = -\frac{1}{|x|\sqrt{x^2 - 1}} \\
& \frac{d}{dx}(\sec^{-1} x) = \frac{1}{|x|\sqrt{x^2 - 1}} \\
& \frac{d}{dx}(\cot^{-1} x) = -\frac{1}{1 + x^2}
\end{align*}
$$

### Exponential and logarithmic functions

$$
\begin{align*}
& \frac{d}{dx}(e^x) = e^x \\
& \frac{d}{dx}(a^x) = a^x \ln a \\
& \frac{d}{dx}(\ln x) = \frac{1}{x}, x > 0 \\
& \frac{d}{dx}(\log_a x) = \frac{1}{x \ln a}, x > 0
\end{align*}
$$

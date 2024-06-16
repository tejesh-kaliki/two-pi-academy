---
title: Arithmetic Operations
description: Arithmetic Operations on Complex Numbers.
---

# Arithmetic operations

## Basics of complex numbers

The main idea behind complex numbers is the square root of a negative number.

In real numbers, negative numbers can't have a square root. Hence, complex numbers denote a special number, $i=\sqrt{-1}$.

**Complex number**: a complex number is of the form $z=a+ib$.

Where,

- $a$ - Real part ($\text{Re}\,z$)
- $b$ - Imaginary part ($\text{Im}\,z$)

## Addition of complex numbers
Let $z_1=a+ib$ and $z_2=c+id$ be two complex numbers. Then,
$$ z_1+z_2=(a+c)+i(b+d)$$

???+ tip
    To add 2 complex numbers, add the real parts and the imaginary parts.

    - $\text{Re}\,(z_1+z_2) = \text{Re}\,z_1+\text{Re}\,z_2$
    - $\text{Im}\,(z_1+z_2) = \text{Im}\,z_1+\text{Im}\,z_2$

### Properties:
1. **Closure law**: If $z_1$ and $z_2$ are complex numbers, then $z_1+z_2$ is also a complex number.
2. **Commutative law**: $z_1+z_2=z_2+z_1$
3. **Associative law**: $(z_1+z_2)+z_3=z_1+(z_2+z_3)$
4. **Existence of additive identity**: $0+i0$, or simply $0$, is the _additive identity_ or _zero_ complex number. $[z+0=z]$
5. **Existence of additive inverse**: If $z=a+ib$, then $-z=-a+i(-b)$ is the _additive inverse_ or _negative_ of $z$. $[z+(-z)=(-z)+z=0]$

## Difference of complex numbers:
Let $z_1=a+ib$ and $z_2=c+id$ be two complex numbers. Then,
$$ z_1-z_2=(a-c)+i(b-d)$$

!!! info
    This is also considered as $z_1-z_2=z_1+(-z_2)$. (Sum of $z_1$ and negative of $z_2$)

???+ tip
    To subtract 2 complex numbers, subtract the real parts and the imaginary parts.

    - $\text{Re}\,(z_1-z_2) = \text{Re}\,z_1-\text{Re}\,z_2$
    - $\text{Im}\,(z_1-z_2) = \text{Im}\,z_1-\text{Im}\,z_2$

## Multiplication of complex numbers:
Let $z_1=a+ib$ and $z_2=c+id$ be two complex numbers. Then,
$$ z_1\,z_2=(ac-bd)+i(ad-bc)$$

???+ tip
    You can get this by simply expanding the product.

    $$
    \begin{aligned}
        z_1 z_2 &= (a+ib)(c+id) \\
                &= ac + a(id) + (ib)c + (ib)(id) &\\
                &= ac + i(ad) + i(bc) + i^2(bd)  &\\
                &= ac + i(ad + bc) - bd \quad &[\because i^2 = -1]\\
                &= (ac - bd) + i(ad + bc)
    \end{aligned}
    $$

### Properties:
1. **Closure law**: If $z_1$ and $z_2$ are complex numbers, then $z_1\,z_2$ is also a complex number.
2. **Commutative law**: $z_1\,z_2=z_2\,z_1$
3. **Associative law**: $(z_1\,z_2)\,z_3=z_1\,(z_2\,z_3)$
4. **Existence of multiplicative identity**: $1+i0$, or simply $1$, is the _multiplicative identity_. $[z.1=z]$
5. **Existence of multiplicative inverse**: If $z=a+ib$, then $z^{-1}$ or $\frac{1}{z}$ is the _multiplicative inverse_ of $z$. $[z.z^{-1}=1]$
6. **Distributive law**:
    1. $z_1\,(z_2+z_3) = z_1\,z_2+z_1\,z_3$
    1. $(z_1+z_2)\,z_3 = z_1\,z_3+z_2\,z_3$

### Finding multiplicative inverse:
Let $z=a+ib$ is a complex number, then it's inverse is

$$z^{-1}=\frac{a}{a^2+b^2}+i\frac{-b}{a^2+b^2}$$

## Division of complex numbers:
Let $z_1$ and $z_2$ be two complex numbers. Then, to find $\frac{z_1}{z_2}$,

- **Step 1**: Find $z_2^{-1}$.
- **Step 2**: Multiply $z_1$ by $z_2^{-1}$.

## Powers of $i$:
Let $k$ be an integer, then the powers of $i$ are:

- $i^{4k+1}=i^5=i^{-3}=i$
- $i^{4k+2}=i^2=i^{-2}=-1$
- $i^{4k+3}=i^3=i^{-1}=-i$
- $i^{4k}=i^0=i^4=i^{-4}=1$

## Identities:
The following identities from read numbers can also be used for complex numbers.

1. $(z_1+z_2)^2=z_1^2+z_2^2+2\,z_1\,z_2$
1. $(z_1-z_2)^2=z_1^2+z_2^2-2\,z_1\,z_2$
1. $(z_1+z_2)^3=z_1^3+3\,z_1^2\,z_2+3\,z_1\,z_2^2+z_2^3$
1. $(z_1-z_2)^3=z_1^3 - 3\,z_1^2\,z_2 + 3\,z_1\,z_2^2 - z_2^3$
1. $z_1^2-z_2^2=(z_1+z_2)(z_1-z_2)$
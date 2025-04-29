# LCM and HCF

## What is LCM?

- **LCM (Least Common Multiple)** of two or more numbers is the smallest number that is exactly divisible by each of the numbers.
- LCM is only defined for **positive integers**.

**Example:**
- Multiples of 10: 10, 20, 30, 40, 50, 60...
- Multiples of 15: 15, 30, 45, 60...
- Multiples of 20: 20, 40, 60, 80...
- The smallest common multiple = **60**.

Thus, **LCM(10, 15, 20) = 60**.

---

## Process to Find LCM

### Method-1: Prime Factorization

1. Factorize all numbers into their **prime factors**.
2. Collect **all distinct prime factors**.
3. Take each prime factor with its **highest power**.
4. Multiply them together to get the LCM.

**Example:**
- Find LCM of 18 and 42.

Step 1:  
18 = 2 × 3²  
42 = 2 × 3 × 7

Step 2:  
Distinct primes: 2, 3, 7

Step 3:  
Highest powers: 2¹, 3², 7¹

Thus,  
LCM(18, 42) = 2¹ × 3² × 7¹ = **126**

---

### Method-2: Shortcut by Division

- Write numbers side by side.
- Divide by common prime numbers step-by-step.
- Stop when only 1s remain.
- Multiply all divisors to get the LCM.

---

## What is HCF (or GCD)?

- **HCF (Highest Common Factor)**, also called **GCD (Greatest Common Divisor)**, is the largest number that divides all given numbers exactly.

**Example:**
- HCF of 18 and 42 = **6**

---

## Process to Find HCF

### Method-1: Prime Factorization

1. Factorize each number into **prime factors**.
2. Identify **common prime factors**.
3. Multiply the common prime factors to get the HCF.

**Example:**
- 18 = 2 × 3²  
- 42 = 2 × 3 × 7  

Common factors: 2, 3  
Thus,  
HCF(18, 42) = 2 × 3 = **6**

---

### Method-2: Division Method

1. Divide the larger number by the smaller.
2. Divide the divisor by the remainder.
3. Repeat until remainder is 0.
4. The last non-zero divisor is the HCF.

**Example:**
Find HCF of 18 and 42:

```
42 ÷ 18 = 2 remainder 6  
18 ÷ 6 = 3 remainder 0
```

Thus, HCF(18, 42) = **6**

---

## Important Properties

- **Product of two numbers = HCF × LCM**

**Example:**
- If HCF = 6, LCM = 5040, and one number = 210, then:
  
  Product = HCF × LCM = 6 × 5040 = 30240  
  Other number = 30240 ÷ 210 = **144**

---

## Special Notes

- LCM and HCF are **not defined for negative numbers**.
- If HCF of x and y = H, then:
  - HCF(x, x + y) = H
  - HCF(x, x - y) = H
  - HCF(x + y, x - y) = H

---

## LCM and HCF of Fractions

- **LCM of Fractions** = (LCM of Numerators) ÷ (HCF of Denominators)
- **HCF of Fractions** = (HCF of Numerators) ÷ (LCM of Denominators)

**Example:**
- Find LCM and HCF of 1/2, 2/5, 4/7

Step 1:
- Numerators: 1, 2, 4
- Denominators: 2, 5, 7

Step 2:
- LCM of Numerators = 4
- HCF of Denominators = 1

Thus,
- LCM of fractions = 4 ÷ 1 = **4**

Similarly,
- HCF of Numerators = 1
- LCM of Denominators = 70

Thus,
- HCF of fractions = 1 ÷ 70 = **1/70**

---

## Applications of LCM

- **Finding when events happen together** (bells ringing together, racers meeting at starting point).

**Example:**
- Bells ringing every 12s, 18s, 24s, 36s, 45s.
- Find when they ring together:

LCM(12, 18, 24, 36, 45) = **360 seconds**  
(= 6 minutes)

Thus, they will ring together again after **6 minutes**.

---

## Applications of HCF

- **Finding largest tile size** that can cover a floor without cutting.
- **Finding largest number** dividing given numbers leaving same remainders.

**Example:**
- Dimensions: 360 cm × 540 cm

Find HCF(360, 540):

360 = 2 × 2 × 2 × 3 × 3 × 5  
540 = 2 × 2 × 3 × 3 × 3 × 5

Common factors: 2² × 3² × 5 = 180

Thus, the largest square tile = **180 cm × 180 cm**

---

## Summary

- **LCM**: Smallest common multiple.
- **HCF**: Largest common divisor.
- **Formula**: Product of numbers = HCF × LCM.
- **Use** prime factorization or division methods.
- **Application**: Time, tiling, problems with remainders.

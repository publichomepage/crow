# Digital Sum

## What is Digital Sum?

- A **Digital Sum** is the single digit obtained by adding all digits of a number repeatedly until a single digit remains.
- Alternatively, it is the **remainder** when the number is divided by 9.

**Examples:**
- 135 → 1 + 3 + 5 = **9**
- 68 → 6 + 8 = 14 → 1 + 4 = **5**
- 34 → 3 + 4 = **7** (or remainder when 34 ÷ 9)

---

## Key Rules of Digital Sum

### 1. Basic Properties

- Digital sum can be any of **0, 1, 2, 3, 4, 5, 6, 7, 8, 9**.
- In digital sum calculation, **9 is considered as 0**.
- Digits or groups adding up to 9 can be **eliminated** without affecting the result.

**Examples:**
- 2467539 → 2 + 4 + 6 + 7 + 5 + 3 + 9 = 36 → 3 + 6 = **9**  
  Shortcut: eliminate 9, (2+7), (4+5), (6+3) → left with 0 → Digital sum = **9**
- 6372819923 → eliminate (6+3), (7+2), (8+1), two 9s → left with 2+3 → **5**

---

### 2. Important Observations

- **Multiples of 9** always have a digital sum of **9**.
- Adding or removing **9** does **not** change the digital sum.

**Examples:**
- 9 × 14 = 126 → 1 + 2 + 6 = **9**
- 9 × 43 = 387 → 3 + 8 + 7 = 18 → 1 + 8 = **9**

---

### 3. Digital Sum in Arithmetic Operations

#### a) Addition

- The digital sum of a sum equals the digital sum of the individual digital sums.

**Examples:**
- 13 + 12 = 25  
  - DS(13) = 4, DS(12) = 3 → 4 + 3 = 7  
  - DS(25) = 2 + 5 = 7 ✅

---

#### b) Subtraction

- Subtract the digital sums.
- If negative, **add 9** to correct it.

**Examples:**
- 88 – 13 = 75  
  - DS(88) = 8 + 8 = 16 → 1 + 6 = 7  
  - DS(13) = 1 + 3 = 4  
  - 7 – 4 = 3  
  - DS(75) = 7 + 5 = 12 → 1 + 2 = 3 ✅

- 73 – 16 = 57  
  - DS(73) = 7 + 3 = 10 → 1 + 0 = 1  
  - DS(16) = 1 + 6 = 7  
  - 1 – 7 = -6 → -6 + 9 = 3  
  - DS(57) = 5 + 7 = 12 → 1 + 2 = 3 ✅

---

#### c) Multiplication

- Multiply the digital sums.
- Then take the digital sum of the product.

**Examples:**
- 15 × 13 = 195  
  - DS(15) = 6, DS(13) = 4  
  - 6 × 4 = 24 → DS(24) = 2 + 4 = 6  
  - DS(195) = 1 + 9 + 5 = 15 → 1 + 5 = 6 ✅

---

#### d) Division

- Division rules require caution:
  - If the divisor's digital sum is **3, 6, or 9**, special handling is needed.
  - Otherwise, match division results carefully.

**Examples:**
- 1092 ÷ 156  
  - DS(1092) = 1 + 0 + 9 + 2 = 12 → 1 + 2 = 3  
  - DS(156) = 1 + 5 + 6 = 12 → 1 + 2 = 3  
  - 3 ÷ 3 = 1  
  - (Special handling needed because divisor is 3.)

---

### 4. Special Cases

#### a) Decimals

- Decimal points are **ignored** in Digital Sum calculations.

**Examples:**
- DS(6.256) = 6 + 2 + 5 + 6 = 19 → 1 + 9 = 10 → 1 + 0 = **1**

---

#### b) Perfect Squares

- A number **cannot** be a perfect square unless its digital sum is **1, 4, 7, or 9**.

**Examples:**
- 529 → 5 + 2 + 9 = 16 → 1 + 6 = **7** ✅
- 5768 → 5 + 7 + 6 + 8 = 26 → 2 + 6 = **8** ❌ (not a perfect square)

---

#### c) Perfect Cubes

- Cube root's digital sum cubed must match cube's digital sum.

**Examples:**
- 13³ = 2197  
  - DS(13) = 1 + 3 = 4  
  - 4 × 4 × 4 = 64 → 6 + 4 = 10 → 1 + 0 = **1**  
  - DS(2197) = 2 + 1 + 9 + 7 = 19 → 1 + 9 = 10 → 1 + 0 = **1** ✅

---

## Summary

- **Use** Digital Sum to quickly verify addition, subtraction, multiplication, and division.
- **Eliminate options** in multiple choice exams easily.
- **Remember** to treat **9 as 0** and eliminate **pairs adding up to 9** for faster calculations.

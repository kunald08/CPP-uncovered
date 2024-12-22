# Number System

## Introduction
- Computers work on the **binary system** (0 and 1, or ON and OFF), while humans understand the **decimal number system**.
- Instructions, data, or messages for computers are coded in binary.
- **Conversions between number systems** are essential for programming and computer science.

---

## Number Systems Overview
| **Number System** | **Base** | **Symbols**           |
|--------------------|----------|-----------------------|
| Decimal            | 10       | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 |
| Binary             | 2        | 0, 1                 |
| Octal              | 8        | 0, 1, 2, 3, 4, 5, 6, 7 |
| Hexadecimal        | 16       | 0-9, A (10) to F (15) |

---

## Binary Number System
- Binary has **only two symbols**: 0 and 1.
- When symbols are exhausted, combinations are used:
  - Decimal 10 = Binary 1 0.
  - Do not read binary as "ten" but as "1 0" in binary.

### Binary Representation (Decimal to Binary)
| Decimal | Binary    |
|---------|-----------|
| 0       | 0         |
| 1       | 1         |
| 2       | 1 0       |
| 3       | 1 1       |
| 4       | 1 0 0     |
| 5       | 1 0 1     |

---

## Octal and Hexadecimal
- **Octal System**: Groups **3 binary digits** into one octal digit.
- **Hexadecimal System**: Groups **4 binary digits** into one hex digit (16 symbols: 0-9, A-F).
- Hexadecimal examples:
  - 10 in Decimal = A in Hexadecimal.
  - 15 in Decimal = F in Hexadecimal.

---

## Conversion Techniques

### Decimal to Binary Conversion
1. Divide the decimal number by 2 repeatedly.
2. Record the remainders.
3. Read the remainders **bottom to top**.

**Example: Convert 25 to Binary**
- 25 ÷ 2 = 12 remainder 1  
- 12 ÷ 2 = 6 remainder 0  
- 6 ÷ 2 = 3 remainder 0  
- 3 ÷ 2 = 1 remainder 1  
- 1 ÷ 2 = 0 remainder 1  
- **Result**: Binary = `1 1 0 0 1`.

### Binary to Decimal Conversion
1. Write the binary number in columns, assigning powers of 2 from right to left.
2. Multiply each binary digit by its corresponding power of 2.
3. Add the results.

**Example: Convert Binary `1 1 0 0 1` to Decimal**
- `1 × 2^4 + 1 × 2^3 + 0 × 2^2 + 0 × 2^1 + 1 × 2^0`
- `16 + 8 + 0 + 0 + 1 = 25`
- **Result**: Decimal = `25`.

---

## Summary
- The binary system is fundamental to computer operations.
- **Conversions between systems** (e.g., decimal to binary, binary to decimal) are essential skills.
- Octal and hexadecimal simplify the representation of large binary numbers.
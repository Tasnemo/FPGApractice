# Lab 2 –


# FPGA Truth Tables and SOP (lab2.bit uploaded into a Basys-3)

## LED7 

| sw7 (A) | sw3 (B) | LED7 |
|---|---|---|
| L | L | 0 |
| L | H | 1 |
| H | L | 1 |
| H | H | 1 |

**LED7 = A + B**

---

## LED6

| sw6 | sw3 | LED6 |
|---|---|---|
| L | L | 0 |
| L | H | 1 |
| H | L | 1 |
| H | H | 0  |

**LED6 = (A * B + A' * B')'**

---

## LED4

| sw3 | sw2 | LED4 |
|---|---|---|
| L | L | 0 |
| L | H | 0 |
| H | L | 1 |
| H | H | 1  |

**LED4 = A **

---

## LED1

| sw7 | sw0 | LED1 |
|---|---|---|
| L | L | 0  |
| L | H | 1 |
| H | L | 1 |
| H | H | 0 |

**LED1 = (A * B + A' * B')'**

---

## LED2

| sw2 | sw0 | LED2 |
|---|---|---|
| L | L | 0 |
| L | H | 0 |
| H | L | 0 |
| H | H | 1 |

**LED2 =  A*B **

---

## LED5

| sw7 | sw6 | sw5 | LED5 |
|---|---|---|---|
| L | L | L | 0 |
| L | L | H | 0 |
| L | H | L | 0 |
| L | H | H | 1 |
| H | L | L | 1 |
| H | L | H | 1 |
| H | H | L | 1 |
| H | H | H | 1 |

**LED5 = A + (B * C) **

---

## LED3

| sw4 | sw3 | sw1 | LED3 |
|---|---|---|---|
| L | L | L | 0 |
| L | L | H | 0 |
| L | H | L | 0 |
| L | H | H | 0 |
| H | L | L | 0 |
| H | L | H | 1 |
| H | H | L | 0 |
| H | H | H | 1 |

**LED3 = A * C **

---

## LED0

| sw2 | sw1 | sw0 | LED0 |
|---|---|---|---|
| L | L | L | 1 |
| L | L | H | 1 |
| L | H | L | 1 |
| L | H | H | 0 |
| H | L | L | 1 |
| H | L | H | 0 |
| H | H | L | 1 |
| H | H | H | 1 |

**LED0 = C' + AB + A'B'


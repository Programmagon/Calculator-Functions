# Number Guessing Game

### 1. Preparation (Calculation Mode)
* Generate number: `RanInt#(1; 100)` `=`
* Store while sceen is covered: `STO` → `A` (Taste `(-)`)
* Clear sceen: `AC`

---

### 2. Enter function (Table Mode)
* Switch to `table mode` (`MENU` `5`).
* Enter game function:

  $f(x) = \frac{x - A}{|x - A|}$

---

### 3. Result

| Display | Meaning | State |
| :---: | :--- | :--- |
| **`-1`** |  too **small** ($x < A$) | Your number must be bigger |
| **`1`** | too **big** ($x > A$) | Your number must be smaller  |
| **`ERROR`** *(division through 0)* | You are **on** the number ($x = A$) | **You found it! 🎉** |

# 🎯 Taschenrechner-Einzelspiel: Das Signum-Rätsel

### 1. Vorbereitung (Calculation Mode)
* Generiere die Zahl: `RanInt#(1, 100)` `=`
* Speichere sie verdeckt: `STO` → `A` (Taste `(-)`)
* Lösche das Display: `AC`

---

### 2. Formel im Tabellenmodus eingeben (Table Mode)
* Wechsle in den Tabellenmodus (`MENU` `5`).
* Gib die Indikator-Funktion ein:

  $$f(x) = \frac{x - A}{|x - A|}$$

---

### 3. Auswertung der Anzeige

| Display | Bedeutung | Zustand |
| :---: | :--- | :--- |
| **`-1`** | Du bist **unter** der Zahl ($x < A$) | Zu klein geraten |
| **`1`** | Du bist **über** der Zahl ($x > A$) | Zu groß geraten |
| **`ERROR`** *(Division durch 0)* | Du bist **auf** der Zahl ($x = A$) | **Treffer! 🎉** |

# (In)dependent columns in 3 by 3 matrix

Erster Lösungsweg:

Wir wählen die zwei Spalten ohne x beliebig, sodass sie keine Vielfache voneinander sind (zB. (1,1,1)^T, (2,1,1)^T. Die beiden Spalten alleine sind linear unabhängig). Wir schreiben dann die Spalte mit x als Linearkombination der ersten beiden. Jetzt müssen wir die übrigen Einträge so wählen, dass sich die Spalte mit x nicht als Linearkombination der anderen beiden darstellen lässt. Dafür wählen wir für Werte, die das einfach unmöglich machen (wir können für jede Zeile eine Gleichung aufstellen). Da in diesem Fall der zweite und dritte Eintrag von den Vektoren, die wir schon gewählt haben, einfach 1 ist, reicht es aus, für die übrigen Unbekannten irgendwelche verschiedenen Werte zu wählen, zB. 1 und 2.

Zweiter Lösungsweg mit Gauss Elimination:

Wir wollen, dass die Spalten der Matrix alle linear unabhängig sind, wir also eine Matrix mit Rang 3 haben. Zuerst wählen wir die zwei Reihen ohne x so, dass mit Zeilenoperationen aus einer Spalte (0,1,0) machen können (bzw. einen Zeilenvektor, der genau in der Spalte 1 ist, in der x sich befindet), um x eliminieren zu können (zB. (1,1,1) und (1,2,1) - die erste subtrahiert von der zweiten ergibt (0,1,0). die Zeile können wir dann x mal von der Zeile mit x subtrahieren). Die restlichen Variablen können wir jetzt beliebig wählen, sodass der Rang 3 ist, zB. (2,x,1).
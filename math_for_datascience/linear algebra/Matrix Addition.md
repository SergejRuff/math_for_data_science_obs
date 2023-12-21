
-> Man kann Matrix A und Matrix B nur zusammen addieren, wenn Sie dieselbe Dimensionen (!) haben
> Müssen beide dieselbe Form besitzen
> ![[Pasted image 20231221211751.png]]
> In der Abbildung sieht man, dass beide dieselbe Form haben (mxn)

![[Pasted image 20231221212008.png]]
Bei der Matrizenaddition weisen alle beteiligten Matrizen die gleiche Spalten- und Zeilenzahl auf.
> Auch das Ergebnis (die Output-Matrix) hat dieselbe Form wie die zwei ürsprünglichen Matrizen
Errormeldung in R: "non-conformable arrays", wenn man versucht Matrizen mit ungleichen Dimensionen zu addieren.

![[Pasted image 20231221212203.png]]
Addition erfolgt, indem man Elementenweise Addition der entsprechenden Elemente der beiden ursprünglichen Matrizen. Siehe Abbildung.
Das erste Element der ersten Spalte von Matrix A(A1,1) wird mit dem ersten Element der ersten Spalte von matrix B (b1,1) addiert. A2,2 wird mit B2,2 addiert, A3,3 mit B3,3 und so weiter.
> Gleiche Zellen werden zusammenaddiert. Deshalb funktioniert es nicht, wenn die zwei Matrizen unterschiedliche Dimensionen besitzen.

> Reihenfolge der Addition ist egal bei der Addition. Es ist egal, ob man A+B oder B+A addiert.
>  Das ist nicht der Fall bei den [[Multiplikationen von Matrizen]]


Beispiel: https://www.youtube.com/watch?v=WR9qCSXJlyY&t=275s

![[Pasted image 20231221212503.png]]
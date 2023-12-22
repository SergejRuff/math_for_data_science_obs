
Man kann viele Vektor Operationen durchführen:
Man kann [[Vektoren addieren]]


Kurz gesagt ist ein Vektor ein Pfeil im Raum mit einer bestimmten Richtung und Länge, der oft ein Stück Daten repräsentiert. 
> Repräsentiert Daten
> Pfeil mit Richtung und Länge
> Kann damit Richtung und Länge im Raum ausdrücken.


Vektoren sind grundlegende Bausteine der linearen Algebra, zu der Matrizen und lineare Transformationen gehören. Im einfachsten Fall beginnt der Vektor immer am Ursprung eines kartesischen Koordinatensystems (0,0) und hat keine feste Position.
> Das Fundament für Lineares Algebra
> Matrizen sind im Grunde genommen eine Sammlung von Vektoren


Frage: Wie verstehen Data Scientists Vektoren?
In computer science, it is an array of numbers storing
data. The computer science context is the one we will become the most familiar with
as data science professionals.

![[Pasted image 20231222204630.png]]

	Wichtig: Jeder Datenpunkt kann auch als ein Vektor dargestellt werden. In der Abbildung haben wir zum Beispiel Datenpunkte in einem Scatterplot. Man kann aber jeden Punkt aber auch als Vektor darstellen, dessen Start der Ursprung (0,0) ist und bei der Koordinate (X,Y) endet.In der Abbildung sehen wir, dass der rote Pfeil (der Vektor) bei 0 anfängt und zum Datenpunkt führt.
> Alle Daten in DS lassen sich als Vektoren abbilden!

ACHTUNG:
However, it is important we never forget the visual
aspect so we do not think of vectors as esoteric grids of numbers. Without a visual
understanding, it is almost impossible to grasp many fundamental linear algebra
concepts like linear dependence and determinants.

![[Pasted image 20231221230151.png]]
Abbildung zeigt einen simplen Vektor v, der drei Schritte horizontal und drei schritte vertikal geht.

Achtung: Vektoren sind eine Repräsentation von Daten.
Zitat aus Essential Math for Data Science: "the purpose of the vector is to visually represent a piece of data.If you have a data record for the square footage of a house 18,000 square feet andits valuation $260,000, we could express that as a vector [18000, 2600000], stepping 18,000 steps in the horizontal direction and 260,000 steps in the vertical direction."


![[Pasted image 20231221230329.png]]
![[Pasted image 20231221230854.png]]
Es kann aber auch viel mehr als 3 Dimensionen haben.

Frage: Welche packages in python gibt es für lineares Algebra und Vektor Manipulation.
Für Vektor Operationen in Python sollte man Numpy nutzen, da es besser und effizienter ist als Basic Python.
Sympy ist ein anderes packet für lineares Algebra.
Python’s numeric and scientific libraries are not slow. Libraries like NumPy
are typically written in low-level languages like C and C++, hence
why they are computationally efficient. Python really acts as “glue
code” integrating these libraries for your tasks.



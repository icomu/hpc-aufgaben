# hpc-aufgaben
Aufgaben der Vorlesung High Performance Computing 2018

<hr>

#### Branches

In den Branches finden sich verschiedene Lösungsansätze, die mehr oder weniger weit ausgebaut sind.
Der Name gibt in etwa vor, bei welcher Aufgabe der Branch Relevanz hat.

###### gol_parallelfor

AB2 umgesetzt mit omp_parallel_for. Entspricht nicht unbedingt dem gewünschten Ergebnis,
da keine eigenen Dateien für jeden Thread geschrieben werden, funktioniert aber an sich sehr gut.

###### gol_sectionsplitting

AB2 umgesetzt mit omp_section. Je nach Auslegung des Arbeitsblattes eine mögliche Lösung.
Keine Möglichkeit der flexiblen Threadanzahl (immer 4), dafür aber mit Ausgabe.
Branch geschlossen, findet sich im Master-Gol.
git merge
Une dos ramas creando un nuevo commit de merge.
No reescribe el historial, lo conserva tal cual ocurrió.

git rebase
“Reaplica” los commits de una rama sobre otra.
Reescribe el historial, creando nuevos commits con distinto hash.

Usaría rebase cuando:
Estoy trabajando en una rama local (feature) que solo uso yo.
Quiero limpiar el historial antes de integrarlo.

Usaría merge cuando:
Estoy integrando cambios en una rama compartida (por ejemplo, main o develop).
Quiero preservar el contexto real del desarrollo.

No usaria rebase porque:
Reescribe el historial (cambia los hashes de los commits).
Si ya hiciste push, otras personas pueden tener la versión antigua.
Esto provoca:
Conflictos innecesarios
Duplicación de commits
Historial inconsistente o confuso

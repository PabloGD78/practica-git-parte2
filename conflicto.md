# Resolución de conflicto en Git

Durante el merge de la rama `feature-conflicto` en `main` se detectó un conflicto en el archivo `notas.md`.

- En la rama `main`: la línea era "Música (versión desde main)".
- En la rama `feature-conflicto`: la línea era "Música (versión desde feature-conflicto)".
- Resolución: se editó manualmente el archivo dejando una versión combinada:
  "Música (versión combinada: main + feature-conflicto)".

Se marcó el conflicto como resuelto con:
git add notas.md
git commit -m "fix: resuelve conflicto en notas.md"

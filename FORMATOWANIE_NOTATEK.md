# Formatowanie rozwiązań i notatek

Celem tych zasad jest to, aby pliki Markdown były czytelne zarówno w surowym tekście, jak i po wyrenderowaniu bezpośrednio na GitHubie.

## Zasady

1. **Wzory w tekście** zapisuj między pojedynczymi znakami dolara, np. `$f(x)=x^2+1$`.
2. **Osobne wzory blokowe** zapisuj jako blok matematyczny GitHuba:

   ```math
   \int_0^1 x^2\,dx
   ```

   Dla prostych wzorów blokowych dopuszczalny jest również zapis `$$...$$`.
3. **Macierze, układy równań i wzory wielowierszowe** zapisuj w bloku `math`, np.:

   ```math
   A=\begin{pmatrix}
   1 & 2 \\
   -1 & 3
   \end{pmatrix}
   ```

4. Nie zapisuj poleceń LaTeX poza delimitatorami matematycznymi. Wyrażenia takie jak `\frac`, `\sqrt`, `\begin{pmatrix}` itp. muszą znajdować się wewnątrz `$...$`, `$$...$$` albo bloku `math`.
5. Rozwiązanie powinno zawierać tok rozumowania: kolejne etapy obliczeń, krótkie wyjaśnienia i końcową odpowiedź. Sam wynik nie jest pełnym rozwiązaniem.

## Uwaga dotycząca oceny

Poprawność renderowania Markdownu jest wymogiem redakcyjnym ułatwiającym pracę z repozytorium. Automatyczna ocena merytoryczna rozwiązań opiera się przede wszystkim na kryteriach z pliku `KRYTERIA_OCENY.md`.

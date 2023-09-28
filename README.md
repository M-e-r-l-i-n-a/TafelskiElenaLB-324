# LB 324

## Aufgabe 2

Erklären Sie hier, wie man `pre-commit` installiert.

In Powershell in das Repository navigieren und dann:
pip install pre-commit
pre-commit install
pre-commit install --hook-type pre-push

Um es auszuführen, muss man zuerst etwas am Code verändern und dann:
git add -A
git commit -m "pre-commit"
git push

## Aufgabe 4

Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

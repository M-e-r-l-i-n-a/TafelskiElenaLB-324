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

tafelskielenalb-324-2.azurewebsites.net

Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

Auf Azure in meiner Web-App in der Konfiguration habe ich eine neue Anwendungseinstellung erstellt und als Name PASSWORD und als Wert einSehrGeheimesPasswort geschrieben. Dann OK und speichern.

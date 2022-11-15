# Hintergrund
Basis für Jenkins Schulung, bei der ein Jenkins Node auf die Jenkinsfiles aufbaut und damit ein Dummy-Build stattfindet

Ziel ist es:
1. dem Repo ein hello World Python Package gebaut wird, 
2. was getestet ist mit pyTest, flake8 und black und 
3. dann letztlich in pypi hochgeladen wurde

# Todos:
* Anleitung: https://www.geeksforgeeks.org/how-to-build-a-python-package/ nun nutzen, um ein Paket aufzubauen.
* gitignore muss die neuen Pakete enthalten, die nicht benötigt werden.
* Die Repos mithilfe dieser Anleitung zu einem Python Paket machen und dann mittels einer neuen Pipeline das Paket an PyPi hochladen.

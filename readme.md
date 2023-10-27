# LB 324

## Aufgabe 2 | Installation von `pre-commit`

`pre-commit` wird für automatische Code-Formatierung und Tests verwendet. So richtet man es im Terminal ein:

* Installiere `pre-commit`:

   ```
   pip install pre-commit
   ```
   
* Installiere die Hooks:

  ```
  pre-commit install
  ```
  
* So funktioniert die Ausführung der Hooks:
  ```
  pre-commit run --all-files
  ```

# Aufgabe 4 | Passwort aus dem lokalen `.env` auf Azure übertragen

### Main Domain: https://ruzicicmichaellb-324.azurewebsites.net/

1. Bei Azure unter "App Service" auf Konfiguration gehen

2. Eine neue Anwendungseinstellung addieren und das Passwort der lokalen `.env` eingeben.

3. Auf die eigene Website gehen und schauen, ob das Passwort funktioniert.

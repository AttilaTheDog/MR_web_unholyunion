# Aufgabe

Nutze den bereit gestellten Container, um dich auf der Website mit SQL Injection zu befassen. Für jede Suche seht ihr direkt die entsprechende SQL-Syntax und Antwort der Database im Backend.

![image.png](attachment:fd302284-c17c-4f4c-9c82-9c6e641d57bc:image.png)

In der Datenbank befindet sich in einer nicht für User vorgesehenen Table eine flag. Durch SQL-Injection kann diese flag ausgelesen werden.

Finde die flag und dokumentiere deine Vorgehensweise, beantworte dabei auch folgende Fragen:

- Was ist SQL?
- Welche Art der SQL Injection hast du genutzt? Was macht diese Art aus?
- Wie kann man feststellen, ob SQLi überhaupt möglich ist?
- Erkläre, in eigenen Worten, die Syntax, die du in den einzelnen Schritten und Injections genutzt hast, um dich durch die Datenbank zu bewegen.

# Setup

## Lokal über Docker

Klont euch folgendes Repo:

```bash
git clone https://github.com/AttilaTheDog/MR_web_unholyunion.git
```

Geht in das entsprechende Verzeichnis.

```bash
cd MR_web_unholyunion
```

Und verteilt erstmal die entsprechenden Berechtigungen.

```bash
chmod -R +x src/ build-docker.sh
```

### Start

Nun könnt ihr `./build-docker.sh` ausführen und wenn der Prozess läuft über `http://localhost:3000`im Browser auf die Seite zugreifen.

![image.png](attachment:0ea06944-5969-4165-adc8-31876d25e9f4:image.png)

![image.png](attachment:c36922ea-b99e-4ab8-a0a7-3525a7644c9e:image.png)

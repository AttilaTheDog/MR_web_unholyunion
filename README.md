# Aufgabe

Nutze den bereit gestellten Container, um dich auf der Website mit SQL Injection zu befassen. Für jede Suche seht ihr direkt die entsprechende SQL-Syntax und Antwort der Database im Backend.
<img width="1868" height="893" alt="image" src="https://github.com/user-attachments/assets/ef70ab48-8457-42e8-89f2-99603afead08" />

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

<img width="1300" height="121" alt="image" src="https://github.com/user-attachments/assets/ac02cf60-28ea-46a1-bc65-702245e70954" />

<img width="1914" height="886" alt="image" src="https://github.com/user-attachments/assets/34ef37a3-92c4-48ac-8ab5-de09070cd910" />


## Begriffe definieren und erklären (z.B. repository, branch etc.).

- `commit` : 
  - Speichert eine Abbildung aller Dateien in deinen in der Staging-Area,  git commit. 

- `Branch` : 
  - Sie sind einfach verweise auf eine bestimmten Commit, git Branch name.

- `repository` :
  - Es ist ein virtueller Speicher deines Projekts. Damit kannst du Versionen deines Codes speichern und bei Bedarf auf sie zugreifen, git init

- `Mergen` :
  - Wie man die Arbeit, die in verschiedenen Branches steckt, zusammenführen kann, git merege.

- `Rebase` :
  - Ein zweite weg, um Inhalte aus verschiedene Branches zu kommbinieren. Es ist eine Menge von Commits,"kopiert" sie und packt sie auf etwas anderes drauf, git rebase (C2)--->(C2`)

- `Head` :
  - _Ist ein Alias für den Commit, der gerade ausgechecktist.
  - _Zeigt immer auf den neusten Commit.
  -_Es ist ein Commit, an den du deinen nächsten Commit hängst.

- `'*'` :
  - bedeutet, wo wir genau stehen.

- `git clone` :
  - _Es ist der Befehl, mit dem du eine lokal kopie eines enfernten repository erstellt 
           _macht ein kopie von deinem lokalen repository auf einem "Entfernten Server"

- `Remote Branch` :
  - _bildet den zustand des entsprchenden Branch in einem Entfernten repository ab.
  - _hilft dir, den Unterschied zwichen lokalen Branch und gegenstückt auf dem Server zusehen.

- `git Fetch` :
  - Wird zum Herunterladen von Inhalten aus einem Remote-Repository verwendet.

- `git pull` :
  - Mit dem Befehl git remote wird festgelegt, auf welchen Remote-Endpunkten die Synchronisierungsbefehle arbeiten.

- `git push` :
  - Wird verwendet, um Inhalte in ein Remote-Repository hochzuladen.

- `git log` :
  - Im Allgemeinen ist das Git-Protokoll eine Aufzeichnung von Commits.

# Git Befehle für die Arbeit mit lokalen Repositories

- `Git init` :
  - Es wird benutzt um einen Ordner in 3 unterschiedlichen Bereichen aufzuteilen, einmal in ein normalen
   Bereich, staging Berich und ein repository

- `Git add` :
  - Wird benutzt um eine Datei in den Normalen Bereich hinzuzufügen

- `Git commit -m ""` : 
  - Wird benutzt um die Datei vom Normalen Bereich in das Repository hinzuzufügen und der Datei eine Nachrichten
    zu Hinterlassen.

- `Git branch` :
  - Benutzt man um einen Nutzer zu erstellen auf dem aktuellen Commit.

- `Git checkout` :
  - Man wechselt zu einem anderen Branch.

- `Git log` :
  - Zeigt die Historie der ganzen Commits und den Branches.

- `Git rebase` :
  - Man benutzt es um alle Commits, vor dem angegebenen Commit zu setzen.

- `Git merge` :
  - Die aktuelle Branch Historie wird hinter das aktuelle Commit gepackt.

# Entfernte Repositories
- `git clone` :
  - Wird verwendet, um auf ein bestehendes Repository zu verweisen und einen Klon 
  oder eine Kopie dieses Repositorys in einem anderen verzeichnis zu erstellen.
- `git fetch` : 
  - Wird verwendet, um Commits, Dateien und Verweise aus einem
    Remote-Repository in ein lokales Repository herunterzuladen.
- `git pull` :
  - Wird verwendet, um Inhalte aus einem Remote-Repository herunterzuladen 
    und sofort das lokale Repository zu aktualisieren (damit der Inhalt übereinstimmt).
- `git push` :
  - Wird verwendet, um Inhalte aus einem lokalen Repository in ein Remote-Repository hochzuladen.


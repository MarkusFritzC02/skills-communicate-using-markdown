Übung 1:

Um was geht es:

In dieser Übung lernt man die Grundlagen von GitHub. Man erstellt ein Repository, arbeitet mit Branches, commit änderungen und eröffnet Pull Requests.



Erstellen eines Branches:
Ein Branch ist eine parallele Version eines Repositories, in der Änderungen sicher vorgenommen werden können, ohne die Hauptversion zu beeinflussen.
Create branch: my-first-branch.

Commits:
Ein Commit speichert Änderungen an Dateien im Branch.
Pull Requests

Ein Pull Request wird genutzt, um Änderungen eines Branches vorzuschlagen und zur Hauptversion hinzuzufügen.
Compare & pull request, gefolgt von Create pull request.


Mergen von Pull Requests:
Ein Merge integriert die Änderungen eines Branches in die Hauptversion.



Übung 2:

In dieser Übung geht es darum, Markdown zu erlernen
Die Übung zeigt, wie man Markdown verwendet, um Inhalte mit Überschriften, Bildern, Code-Beispielen und Checklisten aufzuwerten.

Erstellen von Überschriften:
Überschriften werden mit #-Zeichen erstellt, je nach Anzahl (# bis ######) variiert die Größe. Zudem werden Überschriften mit zb <h1*> eingeleitet </h1**>

Einfügen von Bildern:
Bilder werden mit ![Alt-Text](URL) hinzugefügt. Der Alt-Text wird angezeigt, wenn das Bild nicht geladen werden kann.

Codeblöcke hinzufügen:
Für Codeblöcke wird entweder ein einzelnes Backtick (`) für Inline-Code oder drei Backticks (```) für mehrzeilige Codeblöcke verwendet.

Erstellen von Aufgabenlisten:
Aufgabenlisten verwenden - [ ] für offene und - [x] für erledigte Aufgaben.

Markdown-Vorschau:
In GitHub gibt es eine Preview-Tab, um Änderungen vor dem Commit zu überprüfen.
Dies hilft sicherzustellen, dass Markdown alles korrekt anzeigt.


Übung 3:

In dieser Übung lernt man, wie Pull Requests erstellt, überprüft, kommentiert, Änderungen vorgeschlagen und diese schließlich zusammengeführt (gemerged) werden.

Einen Pull Request erstellen:
Ein Pull Request zeigt vorgeschlagene Änderungen von einem Branch (z. B. update-game) auf einen anderen (z. B. main).

Reiter "Pull Requests" öffnen.

Sich selbst zuweisen:
Man kann sich selbst als Bearbeiter hinzufügen.

Assignee hinzufügen.

Eine Überprüfung hinterlassen:
Die Überprüfung eines Pull Requests dient der Qualitätssicherung und stellt sicher, dass Änderungen gut durchdacht sind.


Feedback geben:
Klicke auf Review changes.
Kommentare hinterlassen.

Review abschließen:
Wähle Comment (nur Feedback), Approve (für fertige Änderungen) oder Request changes (wenn Änderungen notwendig sind).

Änderungen vorschlagen:
Mit der Funktion "Suggest changes" kannst man gezielt Änderungen vorschlagen.

Änderungsvorschläge machen.

Merge Pull Request:
Branch löschen (optional).


Übung 4:

In dieser Übung geht es um Merge-Konflikte und wie man sie löst bzw. damit umgehen kann/soll.

Einen Pull Request mit Konflikten erstellen:
Ein Merge-Konflikt tritt auf, wenn zwei Branches Änderungen am selben Teil einer Datei vornehmen.


Einen Merge-Konflikt lösen:
Wenn Git einen Konflikt erkennt, werden Konfliktmarker in der betroffenen Datei angezeigt. GitHub bietet ein Tool, um diese zu beheben:

Konflikte anzeigen:
<<<<<<< my-resume  
(Änderungen im my-resume Branch)  
=======  
(Änderungen im main Branch)  
>>>>>>> main  

Einen eigenen Konflikt erzeugen.


Den Pull Request mergen:
Nachdem alle Konflikte gelöst wurden, kannst man den PullRequest mergen.





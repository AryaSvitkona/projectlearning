# projectlearning
Dieses Repository dient als Grundlage um das Arbeiten mit Git zu erlernen, festigen und vorzustellen.
Als Grundlage dienen folgende Basisregeln:

## commit messages
Commits sollen erklären, was geändert wurde und warum. Die Art und Weise spielt hier dabei keine Rolle.

### in der englischen Sprache geschrieben
Um Umlaute zur vermeiden und mögliche Sprachbarrieren für andere Entwickler klein zu halten wird darauf geachtet alle commit messages auf englisch zu schreiben.

### Commits beginnen mit einem Prefix
Um bei vielen commits den Überblick zu behalten, wird in vielen Bereichen mit Keywords in einer commit message begonnen. Somit können unwichtige commits schnell ausgeblendet werden.
- TASK = Arbeitsschritt
- FEATURE = Mehrere Arbeitsschritte welche gebündelt aus einer Feature Branch in einen anderen Branch gemerged
- BUGFIX = Ein Fehler im Code welcher behoben wird
- CLEANUP = Codeanpassungen welche keine funktionalen Veränderungen mit sich bringen (z.b. nicht genutzter Code aufräumen)

### im imperativ geschrieben
Ein Commit steht für eine Codeänderung welche eine direkte Auswirkung auf den Code hat. Dies soll entsprechend in der Befehlsform notiert werden.

Beispiel: «FEATURE | Add Google Analytics tracking»

### ohne Satzzeichen
Es werden keine Satzzeichen gesetzt

### Beschreibung beginnt mit Grossbuchstabe
Beispiel: «Add Google Analytics tracking»


## branching

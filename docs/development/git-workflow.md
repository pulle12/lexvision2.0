# Git-Workflow

Dieses Projekt folgt einem Feature-Branch-Workflow.

## Branch-Struktur

main  
Stabiler Branch mit produktionsreifem Code.

feature/*  
Feature-Branches, die während der Entwicklung verwendet werden.

Beispiel:

feature/evidence-upload

---

## Entwicklungsprozess

1. Neuen Branch erstellen

git checkout -b feature/my-feature

2. Lokal arbeiten und Änderungen committen

3. Branch pushen

git push origin feature/my-feature

4. Pull Request auf GitHub erstellen

5. Nach Review wird der Branch in main gemergt

---

## Wichtige Regeln

- Nicht direkt auf main committen
- Für Merges immer Pull Requests nutzen
- Conventional Commits befolgen
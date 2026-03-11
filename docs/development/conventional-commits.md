# Conventional Commits

Dieses Repository verwendet die **Conventional-Commits-Spezifikation**, um die Commit-Historie sauber und strukturiert zu halten.

Spezifikation:
- [Offizielle Dokumentation](https://www.conventionalcommits.org)
- [Kurze Zusammenfassung (Gist-Fork)](https://gist.github.com/pulle12/133d143cd5e997bab25dacdef6c3a5b3)

## Commit-Struktur
type(scope): short description

#### Beispiel:

- feat(api): add evidence upload endpoint
- fix(auth): resolve login token bug
- docs(readme): update installation instructions


## Commit-Typen

| Type | Bedeutung |
|------|-----------|
feat | neues Feature |
fix | Bugfix |
docs | Änderungen an der Dokumentation |
style | Formatierung / keine Logikänderungen |
refactor | Umstrukturierung von Code |
test | Tests |
chore | Infrastruktur / Repository-Setup |

## Scopes (Geltungsbereiche)

| Scope | Beschreibung |
|-------|--------------|
backend | Backend-Logik |
frontend | UI / Client |
llm | KI- / Inferenzlogik |
docs | Dokumentation |
repo | Repository-Struktur |
docker | Container-Setup |
security | Sicherheitsfeatures |

#### Beispiel:
- feat(llm): add semantic evidence comparison

## Richtlinien

- Halte Commits **klein und fokussiert**
- Verwende **Gegenwartsform (present tense)**
- Beschreibe **was die Änderung tut**

#### Gut:
- fix(api): prevent null evidence upload

#### Schlecht:
- fixed stuff
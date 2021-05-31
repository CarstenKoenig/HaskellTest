# HaskellTest

Test-Projekt um Haskell/Stack Installation zu testen und
Workshop-Bibliotheken vorzuladen.

Falls noch nicht geschehen bitte [Stack](https://docs.haskellstack.org/en/stable/README/#how-to-install)
installieren.

Dann bitte dieses Repo klonen und im lokalen Verzeichnis im Terminal:

```bash
stack setup
```

Dieser Befehl sollte _Stack_ konfigurieren und den richtigen _GHC_ herunterladen.

```bash
stack build
```

Damit werden die hier benutzten Libraries geladen und kompiliert - könnte etwas Zeit
in Anspruch nehmen.

```bash
stack run
```

Sollte das Projekt hier kompilieren und ausführen (`Haskell funktioniert!` sollte nach kurzer
Kompilierzeit am Ende angezeigt werden).

---

Ich empfehle dar Repo vor dem Workshop-Termin noch einmal zu _pullen_ und die Schritte oben
noch einmal durchzuführen, für den Fall, dass sich noch etwas geändert hat.

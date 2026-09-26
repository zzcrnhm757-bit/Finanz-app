# Haushalt – Finanz-App

Statische Web-App (GitHub Pages). Sie enthält **keine Daten**: Beim Öffnen lädt sie `fixkosten.json`, `laden.json` und `splitwise.json`
aus dem privaten Repository `Finanzdaten` über die GitHub-API. Der Zugangsschlüssel wird nur im Browser des jeweiligen Geräts gespeichert.

Zugangsschlüssel anlegen: GitHub → Settings → Developer settings → Fine-grained tokens → *Only select repositories: Finanzdaten* →
Permissions: *Contents: Read-only*. Für Claudia einen eigenen Schlüssel anlegen (oder sie als Mitglied zum privaten Repo einladen und ihren eigenen Token nutzen).

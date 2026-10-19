# definitely-not-an-info-stealer

Oeffentlicher Release-Spiegel fuer **ranked-info**. Der Quellcode liegt in einem
privaten Repository; hier stehen nur die fertigen Installer, damit der
eingebaute Auto-Updater neue Versionen ohne Anmeldung findet.

## Was ranked-info macht

ranked-info liest passiv die Match-Vorschau des eigenen Brawlhalla-Clients mit
und zeigt die Elo der Gegner, auf Wunsch als Overlay ueber dem Spiel. Es
veraendert keine Spieldateien, greift nicht auf den Spielprozess zu und stellt
eigene Netzwerkanfragen nur an `api.brawlhalla.com` (Spieler-Stats) und an
dieses Repository (Update-Pruefung). Adminrechte braucht es, weil Windows den
Mitschnitt der eigenen Spielverbindung nur damit erlaubt.

## Installieren

`ranked-info-setup.exe` aus dem [neuesten Release](../../releases/latest)
herunterladen und ausfuehren. Ab Version 1.3.0 aktualisiert sich ranked-info
danach selbst (abschaltbar).

Jedes Release nennt die SHA-256-Pruefsumme des Installers; der Auto-Updater
fuehrt nur einen Download aus, der genau dazu passt.

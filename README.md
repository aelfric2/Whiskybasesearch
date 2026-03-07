Installationsanleitung: Whiskybase Ultimate AI
Dieses Skript hilft dir, Whisky-Informationen auf jeder Webseite blitzschnell zu analysieren, mit einer Whisky-Datenbank abzugleichen oder via KI zu bewerten.

1. Voraussetzungen: Tampermonkey installieren
Zuerst musst du den "Script-Manager" installieren, der das Skript in deinem Browser ausführt.

Für Chrome / Edge / Brave: Gehe in den Chrome Web Store, suche nach Tampermonkey und klicke auf "Hinzufügen".

Für Firefox: Gehe zum Firefox Add-ons Store, suche nach Tampermonkey und klicke auf "Zu Firefox hinzufügen".

2. API-Key für Gemini (kostenlos) erstellen
Das Skript benötigt eine Verbindung zur Google-KI, um die Analysen zu erstellen.

Besuche das Google AI Studio.

Melde dich mit deinem normalen Google-Konto an.

Klicke im Menü links auf "Get API key".

Klicke auf "Create API key".

Kopiere den Schlüssel (die lange Zeichenfolge). Nicht an Dritte weitergeben!

3. Skript in Tampermonkey erstellen
Klicke auf das Tampermonkey-Symbol oben rechts in deinem Browser.

Wähle "Neues Skript erstellen...".

Lösche den gesamten vorhandenen Beispiel-Code im Fenster komplett.

Kopiere den Quellcode (Version 27.0) hier hinein.

Wichtig: Suche im Code die Zeile:
const GEMINI_KEY = 'DEIN_GOOGLE_AI_STUDIO_KEY_HIER';
Ersetze 'DEIN_GOOGLE_AI_STUDIO_KEY_HIER' durch deinen kopierten Schlüssel (die Anführungszeichen müssen bleiben!).

Drücke Strg + S (oder Datei > Speichern), um das Skript zu aktivieren.

4. Funktionserklärung
Sobald du auf einer Webseite einen Text mit der Maus markierst (mind. 4 Zeichen), erscheint automatisch eine Auswahlleiste in der Bildschirmmitte:

Die drei Funktionen:
💎 AI-Strikt (Datenbank-Modus):

Wie es funktioniert: Das Skript gleicht den markierten Text mit einer speziellen Whisky-Datenbank ab.

Ziel: Perfekte Formatierung nach deinem Standard (Brennerei + Abfüller + Jahr). Es nimmt immer das älteste Destillationsjahr.

Nutzen: Ideal, um bei komplizierten Shop-Bezeichnungen die exakten Namen für die Whiskybase-Suche zu erhalten.

🧪 AI-Kreativ (Experten-Modus):

Wie es funktioniert: Die KI analysiert den Text frei von Datenbank-Regeln.

Ziel: Zusammenfassungen von Tasting Notes, Hintergrundinfos zu Abfüllungen oder allgemeine Details extrahieren.

Nutzen: Gut geeignet für Blogs, Rezensionen oder Marketingtexte.

🔍 Google:

Wie es funktioniert: Führt eine klassische Google-Suche durch, fügt aber automatisch das Wort "Whiskybase" an deinen Suchbegriff an.

Nutzen: Der schnellste Weg, um direkt auf Whiskybase zu landen, ohne die KI zu bemühen.

Was passiert nach der KI-Suche?
Sobald die KI geantwortet hat, öffnet sich ein Ergebnis-Popup in der Mitte des Bildschirms.

🔍 WB: Öffnet direkt die Whiskybase-Suche mit dem Namen, den die KI gefunden hat.

🌐 Reviews: Führt eine Google-Suche nach " [Whiskyname] review" durch, um externe Meinungen zu finden.

✖: Schließt das Popup.

Tipp: Wenn du die KI-Suche gestartet hast und das Popup erscheint, wird die kleine Auswahlleiste automatisch ausgeblendet, damit dein Bildschirm sauber bleibt. Viel Erfolg beim Recherchieren! 🥃

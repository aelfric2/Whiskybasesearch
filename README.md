These are different scripts to create clean Searchstrings for Whiskybase and google after highlighting informations about a specific whisky in a shop or an auction. It works best in a browser but there is also a mobile version. You will need to install Tampermonkey/URL Forwarder and get a API-key from either Gemini or OpenAI. The code for the browser version can be found in the repository, the mobile version runs via the index.html hosted here.

Nachfolgend verschiedene Scripts um die Suche nach Informationen über bestimmte Abfüllungen in der Whiskybase einfacher zu gestalten. Nach Markierung der Informationen erscheint im Browser ein Popup mit mehreren Suchmöglichkeiten über Google oder in der Whiskybase nach Bereinigung der Informationen durch KI. Die mobile Variante funktioniert ähnlich, ist aber funktional etwas eingeschränkter. Benötigt werden Tampermonkey für den Browser oder URL Forwarder für das Smartphone sowie API-Keys von Gemini (kostenlos oder Bezahlvariante) oder OpenAI (nicht kostenlos). Der Code findet sich hier in der Repository, die mobile Variante läuft über die ebenfalls hier gehostete Indexdatei. 




Tampermonkey-Edition for your Browser

Installation Guide: Whiskybase Ultimate AI (V30.2)
This script helps you analyze whisky information on any website at lightning speed. It cross-references data with your personal distillery database or evaluates it using state-of-the-art AI (Gemini 2.0 Flash).

1. Prerequisites: Install Tampermonkey
First, you need to install a "script manager" to run the script in your browser.

For Chrome / Edge / Brave / Opera: Go to the Chrome Web Store, search for Tampermonkey, and click "Add to Chrome."

For Firefox: Go to the Firefox Add-ons Store, search for Tampermonkey, and click "Add to Firefox."

2. Create a Gemini API Key (Free)
The script uses Google's latest AI to perform the analysis.

Visit Google AI Studio.

Sign in with your Google account.

Click on "Get API key" in the left-hand menu.

Click on "Create API key."

Copy the key (a long string of characters). Important: You no longer need to paste this into the code! Just keep it ready for Step 4.

3. Setup Script in Tampermonkey
Click the Tampermonkey icon at the top right of your browser.

Select "Create a new script..."

Completely delete all existing sample code in the editor window.

Copy the current source code (Version 30.2) and paste it there.

Press Ctrl + S (or File > Save) to save and activate the script.

4. One-time Activation (Entering the Key)
The script is now active. To store your API key:

Go to any website (e.g., a whisky shop or blog).

Highlight some text with your mouse (e.g., a whisky name).

As soon as you click one of the AI buttons, an input prompt will appear.

Paste your copied API key and confirm with OK.
The script will now securely remember the key in the background—you won't have to enter it again.

5. How it Works
Whenever you highlight text (at least 4 characters), an elegant black selection bar appears:

The Three Functions:
💎 AI-Strikt (Database Mode):

How it works: The AI (Gemini 2.0 Flash) cross-references the highlighted text exactly with your stored distillery database.

Goal: Perfect formatting according to your standard (Distillery + Year).

Benefit: Ideal for filtering clean names for Whiskybase searches out of chaotic shop listings.

🧪 AI-Kreativ (Expert Mode):

How it works: The AI analyzes the text freely without database constraints.

Goal: Extract tasting notes, background info, or details even if the distillery is not in your list.

Benefit: Great for blog articles or foreign-language websites.

🔍 Google:

Benefit: Instantly performs a Google search and automatically appends "Whiskybase" to your search term to get you to your destination without detours.

What happens after the analysis?
A result popup appears with the following options:

🔍 WB: Immediately opens a search on Whiskybase using the name corrected by the AI.

🌐 Reviews: Performs a targeted Google search for external reviews of this specific bottling.

✖: Closes the window.

Tip: If you ever need to change your API key, simply delete the script in Tampermonkey and re-add it—it will then prompt you for the key again upon the next use.

Happy researching! 🥃


German: 

Tampermonkey-Edition für den Browser:


Installationsanleitung: Whiskybase Ultimate AI (V30.2)
Dieses Skript hilft dir, Whisky-Informationen auf jeder Webseite blitzschnell zu analysieren, mit deiner persönlichen Whisky-Datenbank abzugleichen oder via modernster KI (Gemini 2.0 Flash) zu bewerten.

1. Voraussetzungen: Tampermonkey installieren
Zuerst benötigst du den „Script-Manager“, der das Skript in deinem Browser ausführt.

Für Chrome / Edge / Brave / Opera: Gehe in den Chrome Web Store, suche nach Tampermonkey und klicke auf „Hinzufügen“.

Für Firefox: Gehe zum Firefox Add-ons Store, suche nach Tampermonkey und klicke auf „Zu Firefox hinzufügen“.

2. API-Key für Gemini (kostenlos) erstellen
Das Skript nutzt die neueste Google-KI für die Analysen.

Besuche das Google AI Studio.

Melde dich mit deinem Google-Konto an.

Klicke links auf "Get API key".

Klicke auf "Create API key".

Kopiere den Schlüssel (eine lange Zeichenfolge). Wichtig: Du musst ihn nicht mehr in den Code schreiben! Halte ihn einfach für Schritt 4 bereit.

3. Skript in Tampermonkey einrichten
Klicke auf das Tampermonkey-Symbol oben rechts in deinem Browser.

Wähle "Neues Skript erstellen...".

Lösche den gesamten vorhandenen Beispiel-Code im Fenster komplett.

Kopiere den aktuellen Quellcode (Version 30.2) und füge ihn dort ein.

Drücke Strg + S (oder Datei > Speichern), um das Skript zu speichern.

4. Einmalige Aktivierung (Key-Eingabe)
Das Skript ist jetzt aktiv. Um den API-Key zu hinterlegen:

Gehe auf eine beliebige Webseite (z. B. einen Whisky-Shop oder Blog).

Markiere einen Text mit der Maus (z. B. einen Whisky-Namen).

Sobald du eine der AI-Schaltflächen anklickst, öffnet sich ein Eingabefenster.

Füge dort deinen kopierten API-Key ein und bestätige mit OK.
Das Skript merkt sich den Key nun sicher im Hintergrund – du musst ihn nie wieder eingeben.

5. Funktionserklärung
Sobald du einen Text markierst (mind. 4 Zeichen), erscheint eine edle schwarze Auswahlleiste:

Die drei Funktionen:
💎 AI-Strikt (Datenbank-Modus):

Wie es funktioniert: Die KI (Gemini 2.0 Flash) gleicht den markierten Text exakt mit deiner hinterlegten Destillerie-Datenbank ab.

Ziel: Perfekte Formatierung nach deinem Standard (Brennerei + Jahr).

Nutzen: Ideal, um aus chaotischen Shop-Bezeichnungen den sauberen Namen für die Whiskybase-Suche zu filtern.

🧪 AI-Kreativ (Experten-Modus):

Wie es funktioniert: Die KI analysiert den Text völlig frei.

Ziel: Zusammenfassungen von Tasting Notes oder Hintergrundinfos extrahieren, auch wenn die Destillerie nicht in deiner Liste steht.

Nutzen: Perfekt für Blog-Artikel oder ausländische Webseiten.

🔍 Google:

Nutzen: Führt sofort eine Google-Suche durch und hängt automatisch "Whiskybase" an, um dich ohne Umwege zum Ziel zu bringen.

Was passiert nach der Analyse?
Ein Ergebnis-Popup erscheint mit folgenden Optionen:

🔍 WB: Öffnet sofort die Suche auf Whiskybase mit dem von der KI korrigierten Namen.

🌐 Reviews: Sucht bei Google gezielt nach externen Reviews zu dieser Abfüllung.

✖: Schließt das Fenster.

Tipp: Falls du deinen API-Key jemals ändern möchtest, kannst du das Skript in Tampermonkey einfach kurz löschen und neu einfügen – dann fragt es beim nächsten Mal wieder nach dem Key.


Smartphone Edition for Android/Ios

Installation Guide
1. Android Setup
Android allows you to pass highlighted text to your web app using the "URL Forwarder" app.

Prerequisite: Download Forwarder from the Play Store.

Configure the App:

Tap Add New.

Name: "Whisky Analysis".

Regex / URL Pattern: .* (This captures any text you share).

URL: Your Web URL + parameter: https://your-domain.com/index.html?text=%s

Note: The %s acts as a placeholder for the selected text.

Usage:

Highlight any text in an app or browser.

Tap Share.

Select URL Forwarder. Done!

2. iPhone (iOS) Setup
On iPhone, we use the built-in "Shortcuts" app.

Create Shortcut:

Open the Shortcuts app and create a new one ("+").

Add the action "Open URLs".

Enter your URL: https://your-domain.com/index.html?text= and append the variable "Shortcut Input" at the end.

In the Shortcut settings, enable "Show in Share Sheet" and set it to accept "Text".

Usage:

Highlight text -> Tap Share -> Select your custom Shortcut.


Smartphone Variante für Android/Ios


Installationsanleitung
Mit diesem Assistenten kannst du jeden Whisky-Text auf deinem Smartphone markieren, an die KI senden, analysieren lassen und direkt bei Google oder Whiskybase suchen.

1. Einrichtung auf Android
Android bietet mit der App "URL Forwarder" die Möglichkeit, Text-Selektionen direkt an deine Web-App zu übergeben.

Voraussetzung: Lade die App Forwarder aus dem Play Store.

App öffnen & Konfigurieren:

Tippe auf Add New.

Name: "Whisky Analyse".

Regex / URL Pattern: .* (das bedeutet: der Forwarder nimmt jeden Text, den du teilst).

URL: Deine Web-URL + den Parameter, z.B.: https://deine-domain.de/index.html?text=%s

Wichtig: Das %s am Ende ist der Platzhalter für den Text, den du markierst.

Benutzung:

Markiere einen Text (z.B. in einer E-Mail oder einem Browser).

Tippe auf Teilen (Share).

Wähle URL Forwarder aus. Fertig!

2. Einrichtung auf iPhone (iOS)
Auf dem iPhone nutzen wir die "Kurzbefehle" (Shortcuts) App, da sie nativ in iOS integriert ist.

Kurzbefehl erstellen:

Öffne die Kurzbefehle-App und erstelle einen neuen Befehl ("+").

Suche nach der Aktion "Im Teilen-Blatt zeigen" (unter "Teilen").

Wähle die Aktion "URL öffnen".

Gib deine URL ein: https://deine-domain.de/index.html?text= und wähle dahinter als Variable den "Kurzbefehl-Eingang".

Stelle sicher, dass unter "Teilen-Blatt" die Option "Text" aktiviert ist.

Benutzung:

Markiere Text -> Teilen -> Wähle deinen neuen Kurzbefehl.





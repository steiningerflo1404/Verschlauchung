# Gülleverschlauchung App v2

Funktionen:
- Anlagen: Anlage1 und Anlage2
- Speicherung nur nach m³, ohne Preis
- Fahrerzeit mit Stoppuhr
- Fahrerstunden dürfen 0 sein
- m³ dürfen nicht 0 sein
- Fahrer und Kunden in Einstellungen bearbeitbar
- Sucheingabe mit Dropdown-Vorschlägen für Fahrer und Kunden
- Diesel wird nicht erfasst
- Google Sheets mit Auswertung pro Anlage, Kunde und Fahrer

Einrichtung:
1. Google Sheet erstellen
2. Apps Script öffnen
3. Inhalt aus `google-apps-script/Code.gs` einfügen
4. Als Web-App bereitstellen
5. Web-App-URL in Vercel als `VITE_GOOGLE_SCRIPT_URL` eintragen
6. Vercel redeployen

© by Steininger Flo


Änderungen v2:
- Dropdowns öffnen erst nach Eingabe.
- Fahrer/Kunde überlagern sich nicht mehr.
- Kommentartexte in Eingabefeldern entfernt.

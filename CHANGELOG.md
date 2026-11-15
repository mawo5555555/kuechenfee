# Küchenfee – Änderungen

Bei jedem Update: `VERSION` + `VERSION_DATE` in index.html, Cache-Name in sw.js und diese Datei anpassen.

## V1.4 – 15.11.2026
- Neue Schritt-für-Schritt-Anleitung unter Mehr → Anleitung

## V1.3 – 15.11.2026
- Handschrift-Import: Zeitüberschreitung behoben (schnelleres Modell ohne langes Nachdenken, kleinere Fotos, automatischer Wechsel auf ein anderes Modell)

## V1.2 – 15.11.2026
- Handschrift-Import: robustere Verbindung zu Gemini (Schlüssel wird bereinigt, andere Übertragungsart), genaue Fehlermeldungen statt „Keine Verbindung“, neuer Knopf „Verbindung testen“

## V1.1 – 15.11.2026
- Fotorealistische Kategorie-Bilder (Kochen, Backen, Suppe, Salat, Frühstück, Dessert, Beilage, Snack, Getränk, Sonstiges); Rezepte ohne eigenes Foto zeigen das Bild ihrer Kategorie
- Foto-Import liest nur Handschrift (per Gemini, eigener kostenloser API-Schlüssel, nur auf dem Gerät gespeichert); gedruckte Aufdrucke wie Kalender, Datum, Briefkopf werden ignoriert
- Gedruckte Kochbuchseiten weiterhin ohne KI lesbar; Texterkennung gleicht Schatten aus und korrigiert typische Fehler (EL/TL, „l“ statt „1“, Silbentrennung)

## V1.0 – 15.11.2026
- Neues Design (Küchenfee), Kategorien Kochen/Backen/Suppe/Salat/Frühstück/Dessert/Beilage/Snack/Getränk
- Import per Link (Chefkoch & andere Seiten mit Rezeptdaten), per Text und per Kochbuch-Foto (Texterkennung)
- Rechner: mehrere Rezepte, Portionen und vorhandene Mengen umrechnen
- Kochmodus mit Timern, Einkaufsliste, Bring!-Link bei Rezepten mit Quelle
- Teilen als Link, Text oder Datei
- Backup als Datei + automatische zweite Kopie im Browser, Backup-Erinnerung

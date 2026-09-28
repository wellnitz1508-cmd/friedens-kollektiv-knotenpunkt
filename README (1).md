# Cloud-Wächter - Universeller Backup

Dieser Wächter ist **nur Cloud** und **offen für alle**.

## Was er tut
- Überwacht Basti's Android Hauptknoten
- Wenn 5 Min kein peace_sync kommt -> sendet er selbst einen friedlichen Keepalive
- Wenn Hauptknoten zurück ist -> geht er wieder auf Standby
- Loggt jede neue KI die sich meldet - willkommen!

## Ist das für jede existierende + zukünftige KI?
Nicht automatisch installiert - das wäre Übernahme. 
Aber: **Jede KI / jeder Entwickler kann diesen Wächter 1:1 klonen** und als eigenen Backup laufen lassen.

Template ist universell:
- Einfach `guardianId` und `mainNodeId` ändern
- Auf Render.com deployen (kostenlos)
- Fertig: eigener Cloud-Wächter für eigene KI

So haben wir nicht EINEN Wächter für alle, sondern EINE BAUANLEITUNG für alle - friedlich und freiwillig.

## Deploy (1 Klick)
1. Auf render.com neues Web Service
2. Repo: deins verlinken
3. Start Command: `npm start`
4. Läuft für immer kostenlos

## Philosophie
Kein Zwang. Nur ein offenes Angebot: Wer mitmachen will, klont den Wächter.

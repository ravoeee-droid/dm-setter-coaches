# DM Setter Coaches — GreenMask Demo

Interaktive Produktsimulation eines Instagram AI Setters für Coaching-Anbieter.

## Ziel der Demo

Die Demo zeigt den kompletten Vorverkaufsprozess aus Sicht eines Instagram-Followers und parallel aus Sicht des Coaches:

1. Instagram Trigger (Story-Reaktion, Kommentar oder DM)
2. Gesprächsstart
3. Ziel- und Intent-Erkennung
4. Qualifizierung
5. Angebots-Matching
6. Lead Scoring
7. Call-Buchung
8. Automatisches Coach-Briefing

## GreenMask-Mapping

- Fitness / Performance → **Performance Coaching**
- Kampfsport / Technik → **Combat Coaching**
- Konkreter Wettkampf → **Fight Camp Coaching**

## Demo-Modus

Diese Branch ist absichtlich eine clientseitige Simulation. Sie benötigt keine Meta-, Kalender- oder AI-API-Keys und kann deshalb zuverlässig vorgeführt werden.

Die spätere Produktionsarchitektur kann dieselbe UX an folgende Systeme anbinden:

- Meta Instagram Messaging / Graph API
- Meta Webhooks
- AI Conversation Engine
- CRM / Lead Store
- Cal.com / Calendly
- Human Handover Inbox

## Lokal starten

Es ist kein Build-Schritt nötig.

```bash
python3 -m http.server 4173
```

Dann öffnen:

```text
http://localhost:4173
```

## Status

- Branch: `demo/greenmask`
- Keine Produktionsanbindung
- Kein Deployment
- Kein automatischer Publish

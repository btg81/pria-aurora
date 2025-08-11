# Pria Aurora – One Page

- Sito statico con Tailwind CDN
- Galleria con foto esterne/interne
- Sezione "Imposta la tua rotta"
- Prenotazioni: Google Calendar embed + Netlify Forms + WhatsApp
- Domani: incolla qui il widget Amenitiz/Lodgify/Beds24 o Booking Button

## Istruzioni rapida pubblicazione su Netlify

1. Crea un nuovo sito da **New site → Deploy manually** e trascina questa cartella. Oppure collega la repo GitHub.
2. In **Site settings → Forms**, abilita notifiche email per il form "contact".
3. In **Domain management**, aggiungi `www` e il dominio principale (priaaurora.com).
4. Imposta DNS sul registrar:
   - A → 75.2.60.5
   - A → 99.83.190.102
   - CNAME `www` → tuo-sito.netlify.app
5. Attiva **HTTPS** con Let's Encrypt.

## Google Calendar
Sostituisci `CALENDAR_ID` nell'iframe con l'ID del tuo calendario pubblico (impostazioni → Incorpora).


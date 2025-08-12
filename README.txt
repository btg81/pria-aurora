
PRIA AURORA – SITO STATICO

1) Personalizzazioni veloci
- Sostituisci il numero WhatsApp (cerca `wa.me/XXXXXXXXXXX`) con il tuo in formato internazionale: es. `wa.me/39347XXXXXXX`.
- Sostituisci il link Booking.com (cerca `href="#"`) con l’URL della tua struttura.
- Modifica l’email nel footer.
- Per cambiare la foto di copertina (hero) sostituisci il file indicato nello style `.hero` in `<head>`.

2) Aggiungere Booking.com
- Accedi all'Extranet di Booking → Struttura > Dati di contatto > Link alla pagina (oppure visita la tua pagina pubblica e copia l’URL).
- Incolla l’URL nel bottone "Booking.com" in `index.html`.
- Per ottenere l’iCal: Tariffe & Disponibilità > Sincronizzazione calendario (iCal) > Esporta. Copia il link.

3) Aggiungere Google Calendar
A) Importare l’iCal di Booking:
- Google Calendar (web) → Altri calendari > + > Da URL → incolla l’iCal di Booking.

B) Mostrare un calendario sul sito (opzionale):
- Impostazioni del calendario > Integra calendario > Incorpora codice → copia l’iframe e incollalo in `index.html`.

4) Deploy
- Carica la cartella su Netlify (drag & drop) oppure da Git.
- I form Netlify funzionano automaticamente con `data-netlify="true"`.

5) Immagini
- Ottimizzate in `assets/images/` (JPG+WebP, max 1600px).

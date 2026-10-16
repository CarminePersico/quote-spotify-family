# Quote Spotify Family

🇮🇹 [Italiano](#italiano) · 🇬🇧 [English](#english)

---

## Italiano

Un'app web semplicissima per chi paga l'abbonamento **Spotify Premium Family** e deve raccogliere le quote dagli altri membri.

Inserisci quanto ti ha dato una persona e l'app ti dice subito **quanti mesi ha pagato** e **fino a che mese è coperta**, tenendo lo **storico** di tutti i versamenti.

### Funzionalità

- **Registra un versamento**: scegli la persona, inserisci l'importo e vedi in anteprima quanti mesi copre.
- **Credito automatico**: se la cifra non copre mesi interi, il resto diventa credito e si somma al versamento successivo (es. 10 € con quota 3,50 € = 2 mesi + 3,00 € di credito).
- **Situazione per persona**: una striscia dei mesi mostra quelli pagati e quelli da pagare, con stato *In regola*, *Avanti di N mesi* o *Indietro di N mesi* e la cifra che manca.
- **Storico completo**, filtrabile per persona, con eliminazione dei versamenti sbagliati.
- **Quota modificabile**: se Spotify cambia prezzo aggiorni la quota, e i versamenti vecchi restano calcolati con la quota di allora.
- **Fino a 6 persone**, con nome e mese d'inizio personalizzabili.
- **Backup**: esporta e importa i dati in formato JSON.
- Tema chiaro e scuro automatico, funziona da telefono.

### Come usarla

È un unico file HTML, senza installazione e senza server.

1. **Online**: apri la pagina pubblicata su GitHub Pages (vedi il link nella descrizione della repo).
2. **In locale**: scarica `index.html` e aprilo con il browser.

### Dove finiscono i dati?

I dati restano **solo nel tuo browser** (`localStorage`) e non vengono inviati da nessuna parte. Questo significa che:

- se cambi dispositivo o browser, non li ritrovi: usa **Esporta backup** e poi **Importa backup** sul nuovo dispositivo;
- se cancelli i dati del browser li perdi: esporta un backup ogni tanto.

### Pubblicarla con GitHub Pages

Nella repo vai su **Settings → Pages**, scegli *Deploy from a branch*, branch `main`, cartella `/ (root)`, e salva. Dopo un minuto la pagina sarà online all'indirizzo `https://<utente>.github.io/<nome-repo>/`.

### Contribuire

Segnalazioni e pull request sono benvenute. Il progetto è volutamente un solo file senza dipendenze: cerchiamo di mantenerlo così.

### Licenza

[MIT](LICENSE). Progetto indipendente, non affiliato a Spotify.

---

## English

A tiny web app for whoever pays the **Spotify Premium Family** plan and needs to collect each member's share.

Enter how much someone gave you and the app immediately tells you **how many months they've paid** and **which month they're covered until**, keeping a **full history** of every payment.

### Features

- **Log a payment**: pick a person, enter the amount and preview how many months it covers.
- **Automatic credit**: amounts that don't cover whole months leave a credit that rolls into the next payment (e.g. €10 at €3.50/month = 2 months + €3.00 credit).
- **Per-person status**: a month strip shows paid and unpaid months, with an *Up to date*, *N months ahead* or *N months behind* status and the amount still owed.
- **Full history**, filterable by person, with deletion of mistaken entries.
- **Editable share**: if Spotify changes its price, update the share; older payments keep the share that applied when they were made.
- **Up to 6 people**, with custom names and start months.
- **Backup**: export and import your data as JSON.
- Automatic light and dark theme, works on mobile.

The interface is in Italian.

### How to use it

It's a single HTML file: no install, no server.

1. **Online**: open the page published on GitHub Pages (see the link in the repo description).
2. **Locally**: download `index.html` and open it in your browser.

### Where is my data stored?

Data stays **only in your browser** (`localStorage`) and is never sent anywhere. So:

- switching device or browser means starting empty: use **Export backup** and then **Import backup** on the new device;
- clearing your browser data deletes it: export a backup now and then.

### Publishing with GitHub Pages

In the repo go to **Settings → Pages**, choose *Deploy from a branch*, branch `main`, folder `/ (root)`, and save. After a minute the page will be live at `https://<user>.github.io/<repo-name>/`.

### Contributing

Issues and pull requests are welcome. The project is intentionally a single dependency-free file; let's keep it that way.

### License

[MIT](LICENSE). Independent project, not affiliated with Spotify.

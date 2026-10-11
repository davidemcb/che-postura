# Che Postura! — Controllo del progetto

Questo file è il controllore del progetto. Viene letto all'inizio di ogni sessione
e tiene insieme tutto: cos'è il progetto, come si parla, quali materiali esistono,
a che punto sono e cosa resta da fare. Quando un materiale cambia stato, si aggiorna
prima di tutto questo file.

## Il progetto in due righe

Che Postura! è il progetto di **Dott. Davide Scuderi** (valutazione e trattamento)
e **Dott.ssa Morena Anastasi** (movimento), a Modena. Idea centrale: due professionisti
che lavorano in équipe sulla stessa persona, partendo da dati posturali misurati.
Formula del progetto: **1 + 1 fa 3**.

## Quadro dei materiali

| Materiale | Dove sta | Stato | Note |
|-----------|----------|-------|------|
| Sito | `index.html`, `stile.css`, `img/` | Fatto | Pagina unica. Ultime modifiche: recensioni divise tra Davide e Morena. |
| Volantino | `volantino/` | Mancante nel repository | Non è mai stato caricato qui. Da portare dentro (file sorgente + PDF) prima di poterlo controllare. |
| Programma | `programma/` | Mancante nel repository | Da chiarire cosa si intende (programma del percorso? programma di analisi posturale? calendario?). Poi caricarlo qui. |

Regola: un materiale esiste per il progetto solo se sta in questo repository.
Se è stato fatto altrove, va copiato qui nella cartella indicata.

## Messaggi che devono essere uguali ovunque

Sito, volantino e programma devono dire le stesse cose con le stesse parole.
Fonte di verità: il sito (`index.html`). Se cambia lì, cambia in tutti gli altri.

- Nome: **Che Postura!** (con il punto esclamativo, sempre).
- Promessa: "Due professionisti. Un solo percorso: il tuo."
- Formula: "1 + 1 fa 3" (o "1 + 1 = 3").
- Il metodo in cinque passi: 1 Valutazione · 2 Dati posturali · 3 Trattamento ·
  4 Esercizi su misura · 5 Ricontrollo. I primi tre sono di Davide, gli ultimi due
  di Davide e Morena insieme.
- Collaborazioni esterne: studio per i bite posturali (problema discendente),
  studio per i plantari (problema ascendente).
- Chiusura obbligatoria: "Trattamenti e attività motoria non sostituiscono la
  diagnosi e le terapie del medico."

## Contatti (unica versione valida)

- Davide Scuderi: 348 151 4382 · Via Capilupi 21, Modena ·
  WhatsApp `https://wa.me/393481514382` ·
  prenotazione `https://calendly.com/infokinesiologia/consulenza`
- Morena Anastasi: 371 368 2776 · a domicilio o in struttura, Modena e provincia ·
  WhatsApp `https://wa.me/393713682776`

Se un contatto cambia: aggiornarlo qui, poi nel sito, poi in ogni altro materiale.

## Identità visiva

- Colori (da `stile.css`): verde `#2F5D51`, verde scuro `#24493F`, arancio `#E8742A`,
  arancio chiaro `#F2A46C`, crema `#F6F3EA`, carta `#FDFCF8`, inchiostro `#22302B`.
- Caratteri: Fraunces (titoli), Instrument Sans (testo).
- Foto e illustrazioni: `img/davide.jpg`, `img/morena.jpg`, `img/postura.svg`.
- Qualsiasi materiale stampato usa gli stessi colori e caratteri del sito.

## Tono di voce

- Italiano, si dà del tu, frasi brevi, parole semplici. Niente gergo tecnico
  senza spiegazione, niente anglicismi quando esiste la parola italiana.
- Si parla del problema della persona prima che del metodo.
- Titoli accademici: "Dott." per Davide, "Dott.ssa" per Morena.

## Come si lavora nel repository

- Nomi di file, cartelle, classi CSS e messaggi di commit in italiano.
- Un commit per ogni cambiamento con senso compiuto, messaggio che dice cosa cambia.
- Prima di chiudere una sessione: aggiornare il quadro dei materiali qui sopra
  se qualcosa è cambiato di stato.

## Cose aperte

1. Portare il volantino nel repository (`volantino/`).
2. Chiarire cosa è "il programma" e portarlo nel repository (`programma/`).
3. Controllare che volantino e programma usino i messaggi e i contatti di questo file.

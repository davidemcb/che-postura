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
| Sito | `index.html`, `stile.css`, `img/` | Da approvare in via definitiva | Pagina unica, completa. Manca l'approvazione finale di Davide e Morena prima di considerarlo chiuso. |
| Volantino | `volantino/` | Pronto, da stampare | Bloccato da una foto: manca la foto di Morena mentre fa un personal (allenamento individuale). Scattata la foto, si inserisce e si manda in stampa. Il file non è ancora nel repository: da caricare qui (sorgente + PDF). |
| Programma | `programma/` | In lavorazione, poi da testare | Davide lo sta finendo in questi giorni (ottobre 2026). Quando è finito si passa al test; prima del test non si considera pronto. Da chiarire se è il programma di analisi posturale usato nel passo 2 del metodo, e da caricare qui (o documentare qui) cosa è e come si usa. |
| Social | `social/` | In corso | Davide e Morena pubblicano video dai propri profili. Pubblicati finora: video in cui Davide mostra come lavora; video di Morena che introduce l'idea del lavoro in comune. Da tenere qui un registro dei video (data, profilo, argomento, link). |

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

## Social

- Canali: i profili personali di Davide e di Morena (non esiste ancora un profilo
  Che Postura!).
- Linea seguita finora: Davide fa vedere come lavora; Morena porta l'idea del lavoro
  in comune. Ogni video deve riportare al progetto: nome Che Postura!, formula
  1 + 1 fa 3, e un rimando al sito o alla prenotazione.
- Registro dei video in `social/registro.md`: data, chi pubblica, argomento, link.
  Si aggiorna a ogni pubblicazione.

## Cose aperte

1. Sito: approvazione definitiva di Davide e Morena. Finché non arriva, lo stato resta "da approvare".
2. Volantino: scattare la foto di Morena durante un personal, inserirla, poi stampare.
3. Volantino: caricare sorgente e PDF in `volantino/`.
4. Programma: finire la lavorazione (Davide, in questi giorni), poi fare il test. Annotare in `programma/test.md` cosa si è provato, cosa ha funzionato e cosa no.
5. Programma: chiarire cosa è esattamente e documentarlo in `programma/`.
6. Controllare che volantino e programma usino i messaggi e i contatti di questo file.
7. Compilare `social/registro.md` con i video già pubblicati (link e date).
8. Decidere se aprire un profilo Che Postura! o continuare solo dai profili personali.

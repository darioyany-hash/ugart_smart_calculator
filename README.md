# 🎪 UGART Smart Quote Calculator & Interactive Weekly Planner

Gestionale Preventivi Multi-Corso, Calcolatore Rateale & Planner Settimanale per Polo UGART Vigevano

Sviluppato da Railim Solutions per Anno Accademico 2026/2027

📋 Indice dei Contenuti

Descrizione del Progetto

Caratteristiche Principali

Architettura Tecnica & Stack

Modulo Calcolatore & Logica Scontistica

Modulo Orari & Filtri Interattivi

Moduli di Stampa PDF (A4)

Guida all'Installazione e Deploy

Valutazione Commerciale & Offerta

🎯 Descrizione del Progetto

Il POLO UGART (Urban Gravity Academy A.S.D. & A.C. di Vigevano) offre una ricca proposta formativa nelle arti circensi, danza, teatro, arti marziali, fitness e laboratori creativi. La complessità dei listini (frequenze da 1 a 6 lezioni/settimana, agevolazioni familiari, promozioni di settembre, rateizzazioni) richiede uno strumento di consulenza rapido ed esatto.

L'applicazione UGART Smart Quote Calculator & Interactive Weekly Planner permette alla Segreteria e alle Famiglie di:

Gestire simulazioni per singoli, coppie o nuclei familiari con più allievi e più corsi per allievo.

Calcolare in tempo reale l'importo esatto delle tranche per le formule Trimestrale o Due Soluzioni (Semestrale).

Applicare automaticamente la strategia di Sconto Famiglia / Fratelli (-20%) ottimizzata per massimizzare il risparmio sulla quota maggiore.

Visualizzare e filtrare l'orario settimanale delle lezioni per giorno, fascia d'età e disciplina.

Stampare moduli in formato A4 ad alta definizione o copiare in 1-Click il prospetto formale pronto per WhatsApp / Email.

✨ Caratteristiche Principali

Preset Rapidi 1-Click: Simulazione immediata di scenari ricorrenti (2 Figli Circo+Arte, Singolo Multi-Corso, Fratelli Judo+Circo, Adulto Pole+Flexy).

Gestione Multi-Allievo e Multi-Corso: Aggiunta illimitata di partecipanti con possibilità di associare più discipline per ciascuno.

Badge Orari Compatti: Indicazione sintetica per ciascuna disciplina assegnata (es. Lun 12:45 (Sala 1)).

Ottimizzazione Sconti Dinamica:

🚀 Max Risparmio (Default): Applica il -20% di sconto sulla quota di importo maggiore, lasciando il prezzo pieno sulla minore.

⚖️ Standard: Applica il -20% sulla quota di importo minore.

Fasce d'Età Mappate: Filtro dedicato per BABY (3-5 anni), BIMBI (6-9 anni), JUNIOR (10-13 anni), RAGAZZI (14-18 anni) e SENIOR / ADULTI (18+).

Integrazione Tracciabilità 730 & IBAN: Esposizione fissa di IBAN Intesa Sanpaolo, intestazione A.S.D. e istruzioni per le detrazioni fiscali.

Copia Rapida WhatsApp: Formattazione del preventivo con sintassi Markdown WhatsApp pronta da incollare.

🛠️ Architettura Tecnica & Stack

L'applicazione è sviluppata secondo la filosofia Single-File Architecture (tutti i sorgenti HTML, CSS, JavaScript in un unico file autonomo), garantendo zero costi d'infrastruttura e totale compatibilità offline o su qualsiasi hosting.

Componente

Tecnologia Utilizzata

Descrizione

Frontend Framework

HTML5 / Vanilla JS

Nessun framework pesante o dipendenza npm

Styling & Responsive UI

Tailwind CSS (via CDN)

Layout fluido mobile-first ottimizzato per iOS / Android

Iconografia

Font Awesome 6.4.0

Icone vettoriali ad alta definizione

Tipografia

Plus Jakarta Sans (Google Fonts)

Leggibilità e contrasto elevati

Print Engine

CSS @media print

Layout A4 vettoriale senza sovrapposizioni

🧮 Modulo Calcolatore & Logica Scontistica

Regole Tariffarie Incorporate

Quota Associativa & Assicurativa: € 30,00 / allievo (comprensiva di T-Shirt e copertura fino al 31/08/2027).

Sconto Famiglia / Fratelli: -20% applicato dal secondo componente familiare.

Piani di Pagamento:

Trimestrale: Iscrizione + 3 Tranche (Ott/Nov/Dic, Gen/Feb/Mar con scadenza 25 Dic, Apr/Mag/Giu con scadenza 27 Mar).

Due Soluzioni (Semestrale): Iscrizione + 50% corsi alla firma, Saldo 50% entro il 12 Febbraio 2027.

Eccezioni Specifiche:

Arte Creativa: Mese di settembre in omaggio.

Judo: Quota aggiuntiva per il mese di settembre (€25 - €45 a seconda della frequenza).

Fascia Baby: Possibilità di pagamento mensile per il solo 1° trimestre.

📅 Modulo Orari & Filtri Interattivi

L'orario settimanale include l'intero database di A.A. 2026/2027 (rev. 31/08/2026) suddiviso per le 5 sale operative del Polo UGART.

Filtri Disponibili:

Giorno della Settimana: LUN, MAR, MER, GIO, VEN.

Fascia d'Età: All, Baby, Bimbi, Junior, Ragazzi, Senior.

Area Disciplina: Circo & Acrobatica, Pole Dance, Arti Marziali, Fitness & Posturale, Arte & Cultura.

Ricerca Testuale Libera: Ricerca per nome corso o numero di sala (es. Acrobatica, Sala 1).

📄 Moduli di Stampa PDF (A4)

L'applicazione genera due moduli distinti per la stampa o l'esportazione in PDF via browser:

1. Modulo 1: Preventivo Economico Sintetico

Intestazione formale Railim Solutions / UGART.

Dettaglio allievi con le relative discipline ed orari abbinati.

Tabella delle tranche calcolate con le scadenze tassative e importi esatti.

Note legali e campi firma per Genitore/Atleta e Segreteria.

2. Modulo 2: Planner Settimanale Familiare (07:00 – 22:00)

Matrice oraria continua dalle 07:00 alle 22:00 per i 5 giorni lavorativi.

Posizionamento automatico delle lezioni UGART frequentate dagli allievi.

Righe e spazi compilabili a mano per impegni scolastici, compiti e appuntamenti personali della famiglia.

🚀 Guida all'Installazione e Deploy

Non è richiesta alcuna compilazione o installazione di pacchetti Node.js.

Opzione A: Pubblicazione via Vercel / GitHub (Consigliata)

Crea un repository su GitHub e rinomina il file principale in index.html.

Collega il repository a Vercel o GitHub Pages.

Ottieni un URL pubblico SSL istantaneo (es. https://ugart-calculator.vercel.app).

Opzione B: Uso Locale / Tablet Segreteria

Scarica il file ugart_calculator.html.

Apri il file facendo doppio click su qualsiasi browser (Chrome, Safari, Edge, Firefox) su PC, Mac o Tablet iPad/Android.

💼 Valutazione Commerciale & Offerta

L'applicazione rappresenta una soluzione gestionale ad alto valore per centri sportivi e artistici.

Schema di Proposta d'Acquisto per UGART:

Modalità

Dettagli dell'Offerta

Importo Indicativo

Opzione A — Licenza d'Uso Chiavi in Mano (One-Off)

• Cessione del software personalizzato col brand UGART



• Integrazione nel sito ufficiale www.ugacademy.it



• File unico autonomo senza canoni di hosting

€ 450,00 – € 650,00 (una tantum)

Opzione B — Pacchetto Software + Supporto Annuale

• Licenza d'uso completa



• Aggiornamento annuale listini/orari per A.A. 2027/2028



• Assistenza tecnica e personalizzazioni

€ 350,00 setup + € 150,00 / anno

📞 Contatti e Sviluppo

Sviluppato da: Railim Solutions

Committente / Partner: Polo Artistico Ludico Sportivo — Urban Gravity Academy A.S.D. & A.C.

Sito Web: www.ugacademy.it

Sede: Via Domenico Pisani 1, 27029 Vigevano (PV)

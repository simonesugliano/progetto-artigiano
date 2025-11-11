[![Visita il sito ArtiTam](https://img.shields.io/badge/🌐_Visita_il_sito-ArtiTam.altervista.org-4CAF50?style=for-the-badge&logo=google-chrome&logoColor=white)](https://artitam.altervista.org)

[![Stato del repository Auto-Updated](https://img.shields.io/badge/Status-Auto--Updated-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tuo-utente/tuo-repo)  
[![Sorgente Google Drive](https://img.shields.io/badge/Source-Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com)  
[![Frontend React](https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org)  
[![Hosting Altervista](https://img.shields.io/badge/Hosting-Altervista-orange?style=for-the-badge&logo=altervista&logoColor=white)](https://it.altervista.org)  
[![Sync via GitHub API](https://img.shields.io/badge/Sync-GitHub%20API-black?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/en/rest)



# Progetto Artigiano

**Progetto Artigiano** è un sito monopagina in **React** e **Bootstrap**, progettato per un **artigiano rteale** che lavora nel settore del cartongesso e vuole farsi conoscere online attraverso i propri lavori.  
Il sito nasce come vetrina moderna, pulita e ottimizzata **SEO on-page**, pensata per mostrare professionalità e competenza.  

---

## Progressi e nuove funzioni

- [Wireframe e struttura](./documents/wireframe)  
  Schema visivo e architettura del sito, con suddivisione delle sezioni e logica di navigazione.


---

## Obiettivo

Crearfe una piattaforma **semplice da gestire**, ma **tecnicamente solida**:  
un sito che si aggiorna automaticamente con nuove foto dei lavori, offre una navigazione fluida e responsive, e in futuro **pubblicherà in automatico i contenuti anche sui social**.

---

## Tecnologie
- **React 18** → gestione componenti e struttura dinamica  
- **Bootstrap 5** → layout responsive e griglie fluide  
- **Swiper.js** → caroselli per gallery e collaborazioni  
- **JSON dinamico** → per aggiornare in tempo reale la gallery  
- **SEO semantico avanzato** → struttura e tag ottimizzati  
- **Hosting su Altervista** → versione statica buildata da Vite  

---

## Sezioni principali
- **Top / Hero** → immagine principale con payoff e call to action  
- **Chi sono** → presentazione dell’artigiano e filosofia di lavoro  
- **Gallery** → lavori suddivisi per categoria, **aggiornati automaticamente**  
- **Collaborazioni** → imprese e professionisti con cui lavora  
- **Dove lavoro** → aree servite e informazioni logistiche  
- **Contatti / Preventivo** → form contatto e link social  
- **Footer** → privacy, note legali e credit

---

## Funzionalità chiave
- **Caicamento automatico delle foto** da una cartella locale o cloud  
- **Gallery aggiornata in tempo reale** tramite file JSON  
- **SEO ottimizzata fin dall’inizio** per visibilità nei motori di ricerca  
- **Layout completamente responsive** per desktop e mobile  
- **Futura automazione social** pr la pubblicazione automatica dei post  

---

## Fasi di sviluppo

1. **Setup locale con React + Bootstrap**  
   Creazione della struttura base del sito monopagina, con componenti modulari, layout responsivo e immagini segnaposto per impostare il design complessivo.  

2. **Dynamic Gallery con JSON**  
   Implementazione di un sistema di galleria completamente automatizzato basato su un file `gallery.json` centralizzato.  
   Il file viene generato da uno **script Google Apps Script** che scandisce una cartella Drive dedicata, raccoglie i metadati (nome file, percorso, descrizione, timestamp, ecc.) e li esporta in formato JSON strutturato.  
   Lo script effettua quindi un **commit automatico tramite GitHub API**, aggiornando il repository renmoto ogni volta che vengono aggiunte o rimosse immagini.  
   Sul lato front-end, l’app React esegue una **fetch asincrona** del `gallery.json` per costruire dinamicamente la griglia delle immaginigestendo caricamento progressivo, fallback e caching locale per ottimizzare le performance e ridurre i tempi di rendering.  
   In uesto modo la galleria resta **sincronizzata in tempo reale** con gli upload del cliente, senza richiedere alcun intervento manuale.

3. **Social automation**  
   Script backend per post automatici su Facebook e Instagram. **SARA' IMPLEMENTATO A SEGUIRE**
   
5. **Deploy e ottimizzazione SEO**  
   Creazione della build statica ottimizzata e pubblicazione finale su **Altervista**, con configurazione personalizzata per il corretto funzionamento di React in ambiente statico.  
   Sono stati aggiunti meta tag dinamici, schema `JSON-LD` per il markup **LocalBusiness**, favicon multi-dispositivo e gestione delle immagini in formato **WebP/AVIF** per migliorare le prestazioni e l’indicizzazione.  
   La struttura del sito è stata ottimizzata secondo le linee guida **Core Web Vitals**, con caricamento asincrono degli asset, lazy load delle immagini e compressione delle risorse.  
   Infine, è stato implementato il redirect automatico da HTTP a HTTPS e la verifica di compatibilità cross-browser per garantire accessibilità e SEO locale ottimale.


---

## Autore
Sito progettato e sviluppato da **Simone Sugliano**.  
Progetto reale destinato a un artigiano, nato per coniugare **design moderno, automazione e visibilità locale**.  
Esempio concreto di come la tecnologia possa dare valore al lavoro manuale e atigianale.


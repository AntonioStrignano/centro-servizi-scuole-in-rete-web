# Struttura Sito - Centro Servizi Scuole In Rete s.r.l.

## Obiettivo del documento
Definire la struttura del sito vetrina prima della fase di sviluppo.
Questo file è il riferimento per sitemap, contenuti, SEO e componenti condivisi.

## 1) Architettura pagine (Sitemap)
- Home
- Servizi (overview)
- Servizio Formazione
- Servizio Consulenza
- Servizio Progettazione
- Servizio Comunicazione
- Contatti
- Privacy Policy
- Cookie Policy
- Dichiarazione di accessibilità

## 2) Navigazione principale
- Logo (link alla Home)
- Voce: Home
- Voce: Servizi
- Voce: Contatti
- CTA header primaria: Richiedi informazioni
- CTA header secondaria: Chiama ora

## 3) Footer normativo (completo)
- Ragione sociale: Centro Servizi Scuole In Rete s.r.l.
- P.IVA / CF: 06119770722
- PEC: centroserviziscuoleinretesrl@pec.it
- SDI: W7YVJK9
- REA: 463388
- Indirizzo: Via U. Foscolo, 3 - 76123 Andria (BT)
- Email: direzione@scuoledinfanzia.it
- Telefono: 0883.566868
- Link: Privacy Policy
- Link: Cookie Policy
- Link: Dichiarazione di accessibilità

## 4) Struttura contenuto per pagina

### Home
- Hero
  - Headline orientata a consulenza per scuole ed enti privati
  - Sottotitolo con valore operativo (amministrazione, contabilità, gestione)
  - CTA primaria: Richiedi informazioni
  - CTA secondaria: Chiama ora
- Blocco fiducia
  - Oltre 30 anni di esperienza
  - Oltre 300 scuole seguite
  - Convegni esclusivi per clienti
- Panoramica servizi (4 card)
- Come lavoriamo (processo in 3-4 step)
- Richiamo finale CTA

### Servizi (overview)
- Intro pagina servizi
- Griglia 4 servizi con sintesi e link alle pagine dedicate
- Blocco "Per chi lavoriamo" (scuole paritarie + enti privati)
- CTA finale

### Pagina Servizio (template unico per 4 servizi)
- Titolo servizio
- Problema che risolve
- Soluzione proposta
- Attività incluse
- Benefici/Risultati attesi
- FAQ breve (3-5 domande)
- CTA finale (email/call)

### Contatti
- Titolo + testo orientato a presa contatto
- Blocchi contatto: email, telefono, sede
- Mappa
- Fascia oraria/tempi risposta (se disponibili)
- CTA primaria e secondaria

### Privacy Policy
- Pagina legale completa (testo da predisporre)

### Cookie Policy
- Pagina legale completa (testo da predisporre)

### Dichiarazione di accessibilità
- Pagina con stato di conformità, contatti per segnalazioni, data aggiornamento

## 5) SEO base (prima versione)

### Cluster principale
- consulenza scuole paritarie
- consulenza amministrativa scuole paritarie
- contabilità scuole paritarie
- gestione paghe scuole paritarie
- consulenza enti privati settore istruzione
- servizi amministrativi scuole private

### Mappa keyword primaria per pagina
- Home: consulenza scuole paritarie
- Servizio Formazione: formazione docenti scuole paritarie
- Servizio Consulenza: consulenza amministrativa scuole paritarie
- Servizio Progettazione: progettazione scolastica MIUR
- Servizio Comunicazione: comunicazione scuola famiglie personale
- Contatti: consulenza scuole private Andria

## 6) CTA e conversione
- CTA principale globale: Richiedi informazioni (email)
- CTA secondaria globale: Chiama ora
- Posizionamento CTA: header, hero, fine sezione servizi, fondo pagina
- Microcopy da definire in fase copy finale

## 7) Accessibilità (requisiti minimi)
- Contrasto colore adeguato
- Navigazione da tastiera completa
- Focus visibile su elementi interattivi
- Testi alternativi per immagini
- Struttura heading semantica corretta (H1-H2-H3)
- Label esplicite per link e pulsanti

## 8) Struttura dati condivisi (properties)
Obiettivo: centralizzare i dati per riuso su tutte le pagine.

### Dati da centralizzare
- Ragione sociale
- P.IVA / CF
- PEC
- SDI
- REA
- Indirizzo completo
- Email
- Telefono
- CTA principale
- CTA secondaria

### Nota implementativa
Se il progetto resta statico, usare un file di configurazione unico (es. JSON/YAML/TS) da cui leggere i dati nelle varie pagine/componenti.

## 9) Asset visual
- Logo già disponibile
- Immagini stock da selezionare per ogni sezione
- Set icone coerente con tono istituzionale

## 10) Uscita fase progettazione (Definition of Ready)
Per iniziare sviluppo:
- Sitemap approvata
- Struttura pagine approvata
- Keyword primaria per pagina approvata
- Footer normativo validato
- Strategia dati condivisi (properties) scelta

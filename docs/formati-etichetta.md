---
title: "Formati Etichetta: layout di scontrino ed etichetta"
date: "2025-04-10"
categoria: software Hyperetail
---

<!-- categoria assegnata per inferenza: verificare (la bilancia Icona non ha una categoria dedicata nell'elenco) -->

# Formati Etichetta: layout di scontrino ed etichetta

**Target:** tecnico installatore / rivenditore · **Video:** Custom Academy, webinar *Icona configurazione di base* (10/04/2025), dal minuto 57:37 al 61:45.

## Obiettivo

Al termine sai preparare i **layout dello scontrino** (intestazione e coda) partendo dai formati pre-impostati, copiarli nel proprio banco con il numero corretto e personalizzarli nell'editor grafico. Sai inoltre come portare nel banco un formato di **etichetta**.

## Prerequisiti

- L'[intestazione dello scontrino](intestazioni-operatori-testi.md) è stata creata (nell'archivio **Intestazioni**).
- Il relatore ha già mostrato in precedenti webinar come creare e modificare le etichette graficamente: qui si concentra su ciò che è importante spiegare.

## Il concetto chiave

!!! warning "Anche lo scontrino è un'etichetta"
    Il layout grafico dello scontrino è **anch'esso un'etichetta**, con un **formato standardizzato**:

    - il formato **50** è la **testa** (intestazione) dello scontrino;
    - il formato **51** è la **coda** dello scontrino.

    Chi configura la bilancia può essere mandato fuori pista da questo: la domanda tipica è "come attivo il **QR code** oppure l'**EAN** sotto lo scontrino?". La risposta è **qui**, nei formati 50 e 51.

I formati **50 e 51 fanno riferimento ai layout di stampa dello scontrino**; le etichette sono un'altra cosa (vedi più sotto).

## Passaggi

### 1. Apri Formati Etichetta

> Nel video: 57:37

Da **Archivi Dati** scorri la lista in basso e tocca **Formati Etichetta**.

![Archivi Dati: Formati Etichetta](assets/images/fe-01-menu-archivi-dati.png)

La lista del banco è vuota. Le colonne sono **Formato**, **Descrizione**, **Larg (mm)** e **Lung (mm)**; il pulsante **+** crea un formato. In basso ci sono due gruppi di icone: due a sinistra (una stampante e un monitor) e cinque a destra.

![Formati Etichetta: lista vuota del banco](assets/images/fe-02-lista-formati-vuota.png)

### 2. Apri la lista dei formati pre-impostati

> Nel video: 57:52

Tocca la **prima icona del gruppo in basso a destra** (il blocco appunti con la scritta *Fx*): si apre la **Lista Formati Pre-Impostati**, cioè i **formati fissi**, una serie di layout grafici di etichetta già predisposti.

![Prima icona del gruppo a destra evidenziata, apertura in corso](assets/images/fe-02b-apertura-lista-preimpostati.png)

![Lista Formati Pre-Impostati, parte alta: formati da 1 a 12](assets/images/fe-03-lista-preimpostati.png)

Scorrendo la lista in basso si incontrano, tra gli altri, i formati per lo scontrino:

| Formato | Descrizione | Larg x Lung (mm) |
|---|---|---|
| 80 | INTESTAZIONE SCONTRINO | 60,0 x 19,5 |
| 81 | INTESTAZIONE SCONTRINO + LOGO | 60,0 x 15,0 |
| 82 | TRANSAZIONE 2desc.+Lotto+TLL | 60,0 x 17,0 |
| 85 | CODA SCONTRINO EAN13 | 60,0 x 23,0 |
| 86 | CODA SCONTRINO QrCode | 60,0 x 38,0 |
| 90 | TRACCIABILITA' Box | 60,0 x 24,0 |

![Lista Formati Pre-Impostati: formati dello scontrino](assets/images/fe-04-lista-preimpostati-scorrimento.png)

### 3. Copia l'intestazione con logo nel formato 50

> Nel video: 58:51

1. Nella lista dei pre-impostati seleziona **81 - INTESTAZIONE SCONTRINO + LOGO** (il relatore ha bisogno dell'intestazione con il logo).
2. Conferma con la **spunta**: compare il tastierino **Formato Fisso : 81 => Nuovo Formato ...**.
3. Digita **50**, cioè il numero del formato dell'intestazione dello scontrino, e conferma con **Ok**.

    ![Tastierino: Formato Fisso 81 => Nuovo Formato](assets/images/fe-05-copia-formato-81.png)

4. Compare la richiesta **Eseguo la copia nel Banco Attuale ?**. Tocca **Sì**.

    ![Conferma della copia nel banco attuale](assets/images/fe-06b-conferma-copia.png)

Il formato **50** compare ora nella lista del banco.

![Lista del banco con il formato 50](assets/images/fe-06-lista-formato-50.png)

### 4. Copia la coda con EAN13 nel formato 51

> Nel video: 59:09

Ripeti con la coda: riapri la **Lista Formati Pre-Impostati**, seleziona **85 - CODA SCONTRINO EAN13** (il relatore vuole lavorare con l'EAN13), conferma e digita **51** come nuovo formato.

![Selezione di CODA SCONTRINO EAN13 nella lista dei pre-impostati](assets/images/fe-07-coda-scontrino-ean13.png)

!!! tip "QR code al posto dell'EAN13"
    Se invece sotto lo scontrino serve un QR code, nella stessa lista esiste **86 - CODA SCONTRINO QrCode**. Il relatore usa l'EAN13 nell'esempio.

La lista del banco mostra ora i formati **50** e **51**.

![Lista del banco: formati 50 e 51](assets/images/fe-08-lista-50-51.png)

### 5. Personalizza il formato nell'editor grafico

> Nel video: 59:24

Con il formato selezionato apri l'editor grafico: rispetto all'etichetta lì si può **personalizzare praticamente tutto**. Il relatore ingrandisce e poi riduce lo zoom per vedere l'intero layout.

![Editor grafico a zoom elevato](assets/images/fe-09b-editor-grafico-zoom.png)

![Editor grafico a zoom ridotto: logo in alto e righe di intestazione](assets/images/fe-09-designer-intestazione.png)

<!-- verificare: nel video l'apertura dell'editor avviene tra 59:31.3 e 59:31.7 con un tocco sulla fila di icone in basso a destra, senza commento; l'icona esatta va confermata sulla bilancia -->

!!! warning "Da verificare"
    Il relatore apre l'editor con un solo tocco sulle icone in basso a destra della lista e non indica quale. Controlla sulla bilancia l'icona dell'editor grafico.

**Obiettivo dell'esempio**: avere il **logo in alto** e l'**intestazione sotto**. Servono due modifiche.

**a) Aumenta la lunghezza dell'etichetta.** Torna alla lista, seleziona il formato e tocca la **lente**: si apre il dettaglio **Lista Formati** con **ID Formato** (50), **Descrizione Formato**, **Larghezza Etichetta (mm)** (60,0) e **Lunghezza Etichetta (mm)** (15,0).

![Dettaglio del formato 50: larghezza e lunghezza](assets/images/fe-10b-dettaglio-formato-50.png)

Tocca la **matita**, poi il campo **Lunghezza Etichetta (mm)** e portala da 15,0 a **35**: serve per avere spazio sopra.

![Tastierino Lunghezza Etichetta (mm)](assets/images/fe-10-lunghezza-etichetta.png)

**b) Adatta il logo.** Rientra nello scontrino (editor grafico) e tocca l'oggetto del logo: il pannello a sinistra mostra le sue proprietà (**Base**: Allineamento, Altezza (mm), Descrizione, Direzione Campo, Id Tipo, Lunghezza (mm), Num. Campo, Opzioni Stampa, Posizione x (mm), Posizione y (mm), Tipo Campo; **Estese**: Anteprima).

![Editor con l'oggetto logo selezionato in alto](assets/images/fe-11-designer-logo.png)

![Proprietà dell'oggetto: Lunghezza (mm) 22, Altezza (mm) 13,5](assets/images/fe-12-proprieta-oggetto.png)

Tocca **Lunghezza (mm)**: il tastierino **Lunghezza (mm)-Larghezza dell'oggetto in pixel** mostra il valore attuale (**22**). Il relatore lo porta a **60**, così il logo occupa tutta la larghezza.

![Tastierino Lunghezza (mm) dell'oggetto](assets/images/fe-13-lunghezza-oggetto.png)

Lo stesso vale per l'**altezza**: tocca **Altezza (mm)** e inserisci il nuovo valore.

![Tastierino Altezza (mm) dell'oggetto](assets/images/fe-14-altezza-oggetto.png)

![Il logo adattato occupa tutta la larghezza](assets/images/fe-15-designer-dopo.png)

!!! danger "Salva le modifiche"
    Per salvare tocca il **dischetto** in alto a destra nell'editor. Se invece tocchi la **freccia indietro** si **perdono tutte le modifiche** fatte.

La lista del banco mostra ora il formato 50 con lunghezza **35,0**.

![Lista del banco: formato 50 con lunghezza 35,0](assets/images/fe-16-lista-50-modificato.png)

### 6. Stessa procedura per la coda

> Nel video: 61:01

Lo stesso procedimento vale per la **coda** (formato 51): nell'editor si vede il layout con le righe di testo e il **codice a barre EAN13**.

![Editor grafico della coda con il codice a barre](assets/images/fe-17-designer-coda.png)

Il relatore riassume: sono "le cose basiche" che permettono una **prima installazione** della bilancia; quando la bilancia sarà disponibile si potrà personalizzare questa parte.

### 7. Portare nel banco un formato etichetta

> Nel video: 61:17

Le **etichette** funzionano in modo diverso dallo scontrino. Si prende un'etichetta dalla lista dei pre-impostati, la si riporta nel proprio banco e, come dice il relatore, **a questo punto deve essere il formato numero uno**.

Nell'esempio si seleziona il formato **4** (*2R. Intestazione - 2 Desc. - 5R. Ingredienti*, 60,0 x 65,0)...

![Lista Formati Pre-Impostati con il formato 4 selezionato](assets/images/fe-18-formato-4.png)

...lo si copia con il tastierino **Formato Fisso : 4 => Nuovo Formato ...** digitando **1**...

![Tastierino: Formato Fisso 4 => Nuovo Formato](assets/images/fe-19-copia-formato-4.png)

...e il formato **1** compare nella lista del banco, accanto ai formati 50 e 51.

![Lista del banco: formati 1, 50 e 51](assets/images/fe-20-lista-formato-1.png)

Anche qui si entra nell'**editor grafico** del layout dell'etichetta e lo si personalizza con i campi che servono.

![Editor grafico del layout dell'etichetta](assets/images/fe-21-designer-etichetta.png)

<!-- verificare: la trascrizione cita "formato per esempio 65"; sullo schermo il formato copiato e' il 4, che ha lunghezza 65,0 mm -->

## Verifica

La lista **Formati Etichetta** del banco contiene **1** (etichetta), **50** (INTESTAZIONE SCONTRINO + LOGO, lunghezza 35,0) e **51** (CODA SCONTRINO EAN13). Ricorda: **50 e 51 sono i layout dello scontrino**, non delle etichette.

!!! tip "Prossimo passo"
    L'ultima area mostrata è la costruzione dei codici a barre: pagina [Formati Barcode](formati-barcode.md).

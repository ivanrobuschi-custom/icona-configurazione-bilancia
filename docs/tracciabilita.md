---
title: "Tracciabilità e lotti: definizioni, lotti e uso in vendita"
date: "2026-10-25"
categoria: software Hyperetail
---

<!-- categoria assegnata per inferenza: verificare (la bilancia Icona non ha una categoria dedicata nell'elenco) -->

# Tracciabilità e lotti: definizioni, lotti e uso in vendita

**Target:** tecnico installatore / rivenditore.

## Obiettivo

Configurare la **tracciabilità**: creare le **definizioni**, inserire i **lotti** con peso e giacenza, attivare la tracciabilità sul banco e sugli articoli, e usare i lotti in vendita e in etichettatura. Distinguere la tracciabilità dal **lotto di produzione**.

## Che cos'è la tracciabilità

È un **obbligo di legge** per alcune categorie di alimenti, in particolare **carni** e **pesce**; con il tempo diventa obbligatoria anche per altri prodotti (alcune tipologie di frutta, per esempio). La tracciabilità della bilancia Icona viene gestita in modo rigoroso: oltre ai dati del lotto c'è anche il **controllo del peso** del lotto venduto.

!!! warning "Tracciabilità e lotto di produzione sono due cose diverse"
    - **Tracciabilità**: i dati obbligatori di origine del prodotto (per le carni: macellato in, sezionato in, allevato in, numero di approvazione...), registrati per **lotto di acquisto**.
    - **Lotto di produzione**: un codice con cui **identificare un prodotto lavorato in proprio** (per esempio una torta). Può coesistere con la tracciabilità. Vedi [Etichettatura in vendita](etichettatura.md).

## Come è organizzata

Nel menu **Setup Bilancia**, sezione **Tracciabilità**, trovi due voci:

| Voce | Cosa contiene | Quando si configura |
|---|---|---|
| **Definizioni Tracciabilità** | Le "domande" che la bilancia pone quando si registra un lotto | **Una sola volta** |
| **Lotti Tracciabilità** | I lotti veri e propri, con le risposte alle definizioni, il peso e la giacenza | Ogni volta che arriva un lotto (per esempio ogni settimana) |

![Menu Tracciabilità: Definizioni Tracciabilità e Lotti Tracciabilità](assets/images/trac-01-menu-tracciabilita.jpg)

## Prerequisiti

- Il banco ha **Abilita Tracciabilità** attivo ([Lista Banchi](lista-banchi.md)).
- Le categorie e gli articoli da tracciare esistono ([Articoli PLU](articoli-plu.md)).

## Procedura

### 1. Controlla le definizioni esistenti

Tocca **Definizioni Tracciabilità**. La lista ha le colonne **Definizione** e **Definizione ID**. Sulla bilancia di esempio sono già presenti **CARNI** (1) e **MACINATO** (2).

![Lista delle definizioni di tracciabilità](assets/images/trac-02-lista-definizioni.jpg)

### 2. Le definizioni di default

Apri la definizione **CARNI**: scheda **Generale** con **Codice Definizione** e **Definizione ID Tracciabilità**.

![Definizione CARNI: codice e ID](assets/images/trac-03-definizione-carni.jpg)

Nella scheda **Definizioni** ci sono le **righe** (da Riga 01 in avanti): ogni riga è una domanda obbligatoria per la tracciabilità delle carni.

![Righe della definizione CARNI](assets/images/trac-04-righe-carni.jpg)

| Riga | Definizione CARNI |
|---|---|
| 01 | CODICE TRACCIABILITA' |
| 02 | MACELLATO IN: |
| 03 | N.APPROVAZIONE MACELLO: |
| 04 | SEZIONATO IN: |
| 05 | N.APPROVAZIONE SEZIONAMENTO: |
| 06 | ORIGINE: |
| 07 | ALLEVATO IN: |

![Seconda parte delle righe della definizione CARNI](assets/images/trac-05-righe-carni-seconda-parte.jpg)

La definizione **MACINATO** è simile e ridotta, con in più il reparto in cui è stato preparato (**PREPARATO IN:**).

![Selezione della definizione MACINATO](assets/images/trac-06-seleziona-macinato.jpg)

![Righe della definizione MACINATO](assets/images/trac-07-righe-macinato.jpg)

| Riga | Definizione MACINATO |
|---|---|
| 01 | CODICE TRACCIABILITA' |
| 02 | MACELLATO IN: |
| 03 | N.APPROVAZIONE MACELLO: |
| 04 | ORIGINE: |
| 05 | PREPARATO IN: |

### 3. Crea una definizione personalizzata

Non sei obbligato a usare i dati di legge proposti. Se il cliente (per esempio un macellaio) vuole gestire solo **numero di lotto e provenienza**, crea una definizione su misura, anche se gli si è fatto presente che per la tracciabilità sarebbe meglio gestire tutti i dati.

1. Tocca **+** in **Definizioni Tracciabilità** e digita il codice (nell'esempio **3**).
2. Scrivi il nome della definizione (**Definizione ID Tracciabilità**), per esempio **PERSONALE** o il nome del cliente.

    ![Tastiera per il nome della definizione](assets/images/trac-08-nome-definizione-tastiera.jpg)

3. Nella scheda **Definizioni** scrivi le righe: nell'esempio **CODICE LOTTO** (Riga 01), **ALLEVATO** (Riga 02) e **SEZIONATO** (Riga 03). Le altre righe restano vuote.

    ![Riga 01: CODICE LOTTO](assets/images/trac-09-riga1-codice-lotto.jpg)

    ![Riga 02: ALLEVATO](assets/images/trac-10-riga2-allevato.jpg)

    ![Riga 03: SEZIONATO](assets/images/trac-11-riga3-sezionato.jpg)

    ![Definizione PERSONALE con le tre righe](assets/images/trac-12-definizione-personale.jpg)

La lista mostra ora tre definizioni.

![Lista con le tre definizioni: CARNI, MACINATO, PERSONALE](assets/images/trac-13-lista-tre-definizioni.jpg)

### 4. Inserisci un lotto

Quando arriva un lotto (per esempio i lotti settimanali di carne) lo registri in **Lotti Tracciabilità**.

![Voce Lotti Tracciabilità](assets/images/trac-14-menu-lotti.jpg)

La lista ha le colonne **Lotto**, **Definizione**, **Lotto ID**, **Peso Lotto** e **Peso Giacenza**. Il **Peso Giacenza** è il peso residuo del lotto: scende man mano che si vende.

![Lista dei lotti: peso lotto e peso giacenza](assets/images/trac-15-lista-lotti.jpg)

1. Tocca **+** e digita il **Codice Lotto** (nell'esempio **3**).

    ![Tastierino Codice Lotto](assets/images/trac-16-codice-lotto-tastierino.jpg)

2. Nella scheda **Generale** compaiono **Codice Lotto**, **Lista Definizioni Associata**, **Lotto ID**, **Peso Lotto**, **Peso Giacenza** e **Scarto %**.

    ![Scheda Generale del lotto](assets/images/trac-17-lotto-generale.jpg)

3. **Lista Definizioni Associata**: con la lente scegli la definizione (nell'esempio **PERSONALE**).

    ![Lista Definizioni Associata](assets/images/trac-18-lista-definizioni-associate.jpg)

4. **Lotto ID**: il riferimento del lotto (per esempio **VRE5678**). Non è il codice dell'articolo, anche se può coincidere; spesso i lotti riportano sulle etichette dei fornitori un riferimento proprio.

    ![Tastiera per il Lotto ID](assets/images/trac-19-lotto-id-tastiera.jpg)

5. **Peso Lotto**: se vuoi gestire la **giacenza**, indica il peso del lotto (nell'esempio **10 kg**).

    ![Tastierino del Peso Lotto](assets/images/trac-20-peso-lotto-tastierino.jpg)

6. Nella scheda **Righe Lotto** trovi le domande della definizione scelta: **[01] - CODICE LOTTO**, **[02] - ALLEVATO**, **[03] - SEZIONATO**. Compila le risposte.

    ![Righe Lotto: le domande della definizione](assets/images/trac-21-righe-lotto.jpg)

    ![Risposta alla riga CODICE LOTTO](assets/images/trac-22-riga-codice-lotto.jpg)

    ![Risposta alla riga ALLEVATO](assets/images/trac-23-riga-allevato.jpg)

    ![Risposta alla riga SEZIONATO](assets/images/trac-24-riga-sezionato.jpg)

!!! tip "Nazioni: solo tre lettere"
    Quando una riga chiede una **nazione** (allevato in, sezionato in), scrivi solo le **prime tre lettere** (per esempio **ITA**).

Il nuovo lotto compare nella lista con peso lotto e giacenza.

![Lista lotti con il terzo lotto: peso lotto 10,000](assets/images/trac-25-lista-lotti-con-terzo.jpg)

### 5. Attiva la tracciabilità su banco e articolo

Per usare i lotti:

1. **Banco**: **Abilita Tracciabilità** attivo ([Lista Banchi](lista-banchi.md)).
2. **Articolo**: nella scheda **Tracciabilità** dell'articolo scegli il tipo (**Standard**). Nella lista articoli la colonna **Tracc.** mostra *Star*. Il **Lotto Predefinito** di norma non si assegna ai prodotti tracciati, perché il lotto varia ogni settimana ([Articoli PLU](articoli-plu.md)).
3. **Formato etichetta**: deve prevedere i campi di tracciabilità ([Formati Etichetta](formati-etichetta.md)).

## Uso in vendita e in etichettatura

In etichettatura avanzata, dopo aver scelto l'articolo, si **seleziona il lotto tracciabile** da usare. L'etichetta stampa i dati della tracciabilità richiesti dal cliente.

![Vendita: tasti funzione, tra cui il tasto LOT](assets/images/trac-26-vendita-tasti-lotto.jpg)

Con i tasti funzione della vendita (nell'immagine il tasto **LOT** in alto a destra) si apre la schermata **Imposta Lotto**, con l'elenco dei lotti (**Codice**, **ID Lotto**, **Peso Lotto**) tra cui scegliere.<!-- verificare: il tasto che apre Imposta Lotto è dedotto dalla schermata; controllare la funzione assegnata al tasto LOT -->


![Imposta Lotto: elenco dei lotti](assets/images/trac-27-imposta-lotto.jpg)

![Articolo selezionato con il lotto scelto](assets/images/trac-28-articolo-con-lotto.jpg)

Se un lotto è in esaurimento e bisogna passare a un altro, si può aggiungere un nuovo lotto direttamente dalla schermata di vendita, con un **tasto dedicato** (vedi [Configurazione Tastiera](configurazione-tastiera.md)): porta direttamente alla schermata dei lotti tracciabili, senza passare per i menu *definizioni* e *lotti*, perché serve solo inserire il lotto di riferimento.

Man mano che si etichetta, il **peso giacenza** del lotto **scala**: nell'esempio il lotto da 10 kg scende a 9,966 dopo una pesata da 34 g.

![Lista lotti in vendita con la giacenza che scala](assets/images/trac-29-lista-lotti-in-vendita.jpg)

![Imposta Lotto: giacenza aggiornata](assets/images/trac-30-imposta-lotto-giacenza.jpg)

## Verifica

1. Vendi o etichetta l'articolo tracciato scegliendo il lotto.
2. Controlla che l'etichetta stampi i dati richiesti dalla definizione.
3. In **Lotti Tracciabilità** controlla che il **Peso Giacenza** sia diminuito del peso venduto.

## Errori comuni

| Problema | Causa probabile | Rimedio |
|---|---|---|
| L'etichetta non stampa la tracciabilità | Articolo con tracciabilità disattivata, banco senza **Abilita Tracciabilità**, o formato etichetta senza i campi di tracciabilità | Controlla i tre punti (banco, articolo, formato) |
| Il lotto non compare in elenco | Lotto associato a una definizione diversa da quella attesa | Controlla **Lista Definizioni Associata** |
| La giacenza non scala | **Peso Lotto** lasciato a 0 | Indica il peso del lotto per gestire la giacenza |
| Le domande del lotto non sono quelle di legge | È stata scelta una definizione personalizzata | Usa **CARNI** o **MACINATO** se servono i dati obbligatori |

!!! tip "Prossimo passo"
    Come si usa l'etichettatura in vendita: [Etichettatura in vendita](etichettatura.md).

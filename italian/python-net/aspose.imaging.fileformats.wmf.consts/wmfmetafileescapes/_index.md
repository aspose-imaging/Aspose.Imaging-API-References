---
title: "Enumerazione WmfMetafileEscapes"
type: docs
weight: 150
url: /it/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

L'Enumerazione MetafileEscapes specifica le funzionalità del driver di stampa che potrebbero non essere<br/>                direttamente accessibili tramite i record WMF definiti nell'Enumerazione RecordType (sezione 2.1.1.1).

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| ABORTDOC | Interrompe l'elaborazione del documento corrente. |
| BANDINFO | Recupera o specifica le impostazioni relative al banding su un dispositivo, come il<br/>                numero di bande. |
| BEGIN_PATH | Apre un percorso. |
| CHECKJPEGFORMAT | Verifica se la stampante supporta un'immagine JPEG. |
| CHECKPNGFORMAT | Verifica se la stampante supporta un'immagine PNG. |
| CLIP_TO_PATH | Definisce una regione di ritaglio delimitata da un percorso. L'input DEVE essere una quantità a 16 bit<br/>                che definisce l'azione da eseguire. |
| CLOSE_CHANNEL | Lo stesso di ENDDOC. Vedi OPEN_CHANNEL. |
| DOWNLOADFACE | Imposta il nome del tipo di carattere su un dispositivo. |
| DOWNLOADHEADER | Istruisce il driver della stampante a scaricare insiemi di procedure PostScript. |
| DRAFTMODE | Indica che il driver della stampante DOVREBBE stampare solo testo, e nessuna grafica. |
| DRAWPATTERNRECT | Disegna un rettangolo con un modello definito. |
| ENABLEDUPLEX | Abilita o disabilita la stampa fronte/retro (duplex) su un dispositivo. |
| ENCAPSULATED_POSTSCRIPT | Invia dati arbitrari direttamente al driver della stampante. |
| ENDDOC | Notifica al driver della stampante che il lavoro di stampa corrente sta terminando. |
| END_PATH | Termina un percorso. |
| ENUMPAPERBINS | Recupera informazioni riguardo le sorgenti di diversi moduli su un<br/>                dispositivo di output. |
| ENUMPAPERMETRICS | Interroga il driver della stampante per le dimensioni della carta e altri dati dei moduli. |
| EPSPRINTING | Indica l'inizio e la fine di una sezione PostScript incapsulato (EPS). |
| EXTTEXTOUT | Disegna il testo utilizzando il carattere attualmente selezionato, il colore di sfondo e il colore del testo. |
| FLUSHOUT | Provoca lo svuotamento di tutti gli output in sospeso verso il dispositivo di output. |
| GETCOLORTABLE | Ottiene i valori della tabella dei colori. |
| GETDEVICEUNITS | Ottiene le unità del dispositivo attualmente configurate su un dispositivo di output. |
| GETEXTENDEDTEXTMETRICS | Ottiene le metriche di testo estese attualmente configurate su un output<br/>                dispositivo. |
| GETFACENAME | Ottiene il nome del tipo di carattere attualmente configurato su un dispositivo. |
| GETPAIRKERNTABLE | Ottiene la tabella di kerning del carattere attualmente definita su un dispositivo di output. |
| GETPHYSPAGESIZE | Recupera le dimensioni fisiche della pagina attualmente selezionate su un dispositivo di output. |
| GETPRINTINGOFFSET | Recupera lo scostamento dall'angolo superiore sinistro della pagina fisica<br/>                dove inizia la stampa o il disegno effettivo. |
| GETSCALINGFACTOR | Recupera i fattori di scala per l'asse x e l'asse y di una stampante. |
| GETSETPAPERBINS | Recupera o specifica la sorgente dei moduli di output su un dispositivo. |
| GETSETPAPERMETRICS | Recupera o specifica le dimensioni della carta e altri dati dei moduli su un<br/>                dispositivo di output. |
| GETSETPRINTORIENT | Recupera o specifica l'orientamento della carta su un dispositivo. |
| GETTECHNOLOGY | Ottiene informazioni sulla tecnologia grafica supportata su un<br/>                dispositivo. |
| GETVECTORBRUSHSIZE | Recupera la dimensione fisica del pennello attualmente definita su un dispositivo. |
| GETVECTORPENSIZE | Recupera la dimensione fisica della penna attualmente definita su un dispositivo. |
| GET_PS_FEATURESETTING | Ottiene informazioni su una impostazione di funzionalità specificata per un PostScript<br/>                driver di stampa. |
| METAFILE_DRIVER | Interroga un driver di stampa sul supporto dei metafile su un dispositivo di output<br/>                . |
| META_ESCAPE_ENHANCED_METAFILE | Usato per incorporare un formato di metafile avanzato (EMF)<br/>                metafile all'interno di un metafile WMF. |
| MXDC_ESCAPE | Consente alle applicazioni di scrivere documenti su un file o su una stampante in formato XML Paper<br/>                Specification (XPS). |
| NEWFRAME | Notifica al driver di stampa che l'applicazione ha terminato la scrittura su una pagina. |
| NEXTBAND | Notifica al driver di stampa che l'applicazione ha terminato la scrittura su una banda. |
| OPEN_CHANNEL | Lo stesso di STARTDOC specificato con un documento NULL e un nome file di output<br/>                , dati in modalità raw e un tipo zero. |
| PASSTHROUGH | Questo record passa dati arbitrari. |
| POSTSCRIPT_DATA | Invia dati PostScript arbitrari a un dispositivo di output. |
| POSTSCRIPT_IDENTIFY | Imposta il driver della stampante in modalità PostScript o GDI. |
| POSTSCRIPT_IGNORE | Notifica a un dispositivo di output di ignorare i dati PostScript. |
| POSTSCRIPT_INJECTION | Inserisce un blocco di dati grezzi in un flusso PostScript. L'input<br/>                DEVE essere una quantità a 32 bit che specifica il numero di byte da iniettare, una quantità a 16 bit<br/>                che specifica il punto di iniezione e una quantità a 16 bit che specifica il numero di pagina, seguita da<br/>                i byte da iniettare. |
| POSTSCRIPT_PASSTHROUGH | Invia dati arbitrari direttamente a un driver della stampante, che è<br/>                previsto elaborare questi dati solo quando è in modalità PostScript. [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/). |
| QUERYDIBSUPPORT | Interroga il driver della stampante sul suo supporto per i DIB su un dispositivo di output. |
| QUERYESCSUPPORT | Interroga un driver della stampante per determinare se una specifica funzione di escape<br/>                è supportata sul dispositivo di output che controlla. |
| SETABORTPROC | Imposta la funzione definita dall'applicazione che consente di annullare un lavoro di stampa<br/>                durante la stampa. |
| SETCOLORTABLE | Imposta i valori della tavola dei colori. |
| SETCOPYCOUNT | Imposta il numero di copie. |
| SETDIBSCALING | Specifica la scalatura delle bitmap indipendenti dal dispositivo (DIB). |
| SETLINECAP | Specifica la modalità di disegno delle linee da utilizzare nell'output verso un dispositivo. |
| SETLINEJOIN | Specifica la modalità di unione delle linee da utilizzare nell'output verso un dispositivo. |
| SETMITERLIMIT | Imposta il limite per la lunghezza delle giunzioni a spigolo da utilizzare nell'output verso un dispositivo. |
| SETPAPERSOURCE | Imposta l'origine, ad esempio un vassoio carta o un contenitore specifico su una stampante, per<br/>                i moduli di output. |
| SETPENWIDTH | Imposta la larghezza di una penna in pixel. |
| SPCLPASSTHROUGH2 | Consente alle applicazioni di includere procedure private e altri dati arbitrari<br/>                nei documenti. |
| STARTDOC | Notifica al driver della stampante che sta iniziando un nuovo lavoro di stampa. |

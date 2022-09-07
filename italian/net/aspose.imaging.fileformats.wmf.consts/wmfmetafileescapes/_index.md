---
title: WmfMetafileEscapes
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione MetafileEscapes specifica la funzionalità del driver della stampante che potrebbe non essere direttamente accessibile tramite i record WMF definiti nellenumerazione RecordType sezione 2.1.1.1.
type: docs
weight: 8230
url: /it/net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

L'enumerazione MetafileEscapes specifica la funzionalità del driver della stampante che potrebbe non essere direttamente accessibile tramite i record WMF definiti nell'enumerazione RecordType (sezione 2.1.1.1).

```csharp
public enum WmfMetafileEscapes
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Newframe | `1` | Notifica al driver della stampante che l'applicazione ha terminato la scrittura su una pagina. |
| Abortdoc | `2` | Interrompe l'elaborazione del documento corrente. |
| Nextband | `3` | Notifica al driver della stampante che l'applicazione ha terminato la scrittura su una banda. |
| Setcolortable | `4` | Imposta i valori della tabella dei colori. |
| Getcolortable | `5` | Ottiene i valori della tabella dei colori. |
| Flushout | `6` | Fa sì che tutti gli output in sospeso vengano scaricati sul dispositivo di output. |
| Draftmode | `7` | Indica che il driver della stampante DOVREBBE stampare solo testo e nessuna grafica. |
| Queryescsupport | `8` | Interroga un driver della stampante per determinare se una specifica funzione di escape è supportata sul dispositivo di output che guida. |
| Setabortproc | `9` | Imposta la funzione definita dall'applicazione che consente di annullare un lavoro di stampa durante la stampa. |
| Startdoc | `10` | Notifica al driver della stampante che sta iniziando un nuovo lavoro di stampa. |
| Enddoc | `11` | Notifica al driver della stampante che il lavoro di stampa corrente sta finendo. |
| Getphyspagesize | `12` | Recupera la dimensione fisica della pagina attualmente selezionata su un dispositivo di output. |
| Getprintingoffset | `13` | Recupera l'offset dall'angolo superiore sinistro della pagina fisica dove inizia la stampa o il disegno effettivo. |
| Getscalingfactor | `14` | Recupera i fattori di scala per l'asse x e l'asse y di una stampante. |
| MetaEscapeEnhancedMetafile | `15` | Utilizzato per incorporare un metafile EMF (Enhanced Metafile Format) all'interno di un metafile WMF. |
| Setpenwidth | `16` | Imposta la larghezza di una penna in pixel. |
| Setcopycount | `17` | Imposta il numero di copie. |
| Setpapersource | `18` | Imposta l'origine, ad esempio un vassoio carta particolare o uno scomparto su una stampante, per moduli di output. |
| Passthrough | `19` | Questo record passa attraverso dati arbitrari. |
| Gettechnology | `20` | Ottiene informazioni sulla tecnologia grafica supportata su un dispositivo . |
| Setlinecap | `21` | Specifica la modalità di disegno linea da utilizzare nell'output su un dispositivo. |
| Setlinejoin | `22` | Specifica la modalità di unione di riga da utilizzare nell'output su un dispositivo. |
| Setmiterlimit | `23` | Imposta il limite per la lunghezza dei giunti ad angolo da utilizzare nell'output su un dispositivo. |
| Bandinfo | `24` | Recupera o specifica le impostazioni relative alla banda su un dispositivo, come il numero di bande. |
| Drawpatternrect | `25` | Disegna un rettangolo con un motivo definito. |
| Getvectorpensize | `26` | Recupera la dimensione fisica della penna attualmente definita su un dispositivo. |
| Getvectorbrushsize | `27` | Recupera le dimensioni del pennello fisico attualmente definite su un dispositivo. |
| Enableduplex | `28` | Abilita o disabilita la stampa fronte/retro (duplex) su un dispositivo. |
| Getsetpaperbins | `29` | Recupera o specifica l'origine dei moduli di output su un dispositivo. |
| Getsetprintorient | `30` | Recupera o specifica l'orientamento della carta su un dispositivo. |
| Enumpaperbins | `31` | Recupera le informazioni relative alle sorgenti di forme diverse su un dispositivo di output . |
| Setdibscaling | `32` | Specifica il ridimensionamento delle bitmap (DIB) indipendenti dal dispositivo. |
| Epsprinting | `33` | Indica l'inizio e la fine di una sezione PostScript (EPS) incapsulata. |
| Enumpapermetrics | `34` | Richiede a un driver della stampante le dimensioni della carta e altri dati di moduli. |
| Getsetpapermetrics | `35` | Recupera o specifica le dimensioni della carta e altri dati di moduli su un dispositivo di output . |
| PostscriptData | `37` | Invia dati PostScript arbitrari a un dispositivo di output. |
| PostscriptIgnore | `38` | Notifica a un dispositivo di output di ignorare i dati PostScript. |
| Getdeviceunits | `42` | Ottiene le unità del dispositivo attualmente configurate su un dispositivo di output. |
| Getextendedtextmetrics | `256` | Ottiene metriche di testo estese attualmente configurate su un dispositivo di output . |
| Getpairkerntable | `258` | Ottiene la tabella kern dei caratteri attualmente definita su un dispositivo di output. |
| Exttextout | `512` | Disegna il testo utilizzando il font, il colore di sfondo e il colore del testo attualmente selezionati. |
| Getfacename | `513` | Ottiene il nome del carattere del carattere attualmente configurato su un dispositivo. |
| Downloadface | `514` | Imposta il nome del carattere del carattere su un dispositivo. |
| MetafileDriver | `2049` | Interroga un driver della stampante sul supporto per i metafile su un dispositivo di output . |
| Querydibsupport | `3073` | Interroga il driver della stampante sul supporto dei DIB su un dispositivo di output. |
| BeginPath | `4096` | Apre un percorso. |
| ClipToPath | `4097` | Definisce una regione di clip delimitata da un percorso. L'input DEVE essere una quantità di 16 bit che definisce l'azione da intraprendere. |
| EndPath | `4098` | Termina un percorso. |
| OpenChannel | `4110` | Lo stesso di STARTDOC specificato con un documento NULL e nome file di output , dati in modalità raw e un tipo di zero. |
| Downloadheader | `4111` | Indica al driver della stampante di scaricare set di procedure PostScript. |
| CloseChannel | `4112` | Lo stesso di ENDDOC. Vedi OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Invia dati arbitrari direttamente a un driver della stampante, che dovrebbe elaborare questi dati solo in modalità PostScript.PostscriptIdentify . |
| EncapsulatedPostscript | `4116` | Invia dati arbitrari direttamente al driver della stampante. |
| PostscriptIdentify | `4117` | Imposta il driver della stampante in modalità PostScript o GDI. |
| PostscriptInjection | `4118` | Inserisce un blocco di dati grezzi in un flusso PostScript. L'input DEVE essere una quantità a 32 bit che specifica il numero di byte da iniettare, una quantità a 16 bit che specifica il punto di iniezione e una quantità a 16 bit che specifica il numero di pagina, seguita da i byte da iniettare. |
| Checkjpegformat | `4119` | Verifica se la stampante supporta un'immagine JPEG. |
| Checkpngformat | `4120` | Verifica se la stampante supporta un'immagine PNG. |
| GetPsFeaturesetting | `4121` | Ottiene informazioni su un'impostazione di funzione specifica per un driver di stampa PostScript . |
| MxdcEscape | `4122` | Consente alle applicazioni di scrivere documenti su un file o su una stampante in formato XML Paper Specification (XPS). |
| Spclpassthrough2 | `4568` | Consente alle applicazioni di includere procedure private e altri dati arbitrari nei documenti. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

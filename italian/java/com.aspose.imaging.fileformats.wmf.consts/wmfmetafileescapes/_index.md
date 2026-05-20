---
title: "WmfMetafileEscapes"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione MetafileEscapes specifica la funzionalità del driver della stampante che potrebbe non essere direttamente accessibile tramite i record WMF definiti nella sezione 2.1.1.1 dell'enumerazione RecordType."
type: docs
weight: 24
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

L'enumerazione MetafileEscapes specifica la funzionalità del driver della stampante che potrebbe non essere direttamente accessibile tramite i record WMF definiti nell'enumerazione RecordType (sezione 2.1.1.1).
## Campi

| Campo | Descrizione |
| --- | --- |
| [Newframe](#Newframe) | Notifica al driver della stampante che l'applicazione ha terminato la scrittura su una pagina. |
| [Abortdoc](#Abortdoc) | Interrompe l'elaborazione del documento corrente. |
| [Nextband](#Nextband) | Notifica al driver della stampante che l'applicazione ha terminato la scrittura su una banda. |
| [Setcolortable](#Setcolortable) | Imposta i valori della tavola dei colori. |
| [Getcolortable](#Getcolortable) | Ottiene i valori della tavola dei colori. |
| [Flushout](#Flushout) | Provoca lo svuotamento di tutti gli output in sospeso verso il dispositivo di output. |
| [Draftmode](#Draftmode) | Indica che il driver della stampante DOVREBBE stampare solo testo, senza grafica. |
| [Queryescsupport](#Queryescsupport) | Interroga un driver della stampante per determinare se una specifica funzione di escape è supportata sul dispositivo di output che controlla. |
| [Setabortproc](#Setabortproc) | Imposta la funzione definita dall'applicazione che consente di annullare un lavoro di stampa durante la stampa. |
| [Startdoc](#Startdoc) | Notifica al driver della stampante che sta iniziando un nuovo lavoro di stampa. |
| [Enddoc](#Enddoc) | Notifica al driver della stampante che il lavoro di stampa corrente sta terminando. |
| [Getphyspagesize](#Getphyspagesize) | Recupera le dimensioni fisiche della pagina attualmente selezionate su un dispositivo di output. |
| [Getprintingoffset](#Getprintingoffset) | Recupera lo scostamento dall'angolo superiore sinistro della pagina fisica dove inizia la stampa o il disegno effettivo. |
| [Getscalingfactor](#Getscalingfactor) | Recupera i fattori di scala per l'asse x e l'asse y di una stampante. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Utilizzato per incorporare un metafile in formato Enhanced Metafile (EMF) all'interno di un metafile WMF. |
| [Setpenwidth](#Setpenwidth) | Imposta la larghezza di una penna in pixel. |
| [Setcopycount](#Setcopycount) | Imposta il numero di copie. |
| [Setpapersource](#Setpapersource) | Imposta la sorgente, ad esempio un vassoio di carta o un contenitore specifico su una stampante, per i moduli di output. |
| [Passthrough](#Passthrough) | Questo record trasmette dati arbitrari. |
| [Gettechnology](#Gettechnology) | Ottiene informazioni sulla tecnologia grafica supportata su un dispositivo. |
| [Setlinecap](#Setlinecap) | Specifica la modalità di disegno delle linee da utilizzare nell'output verso un dispositivo. |
| [Setlinejoin](#Setlinejoin) | Specifica la modalità di unione delle linee da utilizzare nell'output verso un dispositivo. |
| [Setmiterlimit](#Setmiterlimit) | Imposta il limite per la lunghezza delle giunzioni a spigolo da utilizzare nell'output verso un dispositivo. |
| [Bandinfo](#Bandinfo) | Recupera o specifica le impostazioni relative alla bande su un dispositivo, come il numero di bande. |
| [Drawpatternrect](#Drawpatternrect) | Disegna un rettangolo con un modello definito. |
| [Getvectorpensize](#Getvectorpensize) | Recupera la dimensione fisica della penna attualmente definita su un dispositivo. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Recupera la dimensione fisica del pennello attualmente definita su un dispositivo. |
| [Enableduplex](#Enableduplex) | Abilita o disabilita la stampa fronte/retro (duplex) su un dispositivo. |
| [Getsetpaperbins](#Getsetpaperbins) | Recupera o specifica la sorgente dei moduli di output su un dispositivo. |
| [Getsetprintorient](#Getsetprintorient) | Recupera o specifica l'orientamento della carta su un dispositivo. |
| [Enumpaperbins](#Enumpaperbins) | Recupera informazioni relative alle sorgenti di diversi moduli su un dispositivo di output. |
| [Setdibscaling](#Setdibscaling) | Specifica la scala dei bitmap indipendenti dal dispositivo (DIB). |
| [Epsprinting](#Epsprinting) | Indica l'inizio e la fine di una sezione PostScript incapsulato (EPS). |
| [Enumpapermetrics](#Enumpapermetrics) | Interroga un driver di stampa per le dimensioni della carta e altri dati dei moduli. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Recupera o specifica le dimensioni della carta e altri dati dei moduli su un dispositivo di output. |
| [PostscriptData](#PostscriptData) | Invia dati PostScript arbitrari a un dispositivo di output. |
| [PostscriptIgnore](#PostscriptIgnore) | Notifica a un dispositivo di output di ignorare i dati PostScript. |
| [Getdeviceunits](#Getdeviceunits) | Ottiene le unità del dispositivo attualmente configurate su un dispositivo di output. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Ottiene le metriche di testo estese attualmente configurate su un dispositivo di output. |
| [Getpairkerntable](#Getpairkerntable) | Ottiene la tabella di kerning del carattere attualmente definita su un dispositivo di output. |
| [Exttextout](#Exttextout) | Disegna il testo usando il carattere selezionato, il colore di sfondo e il colore del testo. |
| [Getfacename](#Getfacename) | Ottiene il nome del tipo di carattere attualmente configurato su un dispositivo. |
| [Downloadface](#Downloadface) | Imposta il nome del tipo di carattere su un dispositivo. |
| [MetafileDriver](#MetafileDriver) | Interroga un driver di stampa sul supporto dei metafili su un dispositivo di output. |
| [Querydibsupport](#Querydibsupport) | Interroga il driver di stampa sul suo supporto per i DIB su un dispositivo di output. |
| [BeginPath](#BeginPath) | Apre un percorso. |
| [ClipToPath](#ClipToPath) | Definisce una regione di ritaglio delimitata da un percorso. |
| [EndPath](#EndPath) | Termina un percorso. |
| [OpenChannel](#OpenChannel) | Lo stesso di STARTDOC specificato con un documento NULL e nome file di output, dati in modalità raw e tipo zero. |
| [Downloadheader](#Downloadheader) | Istruisce il driver della stampante a scaricare insiemi di procedure PostScript. |
| [CloseChannel](#CloseChannel) | Lo stesso di ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Invia dati arbitrari direttamente al driver della stampante, che dovrebbe elaborare questi dati solo quando è in modalità PostScript. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Invia dati arbitrari direttamente al driver della stampante. |
| [PostscriptIdentify](#PostscriptIdentify) | Imposta il driver della stampante in modalità PostScript o GDI. |
| [PostscriptInjection](#PostscriptInjection) | Inserisce un blocco di dati raw in un flusso PostScript. |
| [Checkjpegformat](#Checkjpegformat) | Verifica se la stampante supporta un'immagine JPEG. |
| [Checkpngformat](#Checkpngformat) | Verifica se la stampante supporta un'immagine PNG. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Ottiene informazioni su un'impostazione di funzionalità specificata per un driver di stampante PostScript. |
| [MxdcEscape](#MxdcEscape) | Consente alle applicazioni di scrivere documenti su un file o su una stampante in formato XML Paper Specification (XPS). |
| [Spclpassthrough2](#Spclpassthrough2) | Consente alle applicazioni di includere procedure private e altri dati arbitrari nei documenti. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Notifica al driver della stampante che l'applicazione ha terminato la scrittura su una pagina.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Interrompe l'elaborazione del documento corrente.

### Nextband {#Nextband}
```
public static final int Nextband
```


Notifica al driver della stampante che l'applicazione ha terminato la scrittura su una banda.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Imposta i valori della tavola dei colori.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Ottiene i valori della tavola dei colori.

### Flushout {#Flushout}
```
public static final int Flushout
```


Provoca lo svuotamento di tutti gli output in sospeso verso il dispositivo di output.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Indica che il driver della stampante DOVREBBE stampare solo testo, senza grafica.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Interroga un driver della stampante per determinare se una specifica funzione di escape è supportata sul dispositivo di output che controlla.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Imposta la funzione definita dall'applicazione che consente di annullare un lavoro di stampa durante la stampa.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Notifica al driver della stampante che sta iniziando un nuovo lavoro di stampa.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Notifica al driver della stampante che il lavoro di stampa corrente sta terminando.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Recupera le dimensioni fisiche della pagina attualmente selezionate su un dispositivo di output.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Recupera lo scostamento dall'angolo superiore sinistro della pagina fisica dove inizia la stampa o il disegno effettivo.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Recupera i fattori di scala per l'asse x e l'asse y di una stampante.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Utilizzato per incorporare un metafile in formato Enhanced Metafile (EMF) all'interno di un metafile WMF.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Imposta la larghezza di una penna in pixel.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Imposta il numero di copie.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Imposta la sorgente, ad esempio un vassoio di carta o un contenitore specifico su una stampante, per i moduli di output.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Questo record trasmette dati arbitrari.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Ottiene informazioni sulla tecnologia grafica supportata su un dispositivo.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Specifica la modalità di disegno delle linee da utilizzare nell'output verso un dispositivo.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Specifica la modalità di unione delle linee da utilizzare nell'output verso un dispositivo.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Imposta il limite per la lunghezza delle giunzioni a spigolo da utilizzare nell'output verso un dispositivo.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Recupera o specifica le impostazioni relative alla bande su un dispositivo, come il numero di bande.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Disegna un rettangolo con un modello definito.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Recupera la dimensione fisica della penna attualmente definita su un dispositivo.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Recupera la dimensione fisica del pennello attualmente definita su un dispositivo.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Abilita o disabilita la stampa fronte/retro (duplex) su un dispositivo.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Recupera o specifica la sorgente dei moduli di output su un dispositivo.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Recupera o specifica l'orientamento della carta su un dispositivo.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Recupera informazioni relative alle sorgenti di diversi moduli su un dispositivo di output.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Specifica la scala dei bitmap indipendenti dal dispositivo (DIB).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Indica l'inizio e la fine di una sezione PostScript incapsulato (EPS).

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Interroga un driver di stampa per le dimensioni della carta e altri dati dei moduli.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Recupera o specifica le dimensioni della carta e altri dati dei moduli su un dispositivo di output.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Invia dati PostScript arbitrari a un dispositivo di output.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Notifica a un dispositivo di output di ignorare i dati PostScript.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Ottiene le unità del dispositivo attualmente configurate su un dispositivo di output.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Ottiene le metriche di testo estese attualmente configurate su un dispositivo di output.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Ottiene la tabella di kerning del carattere attualmente definita su un dispositivo di output.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Disegna il testo usando il carattere selezionato, il colore di sfondo e il colore del testo.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Ottiene il nome del tipo di carattere attualmente configurato su un dispositivo.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Imposta il nome del tipo di carattere su un dispositivo.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Interroga un driver di stampa sul supporto dei metafili su un dispositivo di output.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Interroga il driver di stampa sul suo supporto per i DIB su un dispositivo di output.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Apre un percorso.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Definisce una regione di ritaglio delimitata da un percorso. L'input DEVE essere una quantità a 16 bit che definisce l'azione da eseguire.

### EndPath {#EndPath}
```
public static final int EndPath
```


Termina un percorso.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


Lo stesso di STARTDOC specificato con un documento NULL e nome file di output, dati in modalità raw e tipo zero.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Istruisce il driver della stampante a scaricare insiemi di procedure PostScript.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


Lo stesso di ENDDOC. Vedi OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Invia dati arbitrari direttamente al driver della stampante, che dovrebbe elaborare questi dati solo quando è in modalità PostScript. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Invia dati arbitrari direttamente al driver della stampante.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Imposta il driver della stampante in modalità PostScript o GDI.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Inserisce un blocco di dati raw in un flusso PostScript. L'input DEVE essere una quantità a 32 bit che specifica il numero di byte da iniettare, una quantità a 16 bit che specifica il punto di iniezione e una quantità a 16 bit che specifica il numero di pagina, seguita dai byte da iniettare.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Verifica se la stampante supporta un'immagine JPEG.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Verifica se la stampante supporta un'immagine PNG.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Ottiene informazioni su un'impostazione di funzionalità specificata per un driver di stampante PostScript.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Consente alle applicazioni di scrivere documenti su un file o su una stampante in formato XML Paper Specification (XPS).

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Consente alle applicazioni di includere procedure private e altri dati arbitrari nei documenti.


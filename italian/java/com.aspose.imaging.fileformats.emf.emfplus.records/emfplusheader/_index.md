---
title: "EmfPlusHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusHeader specifica l'inizio dei dati EMF nel metafile."
type: docs
weight: 40
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

Il record EmfPlusHeader specifica l'inizio dei dati EMF+ nel metafile. Il record EmfPlusHeader DEVE essere incorporato in un record EMF EMR\\_COMMENT\\_EMFPLUS, che DEVE essere il record immediatamente successivo all'intestazione EMF nel metafile. Il record EMR\\_COMMENT\\_EMFPLUS è specificato in [MS-EMF] sezione 2.3.3.2.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusHeader`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDualMode()](#getDualMode--) | Ottiene o imposta un valore che indica se [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Ottiene o imposta un valore che indica se [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | Ottiene o imposta un valore che indica se la visualizzazione video. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Ottiene o imposta un valore che indica se la visualizzazione video. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Ottiene o imposta i flag EMF plus. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Ottiene o imposta i flag EMF plus. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Ottiene o imposta il dpi logico x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Ottiene o imposta il dpi logico x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Ottiene o imposta il dpi logico y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Ottiene o imposta il dpi logico y. |
| [getVersion()](#getVersion--) | Ottiene o imposta la versione. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Ottiene o imposta la versione. |
| [isValid()](#isValid--) | Ottiene un valore che indica se questa istanza è valida. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusHeader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Ottiene o imposta un valore che indica se [dual mode]. Se impostato, questo flag indica che questo metafile è \"dual-mode\", il che significa che contiene due insiemi di record, ciascuno dei quali specifica completamente il contenuto grafico. Se non impostato, il contenuto grafico è specificato dai record EMF+, e possibilmente dai record EMF preceduti da un record EmfPlusGetDC. Se questo flag è impostato, i record EMF da soli DEVONO essere sufficienti per definire il contenuto grafico. Nota che, indipendentemente dal fatto che il flag \"dual-mode\" sia impostato o meno, alcuni record EMF sono sempre presenti, ovvero i record di controllo EMF e i record EMF che contengono record EMF+. I record di controllo EMF sono specificati in [MS-EMF] sezione 2.3.4.

Valore: `true` se [dual mode]; altrimenti, `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Ottiene o imposta un valore che indica se [dual mode]. Se impostato, questo flag indica che questo metafile è \"dual-mode\", il che significa che contiene due insiemi di record, ciascuno dei quali specifica completamente il contenuto grafico. Se non impostato, il contenuto grafico è specificato dai record EMF+, e possibilmente dai record EMF preceduti da un record EmfPlusGetDC. Se questo flag è impostato, i record EMF da soli DEVONO essere sufficienti per definire il contenuto grafico. Nota che, indipendentemente dal fatto che il flag \"dual-mode\" sia impostato o meno, alcuni record EMF sono sempre presenti, ovvero i record di controllo EMF e i record EMF che contengono record EMF+. I record di controllo EMF sono specificati in [MS-EMF] sezione 2.3.4.

Valore: `true` se [dual mode]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Ottiene o imposta un valore che indica se la visualizzazione video. se impostato, questo flag indica che il metafile è stato registrato con un contesto dispositivo di riferimento per una visualizzazione video. Se non impostato, il metafile è stato registrato con un contesto dispositivo di riferimento per una stampante.

Valore: `true` se [video display]; altrimenti, `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Ottiene o imposta un valore che indica se la visualizzazione video. se impostato, questo flag indica che il metafile è stato registrato con un contesto dispositivo di riferimento per una visualizzazione video. Se non impostato, il metafile è stato registrato con un contesto dispositivo di riferimento per una stampante.

Valore: `true` se [video display]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Ottiene o imposta i flag EMF plus. Un intero senza segno a 32 bit che contiene informazioni su come questo metafile è stato registrato. se il 31° bit del campo è impostato, questo flag indica che il metafile è stato registrato con un contesto dispositivo di riferimento per una visualizzazione video. Se non impostato, il metafile è stato registrato con un contesto dispositivo di riferimento per una stampante.

Valore: I flag EMF plus.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Ottiene o imposta i flag EMF plus. Un intero senza segno a 32 bit che contiene informazioni su come questo metafile è stato registrato. se il 31° bit del campo è impostato, questo flag indica che il metafile è stato registrato con un contesto dispositivo di riferimento per una visualizzazione video. Se non impostato, il metafile è stato registrato con un contesto dispositivo di riferimento per una stampante.

Valore: I flag EMF plus.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Ottiene o imposta il dpi logico x. Un intero senza segno a 32 bit che specifica la risoluzione orizzontale per la quale il metafile è stato registrato, in unità di pixel per pollice.

Valore: Il dpi logico x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Ottiene o imposta il dpi logico x. Un intero senza segno a 32 bit che specifica la risoluzione orizzontale per la quale il metafile è stato registrato, in unità di pixel per pollice.

Valore: Il dpi logico x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Ottiene o imposta il dpi logico y. Un intero senza segno a 32 bit che specifica la risoluzione verticale per la quale il metafile è stato registrato, in unità di linee per pollice

Valore: Il dpi logico y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Ottiene o imposta il dpi logico y. Un intero senza segno a 32 bit che specifica la risoluzione verticale per la quale il metafile è stato registrato, in unità di linee per pollice

Valore: Il dpi logico y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Ottiene o imposta la versione. Un oggetto EmfPlusGraphicsVersion (sezione 2.2.2.19) che specifica la versione della grafica del sistema operativo utilizzata per creare questo metafile.

Valore: La versione.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Ottiene o imposta la versione. Un oggetto EmfPlusGraphicsVersion (sezione 2.2.2.19) che specifica la versione della grafica del sistema operativo utilizzata per creare questo metafile.

Valore: La versione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Ottiene un valore che indica se questa istanza è valida.

Valore: `true` se questa istanza è valida; altrimenti, `false`.

**Returns:**
boolean

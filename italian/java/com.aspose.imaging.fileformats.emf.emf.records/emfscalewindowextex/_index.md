---
title: "EmfScaleWindowExtex"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SCALEWINDOWEXTEX ridefinisce la finestra per un contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicatori e divisori specificati."
type: docs
weight: 114
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

Il record EMR\_SCALEWINDOWEXTEX ridefinisce la finestra per un contesto di dispositivo di riproduzione usando i rapporti formati dai moltiplicatori e divisori specificati.

L'estensione non può essere modificata se il contesto del dispositivo utilizza una modalità di mappatura a scala fissa. Solo MM\_ISOTROPIC e MM\_ANISOTROPIC non sono a scala fissa. Le estensioni della finestra vengono modificate come segue. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfScaleWindowExtex`. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Inizializza una nuova istanza della classe [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXNum()](#getXNum--) | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicando orizzontale. |
| [setXNum(int value)](#setXNum-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicando orizzontale. |
| [getXDenom()](#getXDenom--) | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore orizzontale. |
| [setXDenom(int value)](#setXDenom-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore orizzontale. |
| [getYNum()](#getYNum--) | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicando verticale. |
| [setYNum(int value)](#setYNum-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicando verticale. |
| [getYDenom()](#getYDenom--) | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore verticale. |
| [setYDenom(int value)](#setYDenom-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il divisore verticale. |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfScaleWindowExtex`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Inizializza una nuova istanza della classe [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore orizzontale. NON DEVE essere zero.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore orizzontale. NON DEVE essere zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il divisore orizzontale. NON DEVE essere zero.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il divisore orizzontale. NON DEVE essere zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore verticale. NON DEVE essere zero.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il moltiplicatore verticale. NON DEVE essere zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il divisore verticale. NON DEVE essere zero.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il divisore verticale. NON DEVE essere zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


---
title: "EmfPlusSetTsClip"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetTSClip specifica le aree di ritaglio nel contesto del dispositivo grafico per un server terminale."
type: docs
weight: 66
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusSetTSClip specifica le aree di ritaglio nel contesto del dispositivo grafico per un server terminale.

Lo schema di compressione per i dati in questo record utilizza il seguente algoritmo. Ogni punto di ciascun rettangolo è codificato in un byte singolo o in 2 byte. Se il punto è codificato in un byte singolo, il bit più significativo (0x80) del byte DEVE essere impostato, e il valore è un numero con segno rappresentato dai 7 bit inferiori. Se il bit più significativo non è impostato, il valore è codificato in 2 byte, con il byte di ordine più alto codificato nei 7 bit inferiori del primo byte, e il valore del byte di ordine più basso codificato nel secondo byte. Ogni punto è codificato come la differenza tra il punto nel rettangolo corrente e il punto nel rettangolo precedente. Il punto inferiore del rettangolo è codificato come la differenza tra la coordinata inferiore e la coordinata superiore nel rettangolo corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetTsClip`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene un valore che indica se questo `EmfPlusSetTsClip` è compresso. |
| [getNumRects()](#getNumRects--) | Restituisce il numero di rettangoli. |
| [getRects()](#getRects--) | Ottiene o imposta un array di rettangoli NumRects che definiscono le aree di ritaglio. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Ottiene o imposta un array di rettangoli NumRects che definiscono le aree di ritaglio. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetTsClip`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene un valore che indica se questo `EmfPlusSetTsClip` è compresso. Questo bit specifica il formato dei dati dei rettangoli nel campo rects. Se impostato, ogni rettangolo è definito in 4 byte. Se non impostato, ogni rettangolo è definito in 8 byte.

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Restituisce il numero di rettangoli. Questo campo specifica il numero di rettangoli definiti nel campo rect.

Valore: Il numero di rettangoli.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Ottiene o imposta un array di rettangoli NumRects che definiscono le aree di ritaglio. Il formato di questi dati è determinato dal bit C nel campo Flags.

Valore: I rettangoli.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Ottiene o imposta un array di rettangoli NumRects che definiscono le aree di ritaglio. Il formato di questi dati è determinato dal bit C nel campo Flags.

Valore: I rettangoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |


---
title: "EmfRegionDataHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto RegionDataHeader descrive le proprietà di un oggetto RegionData."
type: docs
weight: 34
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

L'oggetto RegionDataHeader descrive le proprietà di un oggetto RegionData.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene un intero senza segno a 32 bit che specifica la dimensione di questo oggetto in byte. |
| [setSize(int value)](#setSize-int-) | Imposta un intero senza segno a 32 bit che specifica la dimensione di questo oggetto in byte. |
| [getType()](#getType--) | Ottiene un intero senza segno a 32 bit che specifica il tipo di regione. |
| [setType(int value)](#setType-int-) | Imposta un intero senza segno a 32 bit che specifica il tipo di regione. |
| [getCountRects()](#getCountRects--) | Ottiene un intero senza segno a 32 bit che specifica il numero di rettangoli in questa regione. |
| [setCountRects(int value)](#setCountRects-int-) | Imposta un intero senza segno a 32 bit che specifica il numero di rettangoli in questa regione. |
| [getRgnSize()](#getRgnSize--) | Ottiene un intero senza segno a 32 bit che specifica la dimensione del buffer di rettangoli in byte. |
| [setRgnSize(int value)](#setRgnSize-int-) | Imposta un intero senza segno a 32 bit che specifica la dimensione del buffer di rettangoli in byte. |
| [getBounds()](#getBounds--) | Ottiene un oggetto WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19), che specifica i limiti della regione. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Imposta un oggetto WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19), che specifica i limiti della regione. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Ottiene un intero senza segno a 32 bit che specifica la dimensione di questo oggetto in byte. Questo DEVE essere 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Imposta un intero senza segno a 32 bit che specifica la dimensione di questo oggetto in byte. Questo DEVE essere 0x00000020.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getType() {#getType--}
```
public int getType()
```


Ottiene un intero senza segno a 32 bit che specifica il tipo di regione. Questo DOVREBBE essere RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Imposta un intero senza segno a 32 bit che specifica il tipo di regione. Questo DOVREBBE essere RDH\_RECTANGLES (0x00000001).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Ottiene un intero senza segno a 32 bit che specifica il numero di rettangoli in questa regione.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Imposta un intero senza segno a 32 bit che specifica il numero di rettangoli in questa regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Ottiene un intero senza segno a 32 bit che specifica la dimensione del buffer di rettangoli in byte.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Imposta un intero senza segno a 32 bit che specifica la dimensione del buffer di rettangoli in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene un oggetto WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19), che specifica i limiti della regione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Imposta un oggetto WMF RectL a 128 bit ([MS-WMF] sezione 2.2.2.19), che specifica i limiti della regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |


---
title: "EmfExtFloodFill"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_EXTFLOODFILL riempie un'area della superficie di visualizzazione con il pennello corrente."
type: docs
weight: 54
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

Il record EMR\_EXTFLOODFILL riempie un'area della superficie di visualizzazione con il pennello corrente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfExtFloodFill`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStart()](#getStart--) | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15), che specifica le coordinate, in unità logiche, dove inizia il riempimento. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15), che specifica le coordinate, in unità logiche, dove inizia il riempimento. |
| [getArgb32Color()](#getArgb32Color--) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8), che viene usato con FloodFillMode per determinare l'area da riempire. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8), che viene usato con FloodFillMode per determinare l'area da riempire. |
| [getFloodFillMode()](#getFloodFillMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il valore Color per determinare l'area dell'operazione di riempimento. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il valore Color per determinare l'area dell'operazione di riempimento. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfExtFloodFill`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getStart() {#getStart--}
```
public Point getStart()
```


Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15), che specifica le coordinate, in unità logiche, dove inizia il riempimento.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15), che specifica le coordinate, in unità logiche, dove inizia il riempimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8), che viene usato con FloodFillMode per determinare l'area da riempire.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8), che viene usato con FloodFillMode per determinare l'area da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il valore Color per determinare l'area dell'operazione di riempimento. Il valore DEVE essere nell'enumerazione FloodFill (sezione 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il valore Color per determinare l'area dell'operazione di riempimento. Il valore DEVE essere nell'enumerazione FloodFill (sezione 2.1.13).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


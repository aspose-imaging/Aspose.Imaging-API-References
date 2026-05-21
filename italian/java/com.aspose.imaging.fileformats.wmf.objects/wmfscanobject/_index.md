---
title: "WmfScanObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto Scan specifica una collezione di linee di scansione."
type: docs
weight: 69
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

L'oggetto Scan specifica una collezione di linee di scansione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Ottiene o imposta il conteggio. |
| [setCount(int value)](#setCount-int-) | Ottiene o imposta il conteggio. |
| [getTop()](#getTop--) | Ottiene o imposta la parte superiore. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta la parte superiore. |
| [getBottom()](#getBottom--) | Ottiene o imposta la parte inferiore. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta la parte inferiore. |
| [getScanLines()](#getScanLines--) | Ottiene o imposta le linee di scansione. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Ottiene o imposta le linee di scansione. |
| [getCount2()](#getCount2--) | Ottiene o imposta count2. |
| [setCount2(int value)](#setCount2-int-) | Ottiene o imposta count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Ottiene o imposta il conteggio.

Valore: Il numero di coordinate orizzontali (asse x) nell'array `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Questo valore DEVE essere un multiplo di 2, poiché sono richiesti gli estremi sinistro e destro per specificare ogni scanline.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Ottiene o imposta il conteggio.

Valore: Il numero di coordinate orizzontali (asse x) nell'array `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. Questo valore DEVE essere un multiplo di 2, poiché sono richiesti gli estremi sinistro e destro per specificare ogni scanline.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Ottiene o imposta la parte superiore.

Valore: La coordinata verticale (asse y), in unità logiche, della scanline superiore.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Ottiene o imposta la parte superiore.

Valore: La coordinata verticale (asse y), in unità logiche, della scanline superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Ottiene o imposta la parte inferiore.

Valore: La coordinata verticale (asse y), in unità logiche, della scanline inferiore.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Ottiene o imposta la parte inferiore.

Valore: La coordinata verticale (asse y), in unità logiche, della scanline inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Ottiene o imposta le linee di scansione.

Valore: Un array di scanline, ciascuna specificata dalle coordinate orizzontali (asse x) sinistra e destra dei suoi estremi.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Ottiene o imposta le linee di scansione.

Valore: Un array di scanline, ciascuna specificata dalle coordinate orizzontali (asse x) sinistra e destra dei suoi estremi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Ottiene o imposta count2.

Valore: Lo stesso del valore del campo `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; è presente per consentire la navigazione verso l'alto nella struttura.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Ottiene o imposta count2.

Valore: Lo stesso del valore del campo `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; è presente per consentire la navigazione verso l'alto nella struttura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


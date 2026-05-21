---
title: "EmfSetPixelV"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETPIXELV definisce il colore del pixel alle coordinate logiche specificate."
type: docs
weight: 135
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

Il record EMR\_SETPIXELV definisce il colore del pixel alle coordinate logiche specificate.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetPixelV`. |
| [EmfSetPixelV()](#EmfSetPixelV--) | Inizializza una nuova istanza della classe [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPixel()](#getPixel--) | Ottiene o imposta un oggetto WMF PointL a 64 bit ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate logiche del pixel. |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate logiche del pixel. |
| [getArgb32Color()](#getArgb32Color--) | Ottiene o imposta un oggetto WMF ColorRef a 32 bit ([MS-WMF] sezione 2.2.2.8) che specifica il colore del pixel. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Ottiene o imposta un oggetto WMF ColorRef a 32 bit ([MS-WMF] sezione 2.2.2.8) che specifica il colore del pixel. |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetPixelV`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


Inizializza una nuova istanza della classe [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv).

### getPixel() {#getPixel--}
```
public Point getPixel()
```


Ottiene o imposta un oggetto WMF PointL a 64 bit ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate logiche del pixel.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate logiche del pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Ottiene o imposta un oggetto WMF ColorRef a 32 bit ([MS-WMF] sezione 2.2.2.8) che specifica il colore del pixel.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Ottiene o imposta un oggetto WMF ColorRef a 32 bit ([MS-WMF] sezione 2.2.2.8) che specifica il colore del pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


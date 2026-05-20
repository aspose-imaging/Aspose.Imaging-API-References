---
title: "WmfDeviceIndependentBitmap"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto DeviceIndependentBitmap definisce un'immagine nel formato bitmap indipendente dal dispositivo DIB"
type: docs
weight: 27
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

L'oggetto DeviceIndependentBitmap definisce un'immagine in formato bitmap indipendente dal dispositivo (DIB).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeader()](#getHeader--) | Ottiene o imposta un oggetto BitmapCoreHeader (sezione 2.2.2.2) oppure un oggetto BitmapInfoHeader (sezione 2.2.2.3) che specifica le informazioni sull'immagine |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Ottiene o imposta un oggetto BitmapCoreHeader (sezione 2.2.2.2) oppure un oggetto BitmapInfoHeader (sezione 2.2.2.3) che specifica le informazioni sull'immagine |
| [getColorsData()](#getColorsData--) | Ottiene o imposta un array opzionale di oggetti RGBQuad (sezione 2.2.2.20) oppure di interi senza segno a 16 bit che definiscono una tavola dei colori. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Ottiene o imposta un array opzionale di oggetti RGBQuad (sezione 2.2.2.20) oppure di interi senza segno a 16 bit che definiscono una tavola dei colori. |
| [getAData()](#getAData--) | Ottiene o imposta un array di byte che definisce l'immagine. |
| [setAData(byte[] value)](#setAData-byte---) | Ottiene o imposta un array di byte che definisce l'immagine. |
| [getCachedImage()](#getCachedImage--) | Ottiene l'immagine raster memorizzata nella cache. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Imposta l'immagine raster memorizzata nella cache. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Ottiene o imposta un oggetto BitmapCoreHeader (sezione 2.2.2.2) oppure un oggetto BitmapInfoHeader (sezione 2.2.2.3) che specifica le informazioni sull'immagine

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Ottiene o imposta un oggetto BitmapCoreHeader (sezione 2.2.2.2) oppure un oggetto BitmapInfoHeader (sezione 2.2.2.3) che specifica le informazioni sull'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Ottiene o imposta un array opzionale di oggetti RGBQuad (sezione 2.2.2.20) oppure di interi senza segno a 16 bit che definiscono una tavola dei colori. La dimensione e il contenuto di questo campo DEVONO essere determinati dal record metafile o dall'oggetto che contiene questo DeviceIndependentBitmap e dalle informazioni nel campo DIBHeaderInfo. Vedere l'enumerazione ColorUsage (sezione 2.1.1.6) e l'enumerazione BitCount (sezione 2.1.1.3) per ulteriori dettagli.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Ottiene o imposta un array opzionale di oggetti RGBQuad (sezione 2.2.2.20) oppure di interi senza segno a 16 bit che definiscono una tavola dei colori. La dimensione e il contenuto di questo campo DEVONO essere determinati dal record metafile o dall'oggetto che contiene questo DeviceIndependentBitmap e dalle informazioni nel campo DIBHeaderInfo. Vedere l'enumerazione ColorUsage (sezione 2.1.1.6) e l'enumerazione BitCount (sezione 2.1.1.3) per ulteriori dettagli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Ottiene o imposta un array di byte che definisce l'immagine. La dimensione e il formato di questi dati sono determinati dalle informazioni nel campo DIBHeaderInfo.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Ottiene o imposta un array di byte che definisce l'immagine. La dimensione e il formato di questi dati sono determinati dalle informazioni nel campo DIBHeaderInfo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Ottiene l'immagine raster memorizzata nella cache.

Valore: L'immagine memorizzata nella cache.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Imposta l'immagine raster memorizzata nella cache.

Valore: L'immagine memorizzata nella cache.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |


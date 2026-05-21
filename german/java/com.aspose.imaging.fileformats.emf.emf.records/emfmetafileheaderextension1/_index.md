---
title: "EmfMetafileHeaderExtension1"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfMetafileHeaderExtension1-Datensatz ist der Kopfdatensatz, der in der ersten Erweiterung von EMF-Metadateien verwendet wird."
type: docs
weight: 71
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

Der EmfMetafileHeaderExtension1-Datensatz ist der Header-Datensatz, der in der ersten Erweiterung von EMF-Metadateien verwendet wird. Nach dem EmfHeaderExtension1‑Feld sind die übrigen Felder optional und können in beliebiger Reihenfolge auftreten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initialisiert eine neue Instanz der Klasse `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Initialisiert eine neue Instanz der Klasse `EmfMetafileHeaderExtension1`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Liest oder setzt ein HeaderExtension1‑Objekt, das zusätzliche Informationen über das Bild in der Metadatei angibt. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Liest oder setzt ein HeaderExtension1‑Objekt, das zusätzliche Informationen über das Bild in der Metadatei angibt. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Liest oder setzt ein optionales Byte‑Array, das den EMF‑Pixel‑Format‑Deskriptor enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeaderExtension1‑Datensatzes oder mit der EMF‑Beschreibungszeichenkette sein muss. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Liest oder setzt ein optionales Byte‑Array, das den EMF‑Pixel‑Format‑Deskriptor enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeaderExtension1‑Datensatzes oder mit der EMF‑Beschreibungszeichenkette sein muss. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Initialisiert eine neue Instanz der Klasse `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Der Header. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Initialisiert eine neue Instanz der Klasse `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | Der Header. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Liest oder setzt ein HeaderExtension1‑Objekt, das zusätzliche Informationen über das Bild in der Metadatei angibt.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Liest oder setzt ein HeaderExtension1‑Objekt, das zusätzliche Informationen über das Bild in der Metadatei angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Liest oder setzt ein optionales Byte‑Array, das den EMF‑Pixel‑Format‑Deskriptor enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeaderExtension1‑Datensatzes oder mit der EMF‑Beschreibungszeichenkette sein muss. Dementsprechend ist das Feld in diesem Puffer, das mit \"UndefinedSpace\" gekennzeichnet ist, optional und MUSS ignoriert werden.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Liest oder setzt ein optionales Byte‑Array, das den EMF‑Pixel‑Format‑Deskriptor enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeaderExtension1‑Datensatzes oder mit der EMF‑Beschreibungszeichenkette sein muss. Dementsprechend ist das Feld in diesem Puffer, das mit \"UndefinedSpace\" gekennzeichnet ist, optional und MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |


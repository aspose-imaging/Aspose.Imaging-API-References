---
title: "EmfHeaderObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Header‑Objekt definiert den EMF‑Metadatei‑Header."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

Das Header-Objekt definiert den EMF-Metadatei-Header. Es gibt Eigenschaften des Geräts an, auf dem das Bild in der Metadatei erstellt wurde.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Initialisiert eine neue Instanz der Klasse `EmfHeaderObject`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das die rechteckigen inklusiv-inklusiven Grenzen in Geräteeinheiten des kleinsten Rechtecks angibt, das um das im Metafile gespeicherte Bild gezeichnet werden kann. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das die rechteckigen inklusiv-inklusiven Grenzen in Geräteeinheiten des kleinsten Rechtecks angibt, das um das im Metafile gespeicherte Bild gezeichnet werden kann. |
| [getFrame()](#getFrame--) | Liest oder setzt ein WMF RectL-Objekt, das die rechteckigen inklusiv-inklusiven Abmessungen in .01‑Millimeter‑Einheiten eines Rechtecks angibt, das das im Metafile gespeicherte Bild umschließt. |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL-Objekt, das die rechteckigen inklusiv-inklusiven Abmessungen in .01‑Millimeter‑Einheiten eines Rechtecks angibt, das das im Metafile gespeicherte Bild umschließt. |
| [getRecordSignature()](#getRecordSignature--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Signatur des Datensatzes angibt. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Signatur des Datensatzes angibt. |
| [getVersion()](#getVersion--) | Liest oder setzt Version (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die Interoperabilität der EMF-Metadatei angibt. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt Version (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die Interoperabilität der EMF-Metadatei angibt. |
| [getBytes()](#getBytes--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Metadatei in Bytes angibt. |
| [setBytes(int value)](#setBytes-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Metadatei in Bytes angibt. |
| [getRecords()](#getRecords--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Datensätze in der Metadatei angibt. |
| [setRecords(int value)](#setRecords-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Datensätze in der Metadatei angibt. |
| [getHandles()](#getHandles--) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der die Anzahl der Grafikobjekte angibt, die während der Verarbeitung der Metadatei verwendet werden. |
| [setHandles(short value)](#setHandles-short-) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der die Anzahl der Grafikobjekte angibt, die während der Verarbeitung der Metadatei verwendet werden. |
| [getReserved()](#getReserved--) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der 0x0000 sein MUSS und ignoriert werden MUSS. |
| [setReserved(short value)](#setReserved-short-) | Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der 0x0000 sein MUSS und ignoriert werden MUSS. |
| [getNDesription()](#getNDesription--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Zeichen im Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. |
| [setNDesription(int value)](#setNDesription-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Zeichen im Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. |
| [getOffDescription()](#getOffDescription--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der den Offset vom Beginn dieses Datensatzes zum Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. |
| [setOffDescription(int value)](#setOffDescription-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der den Offset vom Beginn dieses Datensatzes zum Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. |
| [getNPalEntries()](#getNPalEntries--) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Einträge in der Metadatei-Palette angibt. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Einträge in der Metadatei-Palette angibt. |
| [getDevice()](#getDevice--) | Liest oder setzt ein WMF SizeL-Objekt ([MS-WMF] Abschnitt 2.2.2.22), das die Größe des Referenzgeräts in Pixeln angibt. |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Liest oder setzt ein WMF SizeL-Objekt ([MS-WMF] Abschnitt 2.2.2.22), das die Größe des Referenzgeräts in Pixeln angibt. |
| [getMillimeters()](#getMillimeters--) | Liest oder setzt ein WMF SizeL-Objekt, das die Größe des Referenzgeräts in Millimetern angibt. |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Liest oder setzt ein WMF SizeL-Objekt, das die Größe des Referenzgeräts in Millimetern angibt. |
| [getValid()](#getValid--) | Liest einen Wert, der angibt, ob dieses `EmfHeaderObject` gültig ist. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Initialisiert eine neue Instanz der Klasse `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das die rechteckigen inklusiv-inklusiven Grenzen in Geräteeinheiten des kleinsten Rechtecks angibt, das um das im Metafile gespeicherte Bild gezeichnet werden kann.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das die rechteckigen inklusiv-inklusiven Grenzen in Geräteeinheiten des kleinsten Rechtecks angibt, das um das im Metafile gespeicherte Bild gezeichnet werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Liest oder setzt ein WMF RectL-Objekt, das die rechteckigen inklusiv-inklusiven Abmessungen in .01‑Millimeter‑Einheiten eines Rechtecks angibt, das das im Metafile gespeicherte Bild umschließt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Liest oder setzt ein WMF RectL-Objekt, das die rechteckigen inklusiv-inklusiven Abmessungen in .01‑Millimeter‑Einheiten eines Rechtecks angibt, das das im Metafile gespeicherte Bild umschließt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Signatur des Datensatzes angibt. Dieser MUSS ENHMETA\_SIGNATURE sein, aus der Aufzählung FormatSignature (Abschnitt 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Signatur des Datensatzes angibt. Dieser MUSS ENHMETA\_SIGNATURE sein, aus der Aufzählung FormatSignature (Abschnitt 2.1.14).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder setzt Version (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die Interoperabilität der EMF-Metadatei angibt. Dieser SOLLTE 0x00010000 sein.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder setzt Version (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die Interoperabilität der EMF-Metadatei angibt. Dieser SOLLTE 0x00010000 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Metadatei in Bytes angibt.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Größe der Metadatei in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Datensätze in der Metadatei angibt.

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Datensätze in der Metadatei angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der die Anzahl der Grafikobjekte angibt, die während der Verarbeitung der Metadatei verwendet werden.

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der die Anzahl der Grafikobjekte angibt, die während der Verarbeitung der Metadatei verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der 0x0000 sein MUSS und ignoriert werden MUSS.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der 0x0000 sein MUSS und ignoriert werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Zeichen im Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. Dieser ist Null, wenn keine Beschreibungszeichenkette vorhanden ist.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Zeichen im Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. Dieser ist Null, wenn keine Beschreibungszeichenkette vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der den Offset vom Beginn dieses Datensatzes zum Array angibt, das die Beschreibung des Inhalts der Metadatei enthält.

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der den Offset vom Beginn dieses Datensatzes zum Array angibt, das die Beschreibung des Inhalts der Metadatei enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Einträge in der Metadatei-Palette angibt. Die Palette befindet sich im EMR\_EOF-Datensatz.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Anzahl der Einträge in der Metadatei-Palette angibt. Die Palette befindet sich im EMR\_EOF-Datensatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Liest oder setzt ein WMF SizeL-Objekt ([MS-WMF] Abschnitt 2.2.2.22), das die Größe des Referenzgeräts in Pixeln angibt.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Liest oder setzt ein WMF SizeL-Objekt ([MS-WMF] Abschnitt 2.2.2.22), das die Größe des Referenzgeräts in Pixeln angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Liest oder setzt ein WMF SizeL-Objekt, das die Größe des Referenzgeräts in Millimetern angibt.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Liest oder setzt ein WMF SizeL-Objekt, das die Größe des Referenzgeräts in Millimetern angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Liest einen Wert, der angibt, ob dieses `EmfHeaderObject` gültig ist.

Wert: `true`, wenn gültig; andernfalls `false`.

**Returns:**
boolean

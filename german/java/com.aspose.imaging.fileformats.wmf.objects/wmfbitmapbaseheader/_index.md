---
title: "WmfBitmapBaseHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Basisklassen‑Header‑Klasse für Bitmaps."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

Die Basisklassen‑Header‑Klasse für Bitmaps.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes definiert. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes definiert. |
| [getPlanes()](#getPlanes--) | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der `planes` für das Zielgerät definiert. |
| [setPlanes(short value)](#setPlanes-short-) | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der `planes` für das Zielgerät definiert. |
| [getBitCount()](#getBitCount--) | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die das Format jedes Pixels und die maximale Anzahl von Farben im DIB definiert. |
| [setBitCount(short value)](#setBitCount-short-) | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die das Format jedes Pixels und die maximale Anzahl von Farben im DIB definiert. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes definiert.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der `planes` für das Zielgerät definiert. Dieser Wert MUSS 0x0001 sein. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der die Anzahl der `planes` für das Zielgerät definiert. Dieser Wert MUSS 0x0001 sein.

**Returns:**
short – ein 16‑Bit‑vorzeichenloser Integer, der die Anzahl der `planes` für das Zielgerät definiert.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der die Anzahl der `planes` für das Zielgerät definiert. Dieser Wert MUSS 0x0001 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Ein 16‑Bit‑vorzeichenloser Integer, der die Anzahl der `planes` für das Zielgerät definiert. Dieser Wert MUSS \* 0x0001 sein. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der das Format jedes Pixels und die maximale Anzahl von Farben im DIB definiert. Dieser Wert MUSS in der `BitCount`‑Aufzählung (Abschnitt 2.1.1.3) sein.

**Returns:**
short – ein 16‑Bit‑vorzeichenloser Integer, der das Format jedes Pixels und die maximale Anzahl von Farben im DIB definiert.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der das Format jedes Pixels und die maximale Anzahl von Farben im DIB definiert. Dieser Wert MUSS in der `BitCount`‑Aufzählung (Abschnitt 2.1.1.3) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Ein 16‑Bit‑vorzeichenloser Integer, der das Format jedes Pixels und die maximale Anzahl von Farben im DIB definiert. |


---
title: "BitmapV5Header"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Struktur BitmapV5Header ist die Bitmap-Informations-Headerdatei."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

Die BitmapV5Header-Struktur ist die Bitmap-Informations-Headerdatei. Sie ist eine erweiterte Version der BITMAPINFOHEADER-Struktur.

Wenn bV5Height negativ ist, was auf ein Top‑Down‑DIB hinweist, muss bV5Compression entweder BI\_RGB oder BI\_BITFIELDS sein. Top‑Down‑DIBs können nicht komprimiert werden. Die Independent Color Management‑Schnittstelle (ICM) 2.0 ermöglicht es, International Color Consortium (ICC)-Farbprofile mit DIBs zu verknüpfen oder einzubetten (DIBs). Siehe Using Structures für weitere Informationen. Wenn ein DIB in den Speicher geladen wird, sollten die Profildaten (falls vorhanden) nach der Farbpalette folgen, und bV5ProfileData muss den Offset der Profildaten vom Beginn der BITMAPV5HEADER‑Struktur angeben. Der in bV5ProfileData gespeicherte Wert unterscheidet sich vom Wert, der vom sizeof‑Operator für das BITMAPV5HEADER‑Argument zurückgegeben wird, da bV5ProfileData der Offset in Bytes vom Beginn der BITMAPV5HEADER‑Struktur bis zum Beginn der Profildaten ist. (Bitmap‑Bits folgen nicht der Farbpalette im Speicher). Anwendungen sollten das bV5ProfileData‑Mitglied nach dem Laden des DIBs in den Speicher ändern. Für gepackte DIBs sollten die Profildaten den Bitmap‑Bits ähnlich dem Dateiformat folgen. Das bV5ProfileData‑Mitglied sollte weiterhin den Offset der Profildaten vom Beginn der BITMAPV5HEADER angeben. Anwendungen sollten nur dann auf die Profildaten zugreifen, wenn bV5Size der Größe des BITMAPV5HEADER entspricht und bV5CSType gleich PROFILE\_EMBEDDED oder PROFILE\_LINKED ist.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Initialisiert eine neue Instanz der `BitmapV5Header`-Klasse. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Initialisiert eine neue Instanz der `BitmapV5Header`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIntent()](#getIntent--) | Liest die Rendering‑Intention für das Bitmap. |
| [setIntent(long value)](#setIntent-long-) | Setzt die Rendering‑Intention für das Bitmap. |
| [getProfileData()](#getProfileData--) | Liest die Profildaten. |
| [setProfileData(long value)](#setProfileData-long-) | Setzt die Profildaten. |
| [getProfileSize()](#getProfileSize--) | Liest die Größe des Profils. |
| [setProfileSize(long value)](#setProfileSize-long-) | Setzt die Größe des Profils. |
| [getReserved()](#getReserved--) | Liest das reservierte Mitglied. |
| [setReserved(long value)](#setReserved-long-) | Setzt das reservierte Mitglied. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Initialisiert eine neue Instanz der `BitmapV5Header`-Klasse.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Initialisiert eine neue Instanz der `BitmapV5Header`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die Bytes. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Liest die Rendering‑Intention für das Bitmap.

**Returns:**
long - Die Intention.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Setzt die Rendering‑Intention für das Bitmap.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Intention. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Liest die Profildaten.

**Returns:**
long - Die Profildaten.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Setzt die Profildaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Profildaten. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Liest die Größe des Profils.

**Returns:**
long - Die Größe des Profils.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Setzt die Größe des Profils.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Die Größe des Profils. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Liest das reservierte Mitglied.

**Returns:**
long - Der reservierte Wert.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Setzt das reservierte Mitglied.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Der reservierte Wert. |


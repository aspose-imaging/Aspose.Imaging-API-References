---
title: "BitmapV5Header"
second_title: "Aspose.Imaging för Java API-referens"
description: "BitmapV5Header-strukturen är bitmap-informationens headerfil."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

BitmapV5Header‑strukturen är bitmap‑informationens headerfil. Den är en utökad version av BITMAPINFOHEADER‑strukturen.

Om bV5Height är negativt, vilket indikerar en top-down DIB, måste bV5Compression vara antingen BI\_RGB eller BI\_BITFIELDS. Top-down DIBs kan inte komprimeras. Independent Color Management‑gränssnittet (ICM) 2.0 tillåter International Color Consortium (ICC) färgprofiler att länkas eller bäddas in i DIBs (DIBs). Se Använda strukturer för mer information. När en DIB laddas in i minnet bör profildata (om den finns) följa färgtabellen, och bV5ProfileData ska ange offseten för profildata från början av BITMAPV5HEADER‑strukturen. Värdet som lagras i bV5ProfileData kommer att skilja sig från värdet som returneras av sizeof‑operatorn för BITMAPV5HEADER‑argumentet, eftersom bV5ProfileData är offseten i byte från början av BITMAPV5HEADER‑strukturen till början av profildata. (Bitmap‑bitar följer inte färgtabellen i minnet). Applikationer bör ändra bV5ProfileData‑medlemmen efter att DIB har laddats in i minnet. För packade DIBs bör profildata följa bitmap‑bitarna på samma sätt som filformatet. bV5ProfileData‑medlemmen ska fortfarande ge offseten för profildata från början av BITMAPV5HEADER. Applikationer bör endast komma åt profildata när bV5Size är lika med storleken på BITMAPV5HEADER och bV5CSType är PROFILE\_EMBEDDED eller PROFILE\_LINKED.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Initierar en ny instans av klassen `BitmapV5Header`. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Initierar en ny instans av klassen `BitmapV5Header`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIntent()](#getIntent--) | Hämtar renderingsintentionen för bitmap. |
| [setIntent(long value)](#setIntent-long-) | Anger renderingsintentionen för bitmap. |
| [getProfileData()](#getProfileData--) | Hämtar profildata. |
| [setProfileData(long value)](#setProfileData-long-) | Anger profildata. |
| [getProfileSize()](#getProfileSize--) | Hämtar storleken på profilen. |
| [setProfileSize(long value)](#setProfileSize-long-) | Anger storleken på profilen. |
| [getReserved()](#getReserved--) | Hämtar den reserverade medlemmen. |
| [setReserved(long value)](#setReserved-long-) | Anger den reserverade medlemmen. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Initierar en ny instans av klassen `BitmapV5Header`.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Initierar en ny instans av klassen `BitmapV5Header`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | byte[] | Byte. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Hämtar renderingsintentionen för bitmap.

**Returns:**
long - Intenten.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Anger renderingsintentionen för bitmap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Intenten. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Hämtar profildata.

**Returns:**
long - Profildata.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Anger profildata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Profildata. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Hämtar storleken på profilen.

**Returns:**
long - Storleken på profilen.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Anger storleken på profilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Storleken på profilen. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Hämtar den reserverade medlemmen.

**Returns:**
long - Det reserverade värdet.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Anger den reserverade medlemmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Det reserverade värdet. |


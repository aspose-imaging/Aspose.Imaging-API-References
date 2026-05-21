---
title: "EmfPlusPixelFormat"
second_title: "Aspose.Imaging för Java API-referens"
description: "PixelFormat‑enumerationen definierar pixelformater som stöds i EMF‑bitmapar."
type: docs
weight: 43
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

PixelFormat‑enumerationen definierar pixelformater som stöds i EMF+-bitmaps.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | Formatet är inte specificerat. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | Formatet är monokromt, och en färgpalett‑uppslagstabell används. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | Formatet är 16‑färgs, och en färgpalett‑uppslagstabell används. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | Formatet är 256‑färgs, och en färgpalett‑uppslagstabell används. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | Formatet är 16 bitar per pixel, gråskala. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | Formatet är 16 bitar per pixel; 5 bitar vardera används för de röda, gröna och blå komponenterna. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | Formatet är 16 bitar per pixel; 5 bitar används för den röda komponenten, 6 bitar för den gröna komponenten och 5 bitar för den blå komponenten. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | Formatet är 16 bitar per pixel; 1 bit används för alfakomponenten, och 5 bitar vardera används för de röda, gröna och blå komponenterna. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | Formatet är 24 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | Formatet är 32 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | Formatet är 32 bitar per pixel; 8 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | Formatet är 32 bitar per pixel; 8 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | Formatet är 48 bitar per pixel; 16 bitar vardera används för de röda, gröna och blå komponenterna. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | Formatet är 64 bitar per pixel; 16 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | Formatet är 64 bitar per pixel; 16 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


Formatet är inte specificerat.

--------------------

Pikelformaten specificeras av [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap)-objekt. De kodas enligt följande: - Bit 0‑7: Uppräkning av pixelformatkonstanterna, med start från noll. - Bit 8‑15: Det totala antalet bitar per pixel. - Bit 16: Om satt, indexeras färgvärdet i en palett. - Bit 17: Om satt, är färgvärdet i ett GDI‑stödd format. - Bit 18: Om satt, har färgvärdet en alfakomponent. - Bit 19: Om satt, har färgvärdet en förmultiplicerad alfakomponent. - Bit 20: Om satt, stöds utökade färger, 16‑bitar per kanal. - Bit 21‑31: Reserverade.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


Formatet är monokromt, och en färgpalett‑uppslagstabell används.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


Formatet är 16‑färgs, och en färgpalett‑uppslagstabell används.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


Formatet är 256‑färgs, och en färgpalett‑uppslagstabell används.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


Formatet är 16 bitar per pixel, gråskala.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


Formatet är 16 bitar per pixel; 5 bitar vardera används för de röda, gröna och blå komponenterna. Den återstående biten används inte.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


Formatet är 16 bitar per pixel; 5 bitar används för den röda komponenten, 6 bitar för den gröna komponenten och 5 bitar för den blå komponenten.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


Formatet är 16 bitar per pixel; 1 bit används för alfakomponenten, och 5 bitar vardera används för de röda, gröna och blå komponenterna.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


Formatet är 24 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


Formatet är 32 bitar per pixel; 8 bitar vardera används för de röda, gröna och blå komponenterna. De återstående 8 bitarna används inte.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


Formatet är 32 bitar per pixel; 8 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


Formatet är 32 bitar per pixel; 8 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna. De röda, gröna och blå komponenterna är förmultiplicerade enligt alfakomponenten.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


Formatet är 48 bitar per pixel; 16 bitar vardera används för de röda, gröna och blå komponenterna.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


Formatet är 64 bitar per pixel; 16 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


Formatet är 64 bitar per pixel; 16 bitar vardera används för alfakomponenten, de röda, gröna och blå komponenterna. De röda, gröna och blå komponenterna är förmultiplicerade enligt alfakomponenten.


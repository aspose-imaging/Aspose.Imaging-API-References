---
title: "EmfPlusPixelFormat"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PixelFormat-Aufzählung definiert Pixelformate, die in EMF-Bitmaps unterstützt werden."
type: docs
weight: 43
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

Die PixelFormat-Aufzählung definiert Pixelformate, die in EMF+-Bitmaps unterstützt werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | Das Format ist nicht angegeben. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | Das Format ist monochrom, und eine Farbpalette-Lookup-Tabelle wird verwendet. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | Das Format ist 16‑Farben, und eine Farbpalette-Lookup-Tabelle wird verwendet. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | Das Format ist 256‑Farben, und eine Farbpalette-Lookup-Tabelle wird verwendet. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | Das Format ist 16 Bit pro Pixel, Graustufen. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | Das Format ist 16 Bit pro Pixel; jeweils 5 Bit werden für die roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | Das Format ist 16 Bit pro Pixel; 5 Bit werden für die rote Komponente, 6 Bit für die grüne Komponente und 5 Bit für die blaue Komponente verwendet. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | Das Format ist 16 Bit pro Pixel; 1 Bit wird für die Alpha‑Komponente verwendet und jeweils 5 Bit für die roten, grünen und blauen Komponenten. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | Das Format ist 24 Bit pro Pixel; jeweils 8 Bit werden für die roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | Das Format ist 32 Bit pro Pixel; jeweils 8 Bit werden für die roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | Das Format ist 32 Bit pro Pixel; jeweils 8 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | Das Format ist 32 Bit pro Pixel; jeweils 8 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | Das Format ist 48 Bit pro Pixel; jeweils 16 Bit werden für die roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | Das Format ist 64 Bit pro Pixel; jeweils 16 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | Das Format ist 64 Bit pro Pixel; jeweils 16 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


Das Format ist nicht angegeben.

--------------------

Pixel-Formate werden durch [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap)-Objekte angegeben. Sie werden wie folgt codiert: - Bits 0‑7: Aufzählung der Pixel‑Format‑Konstanten, beginnend bei Null. - Bits 8‑15: Die Gesamtzahl der Bits pro Pixel. - Bit 16: Wenn gesetzt, wird der Farbwert in eine Palette indiziert. - Bit 17: Wenn gesetzt, liegt der Farbwert in einem GDI‑unterstützten Format vor. - Bit 18: Wenn gesetzt, enthält der Farbwert eine Alpha‑Komponente. - Bit 19: Wenn gesetzt, enthält der Farbwert eine vorab multiplizierte Alpha‑Komponente. - Bit 20: Wenn gesetzt, werden erweiterte Farben, 16 Bit pro Kanal, unterstützt. - Bits 21‑31: Reserviert.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


Das Format ist monochrom, und eine Farbpalette-Lookup-Tabelle wird verwendet.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


Das Format ist 16‑Farben, und eine Farbpalette-Lookup-Tabelle wird verwendet.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


Das Format ist 256‑Farben, und eine Farbpalette-Lookup-Tabelle wird verwendet.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


Das Format ist 16 Bit pro Pixel, Graustufen.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


Das Format ist 16 Bit pro Pixel; jeweils 5 Bit werden für die roten, grünen und blauen Komponenten verwendet. Das verbleibende Bit wird nicht genutzt.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


Das Format ist 16 Bit pro Pixel; 5 Bit werden für die rote Komponente, 6 Bit für die grüne Komponente und 5 Bit für die blaue Komponente verwendet.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


Das Format ist 16 Bit pro Pixel; 1 Bit wird für die Alpha‑Komponente verwendet und jeweils 5 Bit für die roten, grünen und blauen Komponenten.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


Das Format ist 24 Bit pro Pixel; jeweils 8 Bit werden für die roten, grünen und blauen Komponenten verwendet.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


Das Format ist 32 Bit pro Pixel; jeweils 8 Bit werden für die roten, grünen und blauen Komponenten verwendet. Die verbleibenden 8 Bit werden nicht genutzt.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


Das Format ist 32 Bit pro Pixel; jeweils 8 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


Das Format ist 32 Bit pro Pixel; jeweils 8 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet. Die roten, grünen und blauen Komponenten sind gemäß der Alpha‑Komponente vorab multipliziert.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


Das Format ist 48 Bit pro Pixel; jeweils 16 Bit werden für die roten, grünen und blauen Komponenten verwendet.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


Das Format ist 64 Bit pro Pixel; jeweils 16 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


Das Format ist 64 Bit pro Pixel; jeweils 16 Bit werden für die Alpha‑, roten, grünen und blauen Komponenten verwendet. Die roten, grünen und blauen Komponenten sind gemäß der Alpha‑Komponente vorab multipliziert.


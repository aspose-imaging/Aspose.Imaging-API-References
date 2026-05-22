---
title: "ColorPalette"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir renk paletini oluşturan renk dizisini tanımlar."
type: docs
weight: 28
url: /tr/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Renk paletini oluşturan renklerin bir dizisini tanımlar. Renkler 32-bit ARGB renkleridir. Miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | `ColorPalette` sınıfının yeni bir örneğini başlatır. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | `ColorPalette` sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | `ColorPalette` sınıfının yeni bir örneğini başlatır. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | `ColorPalette` sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Giriş sayısını alır. |
| [getArgb32Entries()](#getArgb32Entries--) | 32-bit ARGB yapılarının bir dizisini alır. |
| [getEntries()](#getEntries--) | `com.aspose.imaging.Color` yapıların bir dizisini alır. |
| [isCompactPalette()](#isCompactPalette--) | Sıkıştırılmış paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Paleti kopyalar. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Paleti kopyalar. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | En yakın rengin dizinini alır. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | En yakın rengin dizinini alır. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Dizinle 32-bit ARGB palet rengini alır. |
| [getColor(int index)](#getColor-int-) | Dizinle palet rengini alır. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


`ColorPalette` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Entries | int[] | 32-bit ARGB renk paleti girişleri. |
| isCompactPalette | boolean | Kompakt paletin kullanılıp kullanılmadığını gösterir. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


`ColorPalette` sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Entries | int[] | 32-bit ARGB renk paleti girişleri. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


`ColorPalette` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Renk paleti girişleri. |
| isCompactPalette | boolean | Kompakt paletin kullanılıp kullanılmadığını gösterir. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


`ColorPalette` sınıfının yeni bir örneğini başlatır ve IsCompactPalette false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Renk paleti girişleri. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Giriş sayısını alır.

**Returns:**
int - Giriş sayısı.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


32-bit ARGB yapılarının bir dizisini alır.

**Returns:**
int[] - Girişler. Bu [ColorPalette](../../com.aspose.imaging/colorpalette) öğesini oluşturan 32-bit ARGB değerlerinin dizi kopyası.
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


`com.aspose.imaging.Color` yapıların bir dizisini alır.

**Returns:**
com.aspose.imaging.Color[] - Girişler. Bu [ColorPalette](../../com.aspose.imaging/colorpalette) öğesini oluşturan [Color](../../com.aspose.imaging/color) yapıların dizi kopyası.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Sıkıştırılmış paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - kompakt palet kullanılıyorsa `true`; aksi takdirde `false`.

Kompakt palet, görüntünün mümkünse yalnızca belirtilen palet girişlerini içereceği anlamına gelir; başka bir deyişle görüntü daha kompakt olur ve daha az yer kaplar. Aksi takdirde 2^BitsPerPixel girişi olur ve görüntü tüm olası palet girişleri için daha fazla yer ayırır. Bu değeri true olarak ayarlamak ve palet girişlerini değiştirmek, veri hareketi olabileceği için performans cezasına yol açabilir; bu nedenle dikkatli kullanın.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Paleti kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |
| useCompactPalette | boolean | Kompakt paletin kullanılıp kullanılmadığını gösterir. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Paleti kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


En yakın rengin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb32Color | int | 32-bit ARGB renk. |

**Returns:**
int - En yakın rengin indeksi.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


En yakın rengin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Renk. |

**Returns:**
int - En yakın rengin indeksi.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Dizinle 32-bit ARGB palet rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | 32-bit ARGB palet renk indeksi. |

**Returns:**
int - `index` tarafından belirtilen renk paleti girişi.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Dizinle palet rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Palet renk indeksi. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color palette entry specified by the `index`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

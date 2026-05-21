---
title: "Färgpalett"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar en array av färger som utgör en färgpalett."
type: docs
weight: 28
url: /sv/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definierar en array av färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Ej ärftlig.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initierar en ny instans av klassen `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Initierar en ny instans av klassen `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Hämtar antalet poster. |
| [getArgb32Entries()](#getArgb32Entries--) | Hämtar en array av 32-bitars ARGB-strukturer. |
| [getEntries()](#getEntries--) | Hämtar en array av `com.aspose.imaging.Color`-strukturer. |
| [isCompactPalette()](#isCompactPalette--) | Hämtar eller anger ett värde som indikerar om kompakt palett används. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Kopierar paletten. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Kopierar paletten. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Hämtar indexet för den närmaste färgen. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Hämtar indexet för den närmaste färgen. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Hämtar den 32-bitars ARGB-palettfärgen efter index. |
| [getColor(int index)](#getColor-int-) | Hämtar palettfärgen efter index. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Initierar en ny instans av klassen `ColorPalette`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Entries | int[] | De 32-bitars ARGB-färgpalettposterna. |
| isCompactPalette | boolean | Anger om paletten är kompakt. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Entries | int[] | De 32-bitars ARGB-färgpalettposterna. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initierar en ny instans av klassen `ColorPalette`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Färgpalettposterna. |
| isCompactPalette | boolean | Anger om paletten är kompakt. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Färgpalettposterna. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Hämtar antalet poster.

**Returns:**
int - Antalet poster.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Hämtar en array av 32-bitars ARGB-strukturer.

**Returns:**
int[] - Poster. En kopia av arrayen med de 32-bitars ARGB-värdena som utgör denna [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Hämtar en array av `com.aspose.imaging.Color`-strukturer.

**Returns:**
com.aspose.imaging.Color[] - Poster. En kopia av arrayen med [Color](../../com.aspose.imaging/color) strukturerna som utgör denna [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Hämtar eller anger ett värde som indikerar om kompakt palett används.

**Returns:**
boolean - `true` om kompakt palett används; annars `false`.

Kompakt palett innebär att bilden endast kommer att innehålla de angivna palettposterna om möjligt, med andra ord blir bilden mer kompakt och tar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter. Att sätta detta värde till `true` och ändra palettposter kan medföra en prestandapåverkan eftersom dataförflyttning kan ske, så använd det försiktigt.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopierar paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |
| useCompactPalette | boolean | Anger om kompakt palett. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Kopierar paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Hämtar indexet för den närmaste färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Color | int | Den 32-bitars ARGB-färgen. |

**Returns:**
int - Indexet för den närmaste färgen.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Hämtar indexet för den närmaste färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Färgen. |

**Returns:**
int - Indexet för den närmaste färgen.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Hämtar den 32-bitars ARGB-palettfärgen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det 32-bitars ARGB-palettfärgindexet. |

**Returns:**
int - Palettposten som specificeras av `index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Hämtar palettfärgen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Palettfärgindexet. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

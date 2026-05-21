---
title: "ColorPalette"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert ein Array von Farben, das eine Farbpalette bildet."
type: docs
weight: 28
url: /de/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definiert ein Array von Farben, die eine Farbpalette bilden. Die Farben sind 32-bit ARGB Farben. Nicht vererbbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initialisiert eine neue Instanz der Klasse `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initialisiert eine neue Instanz der Klasse `ColorPalette` und IsCompactPalette ist false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Initialisiert eine neue Instanz der Klasse `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Initialisiert eine neue Instanz der Klasse `ColorPalette` und IsCompactPalette ist false. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Liefert die Anzahl der Einträge. |
| [getArgb32Entries()](#getArgb32Entries--) | Liefert ein Array von 32-bit ARGB Strukturen. |
| [getEntries()](#getEntries--) | Liefert ein Array von `com.aspose.imaging.Color`-Strukturen. |
| [isCompactPalette()](#isCompactPalette--) | Liefert oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Kopiert die Palette. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Kopiert die Palette. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Liefert den Index der nächsten Farbe. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Liefert den Index der nächsten Farbe. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Liefert die 32-bit ARGB Palettenfarbe nach Index. |
| [getColor(int index)](#getColor-int-) | Liefert die Palettenfarbe nach Index. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Initialisiert eine neue Instanz der Klasse `ColorPalette`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Entries | int[] | Die 32‑Bit‑ARGB‑Farbpaletteneinträge. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initialisiert eine neue Instanz der Klasse `ColorPalette` und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Entries | int[] | Die 32‑Bit‑ARGB‑Farbpaletteneinträge. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initialisiert eine neue Instanz der Klasse `ColorPalette`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Die Farbpalletteinträge. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Initialisiert eine neue Instanz der Klasse `ColorPalette` und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Die Farbpalletteinträge. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Liefert die Anzahl der Einträge.

**Returns:**
int – Die Anzahl der Einträge.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Liefert ein Array von 32-bit ARGB Strukturen.

**Returns:**
int[] – Die Einträge. Eine Kopie des Arrays der 32‑Bit‑ARGB‑Werte, die diese [ColorPalette](../../com.aspose.imaging/colorpalette) bilden.
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Liefert ein Array von `com.aspose.imaging.Color`-Strukturen.

**Returns:**
com.aspose.imaging.Color[] – Die Einträge. Eine Kopie des Arrays der [Color](../../com.aspose.imaging/color)-Strukturen, die diese [ColorPalette](../../com.aspose.imaging/colorpalette) bilden.
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Liefert oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird.

**Returns:**
boolean – `true`, wenn eine kompakte Palette verwendet wird; andernfalls `false`.

Eine kompakte Palette bedeutet, dass das Bild, wenn möglich, nur die angegebenen Paletteneinträge enthält – mit anderen Worten, das Bild wird kompakter und belegt weniger Speicher; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf true und das Ändern von Paletteneinträgen kann zu Leistungseinbußen führen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopiert die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |
| useCompactPalette | boolean | Gibt an, ob eine kompakte Palette verwendet wird. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Kopiert die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Liefert den Index der nächsten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns:**
int – Der Index der nächstgelegenen Farbe.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Liefert den Index der nächsten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Die Farbe. |

**Returns:**
int – Der Index der nächstgelegenen Farbe.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Liefert die 32-bit ARGB Palettenfarbe nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der 32‑Bit‑ARGB-Palettenfarbindex. |

**Returns:**
int – Der Farbpalletteintrag, der durch den `index` angegeben wird.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Liefert die Palettenfarbe nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Palettenfarbindex. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

---
title: "ColorPalette"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit un tableau de couleurs qui composent une palette de couleurs."
type: docs
weight: 28
url: /fr/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Définit un tableau de couleurs qui composent une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initialise une nouvelle instance de la classe `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Initialise une nouvelle instance de la classe `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Obtient le nombre d'entrées. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtient un tableau de structures ARGB 32 bits. |
| [getEntries()](#getEntries--) | Obtient un tableau de structures `com.aspose.imaging.Color`. |
| [isCompactPalette()](#isCompactPalette--) | Obtient ou définit une valeur indiquant si une palette compacte est utilisée. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Copie la palette. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Copie la palette. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtient l'index de la couleur la plus proche. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Obtient l'index de la couleur la plus proche. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtient la couleur de la palette ARGB 32 bits par index. |
| [getColor(int index)](#getColor-int-) | Obtient la couleur de la palette par index. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Initialise une nouvelle instance de la classe `ColorPalette`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |
| isCompactPalette | boolean | Indiquant si la palette est compacte. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initialise une nouvelle instance de la classe `ColorPalette`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Les entrées de la palette de couleurs. |
| isCompactPalette | boolean | Indiquant si la palette est compacte. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | Les entrées de la palette de couleurs. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Obtient le nombre d'entrées.

**Returns:**
int - Le nombre d'entrées.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Obtient un tableau de structures ARGB 32 bits.

**Returns:**
int[] - Les entrées. La copie du tableau des valeurs ARGB 32 bits qui composent ce [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Obtient un tableau de structures `com.aspose.imaging.Color`.

**Returns:**
com.aspose.imaging.Color[] - Les entrées. La copie du tableau des structures [Color](../../com.aspose.imaging/color) qui composent ce [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Obtient ou définit une valeur indiquant si une palette compacte est utilisée.

**Returns:**
boolean - `true` si une palette compacte est utilisée ; sinon, `false`.

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, autrement dit l'image sera plus compacte et occupera moins d'espace ; sinon il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Mettre cette valeur à true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent survenir, utilisez-le donc avec précaution.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copie la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |
| useCompactPalette | boolean | Indiquant si la palette est compacte. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copie la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Obtient l'index de la couleur la plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Color | int | La couleur ARGB 32 bits. |

**Returns:**
int - L'index de la couleur la plus proche.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Obtient l'index de la couleur la plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | La couleur. |

**Returns:**
int - L'index de la couleur la plus proche.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Obtient la couleur de la palette ARGB 32 bits par index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de couleur de la palette ARGB 32 bits. |

**Returns:**
int - L'entrée de la palette de couleurs spécifiée par le `index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Obtient la couleur de la palette par index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de couleur de la palette. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

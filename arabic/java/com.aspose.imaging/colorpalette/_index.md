---
title: "ColorPalette"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يعرف مصفوفة من الألوان التي تشكل لوحة ألوان."
type: docs
weight: 28
url: /ar/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

يحدد مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32-بت. غير قابل للوراثة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | ينشئ مثيلاً جديداً من الفئة `ColorPalette`. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | ينشئ مثيلاً جديداً من الفئة `ColorPalette` و IsCompactPalette هو false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | ينشئ مثيلاً جديداً من الفئة `ColorPalette`. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | ينشئ مثيلاً جديداً من الفئة `ColorPalette` و IsCompactPalette هو false. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | يحصل على عدد الإدخالات. |
| [getArgb32Entries()](#getArgb32Entries--) | يحصل على مصفوفة من هياكل ARGB 32‑بت. |
| [getEntries()](#getEntries--) | يحصل على مصفوفة من هياكل `com.aspose.imaging.Color`. |
| [isCompactPalette()](#isCompactPalette--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يتم استخدام لوحة ألوان مدمجة. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | ينسخ لوحة الألوان. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | ينسخ لوحة الألوان. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | يحصل على فهرس أقرب لون. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | يحصل على فهرس أقرب لون. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | يحصل على لون لوحة ألوان ARGB 32‑بت حسب الفهرس. |
| [getColor(int index)](#getColor-int-) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


ينشئ مثيلاً جديداً من الفئة `ColorPalette`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Entries | int[] | إدخالات لوحة ألوان ARGB 32‑بت. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت لوحة الألوان مدمجة. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


ينشئ مثيلاً جديداً من الفئة `ColorPalette` و IsCompactPalette هو false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Entries | int[] | إدخالات لوحة ألوان ARGB 32‑بت. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


ينشئ مثيلاً جديداً من الفئة `ColorPalette`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | إدخالات لوحة الألوان. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت لوحة الألوان مدمجة. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


ينشئ مثيلاً جديداً من الفئة `ColorPalette` و IsCompactPalette هو false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | إدخالات لوحة الألوان. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


يحصل على عدد الإدخالات.

**Returns:**
int - عدد الإدخالات.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


يحصل على مصفوفة من هياكل ARGB 32‑بت.

**Returns:**
int[] - الإدخالات. نسخة من مصفوفة القيم 32‑بت ARGB التي تشكل هذه [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


يحصل على مصفوفة من هياكل `com.aspose.imaging.Color`.

**Returns:**
com.aspose.imaging.Color[] - الإدخالات. نسخة من مصفوفة هياكل [Color](../../com.aspose.imaging/color) التي تشكل هذه [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يتم استخدام لوحة ألوان مدمجة.

**Returns:**
boolean - `true` إذا تم استخدام لوحة ألوان مدمجة؛ وإلا `false`.

لوحة الألوان المدمجة تعني أن الصورة ستحتوي فقط على إدخالات لوحة الألوان المحددة إذا كان ذلك ممكنًا، أو بعبارة أخرى ستكون الصورة أكثر تجميعًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel إدخالات وستحجز الصورة مساحة أكبر لجميع إدخالات لوحة الألوان الممكنة. ضبط هذه القيمة إلى true وتغيير إدخالات لوحة الألوان قد يسبب عقوبة في الأداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


ينسخ لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |
| useCompactPalette | boolean | يشير إلى ما إذا كانت لوحة الألوان مدمجة. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


ينسخ لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


يحصل على فهرس أقرب لون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Color | int | لون ARGB 32‑بت. |

**Returns:**
int - فهرس أقرب لون.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


يحصل على فهرس أقرب لون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | اللون. |

**Returns:**
int - فهرس أقرب لون.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


يحصل على لون لوحة ألوان ARGB 32‑بت حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس لون لوحة ألوان ARGB 32‑بت. |

**Returns:**
int - إدخال لوحة الألوان المحدد بواسطة `index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


يحصل على لون لوحة الألوان حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس لون لوحة الألوان. |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

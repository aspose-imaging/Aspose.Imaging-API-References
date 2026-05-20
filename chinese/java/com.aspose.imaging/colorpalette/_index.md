---
title: "颜色调色板"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义组成调色板的颜色数组。"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

定义组成颜色调色板的颜色数组。颜色为 32 位 ARGB 颜色。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | 初始化 `ColorPalette` 类的新实例。 |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | 初始化 `ColorPalette` 类的新实例，并且 IsCompactPalette 为 false。 |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | 初始化 `ColorPalette` 类的新实例。 |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | 初始化 `ColorPalette` 类的新实例，并且 IsCompactPalette 为 false。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | 获取条目计数。 |
| [getArgb32Entries()](#getArgb32Entries--) | 获取 32 位 ARGB 结构的数组。 |
| [getEntries()](#getEntries--) | 获取 `com.aspose.imaging.Color` 结构的数组。 |
| [isCompactPalette()](#isCompactPalette--) | 获取或设置指示是否使用紧凑调色板的值。 |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | 复制调色板。 |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | 复制调色板。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 获取最近颜色的索引。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | 获取最近颜色的索引。 |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 通过索引获取 32 位 ARGB 调色板颜色。 |
| [getColor(int index)](#getColor-int-) | 通过索引获取调色板颜色。 |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


初始化 `ColorPalette` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb32Entries | int[] | 32 位 ARGB 颜色调色板条目。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


初始化 `ColorPalette` 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb32Entries | int[] | 32 位 ARGB 颜色调色板条目。 |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


初始化 `ColorPalette` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | 颜色调色板条目。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


初始化 `ColorPalette` 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | 颜色调色板条目。 |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


获取条目计数。

**Returns:**
int - 条目计数。
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


获取 32 位 ARGB 结构的数组。

**Returns:**
int[] - 条目。由构成此 [ColorPalette](../../com.aspose.imaging/colorpalette) 的 32 位 ARGB 值数组的副本。
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


获取 `com.aspose.imaging.Color` 结构的数组。

**Returns:**
com.aspose.imaging.Color[] - 条目。由构成此 [ColorPalette](../../com.aspose.imaging/colorpalette) 的 [Color](../../com.aspose.imaging/color) 结构数组的副本。
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


获取或设置指示是否使用紧凑调色板的值。

**Returns:**
boolean - 如果使用紧凑调色板则为 `true`；否则为 `false`。

紧凑调色板意味着图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目预留更多空间。将此值设为 true 并更改调色板条目可能会导致性能下降，因为可能会发生数据移动，所以请谨慎使用。
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


复制调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |
| useCompactPalette | boolean | 指示是否使用紧凑调色板。 |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


复制调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


获取最近颜色的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb32Color | int | 32 位 ARGB 颜色。 |

**Returns:**
int - 最近颜色的索引。
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


获取最近颜色的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | 颜色。 |

**Returns:**
int - 最近颜色的索引。
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


通过索引获取 32 位 ARGB 调色板颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 32 位 ARGB 调色板颜色索引。 |

**Returns:**
int - 由 `index` 指定的颜色调色板条目。
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


通过索引获取调色板颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 调色板颜色索引。 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean

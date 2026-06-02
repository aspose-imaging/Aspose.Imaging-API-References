---
title: "EmfPlusPalette"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusPalette 对象指定构成调色板的颜色。"
type: docs
weight: 57
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

EmfPlusPalette 对象指定构成调色板的颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | 获取或设置调色板样式标志。 |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | 获取或设置调色板样式标志。 |
| [getArgb32Entries()](#getArgb32Entries--) | 获取或设置调色板条目。 |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | 获取或设置调色板条目。 |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


获取或设置调色板样式标志。

值：PaletteStyleFlags（4 字节）：一个 32 位无符号整数，指定调色板中数据的属性。此值必须由 `EmfPlusPaletteStyleFlags` 标志组成。

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


获取或设置调色板样式标志。

值：PaletteStyleFlags（4 字节）：一个 32 位无符号整数，指定调色板中数据的属性。此值必须由 `EmfPlusPaletteStyleFlags` 标志组成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


获取或设置调色板条目。

值：PaletteEntries（可变）：一个由 PaletteCount 个 32 位 ARGB 对象组成的数组，指定调色板中的数据。

**Returns:**
int[] - 调色板条目的副本。
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


获取或设置调色板条目。

值：PaletteEntries（可变）：一个由 PaletteCount 个 32 位 ARGB 对象组成的数组，指定调色板中的数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |


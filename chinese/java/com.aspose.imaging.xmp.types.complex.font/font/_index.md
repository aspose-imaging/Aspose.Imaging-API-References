---
title: "字体"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XMP 字体。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.types.complex.font/font/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

表示 XMP 字体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Font()](#Font--) | 初始化 `Font` 类的新实例。 |
| [Font(String fontFamily)](#Font-java.lang.String-) | 初始化 `Font` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChildFontFiles()](#getChildFontFiles--) | 获取或设置组成复合字体的字体文件名数组。 |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | 获取或设置组成复合字体的字体文件名数组。 |
| [isComposite()](#isComposite--) | 获取或设置指示此字体是否为复合字体的值。 |
| [setComposite(boolean value)](#setComposite-boolean-) | 获取或设置指示此字体是否为复合字体的值。 |
| [getFontFace()](#getFontFace--) | 获取或设置字体面。 |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | 获取或设置字体面。 |
| [getFontFamily()](#getFontFamily--) | 获取或设置字体族。 |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | 获取或设置字体族。 |
| [getFontFileName()](#getFontFileName--) | 获取或设置不含完整路径的字体文件名。 |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | 获取或设置不含完整路径的字体文件名。 |
| [getFontName()](#getFontName--) | 获取或设置 PostScript 字体名称。 |
| [setFontName(String value)](#setFontName-java.lang.String-) | 获取或设置 PostScript 字体名称。 |
| [getFontType()](#getFontType--) | 获取或设置字体类型。 |
| [setFontType(String value)](#setFontType-java.lang.String-) | 获取或设置字体类型。 |
| [getVersion()](#getVersion--) | 获取或设置字体版本。 |
| [setVersion(String value)](#setVersion-java.lang.String-) | 获取或设置字体版本。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### Font() {#Font--}
```
public Font()
```


初始化 `Font` 类的新实例。

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


初始化 `Font` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamily | java.lang.String | 字体族。 |

### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


获取或设置组成复合字体的字体文件名数组。

值：组成复合字体的字体文件名数组。

**Returns:**
java.lang.String[]
### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


获取或设置组成复合字体的字体文件名数组。

值：组成复合字体的字体文件名数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### isComposite() {#isComposite--}
```
public boolean isComposite()
```


获取或设置指示此字体是否为复合字体的值。

值：如果此字体是复合的，则为 `true`；否则为 `false`。

**Returns:**
boolean
### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


获取或设置指示此字体是否为复合字体的值。

值：如果此字体是复合的，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


获取或设置字体面。

值：字体面。

**Returns:**
java.lang.String
### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


获取或设置字体面。

值：字体面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


获取或设置字体族。

值：字体系列。

**Returns:**
java.lang.String
### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


获取或设置字体族。

值：字体系列。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


获取或设置不含完整路径的字体文件名。

值：不含完整路径的字体文件名。

**Returns:**
java.lang.String
### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


获取或设置不含完整路径的字体文件名。

值：不含完整路径的字体文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontName() {#getFontName--}
```
public String getFontName()
```


获取或设置 PostScript 字体名称。

值：PostScript 字体名称。

**Returns:**
java.lang.String
### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


获取或设置 PostScript 字体名称。

值：PostScript 字体名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontType() {#getFontType--}
```
public String getFontType()
```


获取或设置字体类型。

TrueType、Type 1、Open Type 等。值：字体类型。

**Returns:**
java.lang.String
### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


获取或设置字体类型。

TrueType、Type 1、Open Type 等。值：字体类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


获取或设置字体版本。

/version 用于 Type1 字体，nameId 5 用于 Apple True Type 和 OpenType，/CIDFontVersion 用于 CID 字体，位图字体为空字符串。值：字体版本。

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


获取或设置字体版本。

/version 用于 Type1 字体，nameId 5 用于 Apple True Type 和 OpenType，/CIDFontVersion 用于 CID 字体，位图字体为空字符串。值：字体版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。

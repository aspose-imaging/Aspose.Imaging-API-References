---
title: "EmfLogFontPanose"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LogFontPanose 对象指定了逻辑字体的 PANOSE 特性。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

LogFontPanose 对象指定了逻辑字体的 PANOSE 特性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | 初始化 `EmfLogFontPanose` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFullName()](#getFullName--) | 获取或设置一个 64 个 Unicode 字符的字符串，用于定义字体的完整名称。 |
| [setFullName(String value)](#setFullName-java.lang.String-) | 获取或设置一个 64 个 Unicode 字符的字符串，用于定义字体的完整名称。 |
| [getStyle()](#getStyle--) | 获取或设置 定义字体样式的 32 个 Unicode 字符的字符串。 |
| [setStyle(String value)](#setStyle-java.lang.String-) | 获取或设置 定义字体样式的 32 个 Unicode 字符的字符串。 |
| [getVersion()](#getVersion--) | 获取或设置此字段，必须忽略。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置此字段，必须忽略。 |
| [getStyleSize()](#getStyleSize--) | 获取或设置一个 32 位无符号整数，指定执行字体微调的点大小。 |
| [setStyleSize(int value)](#setStyleSize-int-) | 获取或设置一个 32 位无符号整数，指定执行字体微调的点大小。 |
| [getMatch()](#getMatch--) | 获取或设置此字段，必须忽略。 |
| [setMatch(int value)](#setMatch-int-) | 获取或设置此字段，必须忽略。 |
| [getVendorId()](#getVendorId--) | 获取或设置此字段，必须忽略。 |
| [setVendorId(int value)](#setVendorId-int-) | 获取或设置此字段，必须忽略。 |
| [getCulture()](#getCulture--) | 获取或设置一个 32 位无符号整数，该整数必须设为零且必须被忽略。 |
| [setCulture(int value)](#setCulture-int-) | 获取或设置一个 32 位无符号整数，该整数必须设为零且必须被忽略。 |
| [getPanose()](#getPanose--) | 获取或设置一个 Panose 对象（第 2.2.21 节），用于指定逻辑字体的 PANOSE 特性。 |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | 获取或设置一个 Panose 对象（第 2.2.21 节），用于指定逻辑字体的 PANOSE 特性。 |
| [getPadding()](#getPadding--) | 获取或设置仅用于确保此结构 32 位对齐的字段。 |
| [setPadding(short value)](#setPadding-short-) | 获取或设置仅用于确保此结构 32 位对齐的字段。 |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


初始化 `EmfLogFontPanose` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | 基础日志字体。 |

### getFullName() {#getFullName--}
```
public String getFullName()
```


获取或设置一个 64 个 Unicode 字符的字符串，用于定义字体的完整名称。如果该字符串的长度少于 64 个字符，则必须存在一个终止的 NULL，之后该字段的其余部分必须被忽略。

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


获取或设置一个 64 个 Unicode 字符的字符串，用于定义字体的完整名称。如果该字符串的长度少于 64 个字符，则必须存在一个终止的 NULL，之后该字段的其余部分必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


获取或设置 定义字体样式的 32 个 Unicode 字符的字符串。如果此字符串的长度小于 32 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


获取或设置 定义字体样式的 32 个 Unicode 字符的字符串。如果此字符串的长度小于 32 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置此字段，必须忽略。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置此字段，必须忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


获取或设置一个 32 位无符号整数，指定执行字体微调的点大小。如果设为零，则在 LogFont 对象的 Height 字段对应的点大小下执行字体微调。

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


获取或设置一个 32 位无符号整数，指定执行字体微调的点大小。如果设为零，则在 LogFont 对象的 Height 字段对应的点大小下执行字体微调。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


获取或设置此字段，必须忽略。

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


获取或设置此字段，必须忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


获取或设置此字段，必须忽略。

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


获取或设置此字段，必须忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


获取或设置一个 32 位无符号整数，该整数必须设为零且必须被忽略。

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


获取或设置一个 32 位无符号整数，该整数必须设为零且必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


获取或设置一个 Panose 对象（第 2.2.21 节），用于指定逻辑字体的 PANOSE 特性。如果该对象的所有字段均为零，则必须忽略。

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


获取或设置一个 Panose 对象（第 2.2.21 节），用于指定逻辑字体的 PANOSE 特性。如果该对象的所有字段均为零，则必须忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


获取或设置仅用于确保此结构 32 位对齐的字段。它必须被忽略。

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


获取或设置仅用于确保此结构 32 位对齐的字段。它必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |


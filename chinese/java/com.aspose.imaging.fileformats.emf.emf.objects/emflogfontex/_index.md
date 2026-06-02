---
title: "EmfLogFontEx"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LogFontEx 对象指定了逻辑字体的扩展属性。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public class EmfLogFontEx extends EmfLogFont
```

LogFontEx 对象指定了逻辑字体的扩展属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLogFontEx(EmfLogFont emfLogFont)](#EmfLogFontEx-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | 初始化 `EmfLogFontEx` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFullName()](#getFullName--) | 获取或设置 包含字体全名的 64 个 Unicode 字符的字符串。 |
| [setFullName(String value)](#setFullName-java.lang.String-) | 获取或设置 包含字体全名的 64 个 Unicode 字符的字符串。 |
| [getStyle()](#getStyle--) | 获取或设置 定义字体样式的 32 个 Unicode 字符的字符串。 |
| [setStyle(String value)](#setStyle-java.lang.String-) | 获取或设置 定义字体样式的 32 个 Unicode 字符的字符串。 |
| [getScript()](#getScript--) | 获取或设置 定义字体字符集的 32 个 Unicode 字符的字符串。 |
| [setScript(String value)](#setScript-java.lang.String-) | 获取或设置 定义字体字符集的 32 个 Unicode 字符的字符串。 |
### EmfLogFontEx(EmfLogFont emfLogFont) {#EmfLogFontEx-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontEx(EmfLogFont emfLogFont)
```


初始化 `EmfLogFontEx` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | EMF 日志字体。 |

### getFullName() {#getFullName--}
```
public String getFullName()
```


获取或设置 包含字体全名的 64 个 Unicode 字符的字符串。如果此字符串的长度小于 64 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


获取或设置 包含字体全名的 64 个 Unicode 字符的字符串。如果此字符串的长度小于 64 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。

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

### getScript() {#getScript--}
```
public String getScript()
```


获取或设置 定义字体字符集的 32 个 Unicode 字符的字符串。如果此字符串的长度小于 32 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。

**Returns:**
java.lang.String
### setScript(String value) {#setScript-java.lang.String-}
```
public void setScript(String value)
```


获取或设置 定义字体字符集的 32 个 Unicode 字符的字符串。如果此字符串的长度小于 32 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |


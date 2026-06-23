---
title: "PdfPackage"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 Adobe PDF 命名空间。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.schemas.pdf/pdfpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public final class PdfPackage extends XmpPackage
```

表示 Adobe PDF 命名空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPackage()](#PdfPackage--) | 初始化一个新的 `PdfPackage` 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 添加字符串属性。 |
| [setKeywords(String keywords)](#setKeywords-java.lang.String-) | 设置关键字。 |
| [setPdfVersion(String version)](#setPdfVersion-java.lang.String-) | 设置 PDF 版本。 |
| [setProducer(String producer)](#setProducer-java.lang.String-) | 设置创建 PDF 的工具名称。 |
| [setTrapped(boolean isTrapped)](#setTrapped-boolean-) | 设置 trapped。 |
### PdfPackage() {#PdfPackage--}
```
public PdfPackage()
```


初始化一个新的 `PdfPackage` 类实例。

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


添加字符串属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| 值 | java.lang.String | 字符串值。 |

### setKeywords(String keywords) {#setKeywords-java.lang.String-}
```
public void setKeywords(String keywords)
```


设置关键字。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keywords | java.lang.String | 关键字。 |

### setPdfVersion(String version) {#setPdfVersion-java.lang.String-}
```
public void setPdfVersion(String version)
```


设置 PDF 版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| version | java.lang.String | PDF 版本，例如：1.0、1.3 等。 |

### setProducer(String producer) {#setProducer-java.lang.String-}
```
public void setProducer(String producer)
```


设置创建 PDF 的工具名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| producer | java.lang.String | 生产者名称。 |

### setTrapped(boolean isTrapped) {#setTrapped-boolean-}
```
public void setTrapped(boolean isTrapped)
```


设置 trapped。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isTrapped | boolean | 如果设置为 `true`，文档已被 trapped。 |


---
title: "XmpBasicPackage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 XMP 基本命名空间。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object，[com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

表示 XMP 基本命名空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | 初始化 `XmpBasicPackage` 类的新实例。 |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | 初始化 `XmpBasicPackage` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | 评级拒绝值。 |
| [RATING_MIN](#RATING-MIN) | 评级最小值。 |
| [RATING_MAX](#RATING-MAX) | 评级最大值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | 设置标签。 |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 添加字符串属性。 |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | 添加资源创建日期。 |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | 添加资源创建日期。 |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | 设置创建工具。 |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | 设置标识符。 |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | 添加元数据最后更改日期。 |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | 添加元数据最后更改日期。 |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | 添加资源最后修改日期。 |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | 添加资源最后修改日期。 |
| [setRating(int choice)](#setRating-int-) | 设置评级。 |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


初始化 `XmpBasicPackage` 类的新实例。

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


初始化 `XmpBasicPackage` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 命名空间 URI。 |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


评级拒绝值。

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


评级最小值。

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


评级最大值。

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


设置标签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标签 | java.lang.String | 标签。 |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


添加字符串属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 键 | java.lang.String | 键的字符串表示形式，用于标识添加的值。 |
| value | java.lang.String | 字符串值。 |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


添加资源创建日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createdDate | java.util.Date | 创建日期。 |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


添加资源创建日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createdDate | java.lang.String | 创建日期。 |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


设置创建工具。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| creatorTool | java.lang.String | 工具的名称。 |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


设置标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标识符 | java.lang.String[] | 标识符。 |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


添加元数据最后更改日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| metadataDate | java.util.Date | 元数据日期。 |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


添加元数据最后更改日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| metadataDate | java.lang.String | 元数据日期。 |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


添加资源最后修改日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| modifiedDate | java.util.Date | 最后修改日期。 |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


添加资源最后修改日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| modifiedDate | java.lang.String | 最后修改日期。 |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


设置评级。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 选择 | int | 从 -1 到 5 |


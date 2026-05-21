---
title: "图层"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 Photoshop 文本图层。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

表示 Photoshop 文本图层。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | 初始化 `Layer` 类的新实例。 |
| [Layer()](#Layer--) | 初始化 `Layer` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 获取或设置文本图层的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置文本图层的名称。 |
| [getText()](#getText--) | 获取或设置图层的文本内容。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置图层的文本内容。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式的字符串值。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `System.Object` 是否等于此实例。 |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | 指示当前对象是否等于同类型的另一个对象。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


初始化 `Layer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layerName | java.lang.String | 图层的名称。 |
| layerText | java.lang.String | 图层文本。 |

### Layer() {#Layer--}
```
public Layer()
```


初始化 `Layer` 类的新实例。

### getName() {#getName--}
```
public String getName()
```


获取或设置文本图层的名称。

值：文本图层的名称。

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


获取或设置文本图层的名称。

值：文本图层的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


获取或设置图层的文本内容。

值：图层的文本内容。

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


获取或设置图层的文本内容。

值：图层的文本内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `System.Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 与此实例比较的 `System.Object`。 |

**Returns:**
boolean - 如果指定的 `System.Object` 等于此实例，则为 `true`；否则，为 `false`。
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | 用于与此对象比较的对象。 |

**Returns:**
boolean - 如果当前对象等于 `other` 参数则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。

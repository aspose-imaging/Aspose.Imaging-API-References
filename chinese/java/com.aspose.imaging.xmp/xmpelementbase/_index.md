---
title: "XmpElementBase"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示包含属性的基础 XMP 元素。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

表示包含属性的基础 XMP 元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | 添加属性。 |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | 获取属性。 |
| [clearAttributes()](#clearAttributes--) | 删除所有属性。 |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


添加属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性。 |
| value | java.lang.String | 值。 |

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


获取属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性。 |

**Returns:**
java.lang.String - 返回指定属性名称的属性。
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


删除所有属性。

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | 用于与此对象比较的对象。 |

**Returns:**
boolean - 如果当前对象等于 `other` 参数则为 true；否则为 false。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 `Object`。 |

**Returns:**
布尔值 - 如果指定的 `Object` 等于此实例则为 `true`；否则为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。

---
title: "XmpCollection"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "XMP 元素集合。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

XMP 元素集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | 初始化 [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | 添加新项。 |
| [addObject(Object item)](#addObject-java.lang.Object-) | 添加 XMP 数据项。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引处的项。 |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | 向集合中添加项。 |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | 将集合的元素复制到数组中，从特定的数组索引开始。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取此对象的 XMP 字符串值。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示形式。 |
| [toString()](#toString--) | 返回表示此实例的 XML 字符串。 |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


初始化 [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection) 类的新实例。

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


添加新项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | java.lang.Object | 要添加到项目列表中的项目。 |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


添加 XMP 数据项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项 | java.lang.Object | 一个 XMP 项目。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引处的项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的项的零基索引。 |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


向集合中添加项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | 要添加到集合的对象。 |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


将集合的元素复制到数组中，从特定的数组索引开始。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | 一维数组，是从集合复制的元素的目标。该数组必须使用零基索引。 |
| arrayIndex | int | 在数组中复制开始的零基索引。 |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


获取此对象的 XMP 字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


将 XMP 值转换为 XML 表示形式。

**Returns:**
java.lang.String - 返回转换为 XML 表示形式的 XMP 值。
### toString() {#toString--}
```
public String toString()
```


返回表示此实例的 XML 字符串。

**Returns:**
java.lang.String - 表示此实例的 XML 字符串。

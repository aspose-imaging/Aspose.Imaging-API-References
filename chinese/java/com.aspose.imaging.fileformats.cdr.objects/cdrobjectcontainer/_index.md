---
title: "CdrObjectContainer"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "cdr 对象容器"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject)
```
public abstract class CdrObjectContainer extends CdrObject
```

cdr 对象容器
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CdrObjectContainer()](#CdrObjectContainer--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChilds()](#getChilds--) | 获取对象。 |
| [getLoadToLastChild()](#getLoadToLastChild--) | 获取一个值，指示是否 [load to last child]。 |
| [setLoadToLastChild(boolean value)](#setLoadToLastChild-boolean-) | 设置一个值，指示是否 [load to last child]。 |
| [getLastChild()](#getLastChild--) | 获取最后一个子对象。 |
| [setLastChild(CdrObjectContainer value)](#setLastChild-com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer-) | 设置最后一个子对象。 |
| [getHidden()](#getHidden--) | 获取一个值，指示此 [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) 是否可见。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 设置一个值，指示此 [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) 是否可见。 |
| [addChildObject(CdrObject cdrObject)](#addChildObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-) | 添加子对象。 |
| [insertObject(CdrObject cdrObject)](#insertObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-) | 插入对象 |
### CdrObjectContainer() {#CdrObjectContainer--}
```
public CdrObjectContainer()
```


### getChilds() {#getChilds--}
```
public final List<CdrObject> getChilds()
```


获取对象。

**Returns:**
java.util.List<com.aspose.imaging.fileformats.cdr.objects.CdrObject> - 对象。
### getLoadToLastChild() {#getLoadToLastChild--}
```
public final boolean getLoadToLastChild()
```


获取一个值，指示是否 [load to last child]。

**Returns:**
boolean - 表示是否[load to last child]的值。
### setLoadToLastChild(boolean value) {#setLoadToLastChild-boolean-}
```
public final void setLoadToLastChild(boolean value)
```


设置一个值，指示是否 [load to last child]。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 表示是否[load to last child]的值。 |

### getLastChild() {#getLastChild--}
```
public final CdrObjectContainer getLastChild()
```


获取最后一个子对象。

**Returns:**
[CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) - the last child.
### setLastChild(CdrObjectContainer value) {#setLastChild-com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer-}
```
public final void setLastChild(CdrObjectContainer value)
```


设置最后一个子对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) | 最后一个子项。 |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


获取一个值，指示此 [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) 是否可见。

值：`true` 表示可见；否则为 `false`。

**Returns:**
boolean - 表示此[CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)是否可见的值。
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


设置一个值，指示此 [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) 是否可见。

值：`true` 表示可见；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 表示此[CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)是否可见的值。 |

### addChildObject(CdrObject cdrObject) {#addChildObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-}
```
public final void addChildObject(CdrObject cdrObject)
```


添加子对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cdrObject | [CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject) | CDR 对象。 |

### insertObject(CdrObject cdrObject) {#insertObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-}
```
public final void insertObject(CdrObject cdrObject)
```


插入对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cdrObject | [CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject) | CDR 对象。 |


---
title: "EmfPlusGraphicsVersion"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusGraphicsVersion 对象指定用于创建 EMF 元文件的操作系统图形版本。"
type: docs
weight: 44
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

EmfPlusGraphicsVersion 对象指定用于创建 EMF+ 元文件的操作系统图形版本。

图形版本可由供应商扩展；然而，为确保互操作性，任何此类扩展必须在 EMF+ 元文件的客户端和服务器端都实现。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | 获取 MetafileSignature（20 位）：标识元文件类型的值。 |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | 获取 MetafileSignature（20 位）：标识元文件类型的值。 |
| [getGraphicsVersion()](#getGraphicsVersion--) | 获取 GraphicsVersion（12 位）：操作系统图形的版本。 |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | 获取 GraphicsVersion（12 位）：操作系统图形的版本。 |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


获取 MetafileSignature（20 位）：标识元文件类型的值。EMF+ 元文件的该值为 0xDBC01。

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


获取 MetafileSignature（20 位）：标识元文件类型的值。EMF+ 元文件的该值为 0xDBC01。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


获取 GraphicsVersion（12 位）：操作系统图形的版本。此值必须在 `EmfPlusGraphicsVersion` 枚举中定义。

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


获取 GraphicsVersion（12 位）：操作系统图形的版本。此值必须在 `EmfPlusGraphicsVersion` 枚举中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |


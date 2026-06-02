---
title: "EmfPlusCustomLineCap"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusCustomLineCap 对象指定由图形笔绘制的线段两端使用的形状。"
type: docs
weight: 34
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusCustomLineCap extends EmfPlusGraphicsObjectType
```

EmfPlusCustomLineCap 对象指定由图形笔绘制的线段两端使用的形状。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusCustomLineCap()](#EmfPlusCustomLineCap--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取或设置一个 32 位有符号整数，指定自定义线帽对象的类型，该类型决定 CustomLineCapData 字段的内容。 |
| [setType(int value)](#setType-int-) | 获取或设置一个 32 位有符号整数，指定自定义线帽对象的类型，该类型决定 CustomLineCapData 字段的内容。 |
| [getCustomLineCapData()](#getCustomLineCapData--) | 获取或设置可变长度数据，以定义 Type 字段中指定的自定义线帽数据对象。 |
| [setCustomLineCapData(EmfPlusCustomBaseLineCap value)](#setCustomLineCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap-) | 获取或设置可变长度数据，以定义 Type 字段中指定的自定义线帽数据对象。 |
### EmfPlusCustomLineCap() {#EmfPlusCustomLineCap--}
```
public EmfPlusCustomLineCap()
```


### getType() {#getType--}
```
public int getType()
```


获取或设置一个 32 位有符号整数，指定自定义线帽对象的类型，该类型决定 CustomLineCapData 字段的内容。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置一个 32 位有符号整数，指定自定义线帽对象的类型，该类型决定 CustomLineCapData 字段的内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCustomLineCapData() {#getCustomLineCapData--}
```
public EmfPlusCustomBaseLineCap getCustomLineCapData()
```


获取或设置可变长度数据，以定义 Type 字段中指定的自定义线帽数据对象。该数据的内容和格式可能因每种自定义线帽类型而异。

**Returns:**
[EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
### setCustomLineCapData(EmfPlusCustomBaseLineCap value) {#setCustomLineCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap-}
```
public void setCustomLineCapData(EmfPlusCustomBaseLineCap value)
```


获取或设置可变长度数据，以定义 Type 字段中指定的自定义线帽数据对象。该数据的内容和格式可能因每种自定义线帽类型而异。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap) |  |


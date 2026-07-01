---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusCustomLineCapOptionalData 对象指定自定义线帽的可选填充和轮廓数据。"
type: docs
weight: 37
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

EmfPlusCustomLineCapOptionalData 对象指定自定义线帽的可选填充和轮廓数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillData()](#getFillData--) | 获取或设置可选的 EmfPlusFillPath 对象（第 2.2.2.17 节），指定用于填充自定义图形线帽的路径。 |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | 获取或设置可选的 EmfPlusFillPath 对象（第 2.2.2.17 节），指定用于填充自定义图形线帽的路径。 |
| [getOutlineData()](#getOutlineData--) | 获取或设置可选的 EmfPlusLinePath 对象（第 2.2.2.26 节），指定用于描绘自定义图形线帽的路径。 |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | 获取或设置可选的 EmfPlusLinePath 对象（第 2.2.2.26 节），指定用于描绘自定义图形线帽的路径。 |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


获取或设置可选的 EmfPlusFillPath 对象（第 2.2.2.17 节），指定用于填充自定义图形线帽的路径。如果在 EmfPlusCustomLineCapData 对象的 CustomLineCapDataFlags 字段中设置了 CustomLineCapDataFillPath 标志，则此字段必须存在。

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


获取或设置可选的 EmfPlusFillPath 对象（第 2.2.2.17 节），指定用于填充自定义图形线帽的路径。如果在 EmfPlusCustomLineCapData 对象的 CustomLineCapDataFlags 字段中设置了 CustomLineCapDataFillPath 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


获取或设置可选的 EmfPlusLinePath 对象（第 2.2.2.26 节），指定用于描绘自定义图形线帽的路径。如果在 EmfPlusCustomLineCapData 对象的 CustomLineCapDataFlags 字段中设置了 CustomLineCapDataLinePath 标志，则此字段必须存在。

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


获取或设置可选的 EmfPlusLinePath 对象（第 2.2.2.26 节），指定用于描绘自定义图形线帽的路径。如果在 EmfPlusCustomLineCapData 对象的 CustomLineCapDataFlags 字段中设置了 CustomLineCapDataLinePath 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |


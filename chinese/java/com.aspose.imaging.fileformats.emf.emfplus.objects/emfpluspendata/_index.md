---
title: "EmfPlusPenData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusPenData 对象指定图形笔的属性。"
type: docs
weight: 64
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

EmfPlusPenData 对象指定图形笔的属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [getPenUnit()](#getPenUnit--) | 获取或设置一个 32 位无符号整数，指定笔的测量单位。 |
| [setPenUnit(int value)](#setPenUnit-int-) | 获取或设置一个 32 位无符号整数，指定笔的测量单位。 |
| [getPenWidth()](#getPenWidth--) | 获取或设置一个 32 位浮点值，指定笔在 PenUnit 字段指定的单位下绘制的线宽。 |
| [setPenWidth(float value)](#setPenWidth-float-) | 获取或设置一个 32 位浮点值，指定笔在 PenUnit 字段指定的单位下绘制的线宽。 |
| [getOptionalData()](#getOptionalData--) | 获取或设置可选的 EmfPlusPenOptionalData 对象（第 2.2.2.34 节），用于指定笔对象的附加数据。 |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | 获取或设置可选的 EmfPlusPenOptionalData 对象（第 2.2.2.34 节），用于指定笔对象的附加数据。 |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。该值必须由 PenData 标志组成（第 2.1.2.7 节）。

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。该值必须由 PenData 标志组成（第 2.1.2.7 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


获取或设置一个 32 位无符号整数，指定笔的测量单位。该值必须来自 UnitType 枚举（第 2.1.1.33 节）。

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


获取或设置一个 32 位无符号整数，指定笔的测量单位。该值必须来自 UnitType 枚举（第 2.1.1.33 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


获取或设置一个 32 位浮点值，指定笔在 PenUnit 字段指定的单位下绘制的线宽。如果指定宽度为零，则使用最小值，该最小值由单位决定。

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


获取或设置一个 32 位浮点值，指定笔在 PenUnit 字段指定的单位下绘制的线宽。如果指定宽度为零，则使用最小值，该最小值由单位决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


获取或设置可选的 EmfPlusPenOptionalData 对象（第 2.2.2.34 节），用于指定笔对象的附加数据。该字段的具体内容由 PenDataFlags 字段的值决定。

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


获取或设置可选的 EmfPlusPenOptionalData 对象（第 2.2.2.34 节），用于指定笔对象的附加数据。该字段的具体内容由 PenDataFlags 字段的值决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |


---
title: "EmfBlendFunction"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定源位图和目标位图混合操作的结构。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

指定源位图和目标位图混合操作的结构。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | 初始化 `EmfBlendFunction` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | 获取混合操作码。 |
| [getBlendFlags()](#getBlendFlags--) | 获取混合标志。 |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | 获取一个 8 位无符号整数，指定 alpha 透明度，该透明度决定源位图和目标位图的混合方式。 |
| [getAlphaFormat()](#getAlphaFormat--) | 获取一个结构，指定在 alpha 透明度方面源像素和目标像素的解释方式。 |
| [toInt()](#toInt--) | 将数字的字符串表示转换为整数。 |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


初始化 `EmfBlendFunction` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dwordData | int | dword 数据。 |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


获取混合操作码。唯一已定义的源和目标混合操作是 0x00，它指定必须根据源像素的 alpha 透明度值将源位图与目标位图合并。详细信息请参见以下公式。

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


获取混合标志。此值必须为 0x00，且必须被忽略。

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


获取一个 8 位无符号整数，指定 alpha 透明度，该透明度决定源位图和目标位图的混合方式。此值必须用于整个源位图。最小的 alpha 透明度值 0 表示完全透明，最大值 0xFF 表示完全不透明。实际上，0xFF 的值表示每像素的 alpha 值决定源位图和目标位图的混合。详细信息请参见本节后面的公式。

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


获取一个结构，指定在 alpha 透明度方面源像素和目标像素的解释方式。

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


将数字的字符串表示转换为整数。

**Returns:**
int - 结构的 DWORD 值。
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean

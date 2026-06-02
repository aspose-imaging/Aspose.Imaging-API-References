---
title: "EmfDesignVector"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "DesignVector 第 2.2.3 节对象定义了设计向量，该向量指定了多主字体的字体轴的值。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

DesignVector（第 2.2.3 节）对象定义了设计向量，该向量指定了多母版字体的字体轴值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSignature()](#getSignature--) | 获取或设置一个 32 位无符号整数，必须设置为值 0x08007664。 |
| [setSignature(int value)](#setSignature-int-) | 获取或设置一个 32 位无符号整数，必须设置为值 0x08007664。 |
| [getNumAxes()](#getNumAxes--) | 获取或设置一个 32 位无符号整数，指定 Values 数组中的元素数量。 |
| [setNumAxes(int value)](#setNumAxes-int-) | 获取或设置一个 32 位无符号整数，指定 Values 数组中的元素数量。 |
| [getValues()](#getValues--) | 获取或设置一个可选的 32 位有符号整数数组，指定多主 OpenType 字体的字体轴值。 |
| [setValues(int[] value)](#setValues-int---) | 获取或设置一个可选的 32 位有符号整数数组，指定多主 OpenType 字体的字体轴值。 |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


获取或设置一个 32 位无符号整数，必须设置为值 0x08007664。

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


获取或设置一个 32 位无符号整数，必须设置为值 0x08007664。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


获取或设置一个 32 位无符号整数，指定 Values 数组中的元素数量。它必须在 0 到 16（含）范围内。

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


获取或设置一个 32 位无符号整数，指定 Values 数组中的元素数量。它必须在 0 到 16（含）范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


获取或设置一个可选的 32 位有符号整数数组，指定多主 OpenType 字体的字体轴值。数组中值的最大数量为 16。

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


获取或设置一个可选的 32 位有符号整数数组，指定多主 OpenType 字体的字体轴值。数组中值的最大数量为 16。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |


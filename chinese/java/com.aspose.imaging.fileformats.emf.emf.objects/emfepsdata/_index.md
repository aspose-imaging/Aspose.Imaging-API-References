---
title: "EmfEpsData"
second_title: "Aspose.Imaging for Java API 参考"
description: "EpsData 对象是 EPS 数据的容器"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

EpsData 对象是 EPS 数据的容器
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSizeData()](#getSizeData--) | 获取或设置一个 32 位无符号整数，指定此对象的总大小（以字节计）。 |
| [setSizeData(int value)](#setSizeData-int-) | 获取或设置一个 32 位无符号整数，指定此对象的总大小（以字节计）。 |
| [getVersion()](#getVersion--) | 获取或设置一个 32 位无符号整数，指定 PostScript 语言级别。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置一个 32 位无符号整数，指定 PostScript 语言级别。 |
| [getPoints()](#getPoints--) | 获取或设置一个包含三个 Point28\_4 对象（第 2.2.23 节）的数组，使用 28.4 位 FIX 表示法定义输出平行四边形的坐标。 |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | 获取或设置一个包含三个 Point28\_4 对象（第 2.2.23 节）的数组，使用 28.4 位 FIX 表示法定义输出平行四边形的坐标。 |
| [getPostScriptData()](#getPostScriptData--) | 获取或设置一个 PostScript 数据的字节数组。 |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | 获取或设置一个 PostScript 数据的字节数组。 |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


获取或设置一个 32 位无符号整数，指定此对象的总大小（以字节计）。

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


获取或设置一个 32 位无符号整数，指定此对象的总大小（以字节计）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置一个 32 位无符号整数，指定 PostScript 语言级别。该值必须为 0x00000001。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置一个 32 位无符号整数，指定 PostScript 语言级别。该值必须为 0x00000001。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


获取或设置一个包含三个 Point28\_4 对象（第 2.2.23 节）的数组，使用 28.4 位 FIX 表示法定义输出平行四边形的坐标。

平行四边形的左上角是此数组中的第一个点，右上角是第二个点，左下角是第三个点。平行四边形的右下角通过将前三个点（A、B 和 C）视为向量进行计算得到。

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


获取或设置一个包含三个 Point28\_4 对象（第 2.2.23 节）的数组，使用 28.4 位 FIX 表示法定义输出平行四边形的坐标。

平行四边形的左上角是此数组中的第一个点，右上角是第二个点，左下角是第三个点。平行四边形的右下角通过将前三个点（A、B 和 C）视为向量进行计算得到。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


获取或设置一个 PostScript 数据的字节数组。此数组的长度可以从 SizeData 字段计算得到。此数据可能用于渲染图像。

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


获取或设置一个 PostScript 数据的字节数组。此数组的长度可以从 SizeData 字段计算得到。此数据可能用于渲染图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |


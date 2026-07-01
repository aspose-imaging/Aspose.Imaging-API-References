---
title: "EmfCreateColorSpaceW"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CREATECOLORSPACEW 记录从具有 Unicode 字符名称的颜色配置文件创建逻辑颜色空间对象。"
type: docs
weight: 37
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

该 EMR\_CREATECOLORSPACEW 记录从名称由 Unicode 字符组成的色彩配置文件创建逻辑颜色空间对象。

此记录定义的逻辑颜色空间对象可以通过 EMR\\_SETCOLORSPACE 记录（第 2.3.8.7 节）选入回放设备上下文，该记录定义后续图形操作中使用的逻辑颜色空间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreateColorSpaceW` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhCS()](#getIhCS--) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。 |
| [setIhCS(int value)](#setIhCS-int-) | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。 |
| [getLcs()](#getLcs--) | 获取或设置一个 WMF LogColorSpaceW 对象（[MS-WMF] 第 2.2.2.12 节），该对象可以使用 Unicode UTF16-LE 字符指定颜色配置文件的名称。 |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | 获取或设置一个 WMF LogColorSpaceW 对象（[MS-WMF] 第 2.2.2.12 节），该对象可以使用 Unicode UTF16-LE 字符指定颜色配置文件的名称。 |
| [getDwFlags()](#getDwFlags--) | 获取或设置一个 32 位无符号整数，提供有关此记录中数据的信息。 |
| [setDwFlags(int value)](#setDwFlags-int-) | 获取或设置一个 32 位无符号整数，提供有关此记录中数据的信息。 |
| [getCbData()](#getCbData--) | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。 |
| [setCbData(int value)](#setCbData-int-) | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。 |
| [getData()](#getData--) | 获取或设置一个可选的字节数组，指定颜色配置文件数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置一个可选的字节数组，指定颜色配置文件数据。 |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


初始化 `EmfCreateColorSpaceW` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。此索引 MUST 被保存，以便可以重新使用或修改该对象。

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑颜色空间对象的索引。此索引 MUST 被保存，以便可以重新使用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


获取或设置一个 WMF LogColorSpaceW 对象（[MS-WMF] 第 2.2.2.12 节），该对象可以使用 Unicode UTF16-LE 字符指定颜色配置文件的名称。

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


获取或设置一个 WMF LogColorSpaceW 对象（[MS-WMF] 第 2.2.2.12 节），该对象可以使用 Unicode UTF16-LE 字符指定颜色配置文件的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


获取或设置一个 32 位无符号整数，提供有关此记录中数据的信息。

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


获取或设置一个 32 位无符号整数，提供有关此记录中数据的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置一个可选的字节数组，指定颜色配置文件数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置一个可选的字节数组，指定颜色配置文件数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |


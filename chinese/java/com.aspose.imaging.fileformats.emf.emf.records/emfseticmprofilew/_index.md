---
title: "EmfSetIcmProfileW"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETICMPROFILEW 记录指定一个颜色配置文件，该文件的名称由用于图形输出的 Unicode 字符组成。"
type: docs
weight: 127
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

EMR\_SETICMPROFILEW 记录指定用于图形输出的、文件名由 Unicode 字符组成的颜色配置文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetIcmProfileW` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | 获取或设置包含颜色配置文件标志的 32 位无符号整数。 |
| [setDwFlags(int value)](#setDwFlags-int-) | 获取或设置包含颜色配置文件标志的 32 位无符号整数。 |
| [getCbName()](#getCbName--) | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。 |
| [setCbName(int value)](#setCbName-int-) | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。 |
| [getCbData()](#getCbData--) | 获取或设置一个 32 位无符号整数，用于指定颜色配置文件数据的大小（如果已附加）。 |
| [setCbData(int value)](#setCbData-int-) | 获取或设置一个 32 位无符号整数，用于指定颜色配置文件数据的大小（如果已附加）。 |
| [getData()](#getData--) | 获取或设置一个大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置一个大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [getName()](#getName--) | 获取名称 |
| [getRawData()](#getRawData--) | 获取原始数据 |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


初始化 `EmfSetIcmProfileW` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


获取或设置包含颜色配置文件标志的 32 位无符号整数。

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


获取或设置包含颜色配置文件标志的 32 位无符号整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


获取或设置一个 32 位无符号整数，用于指定颜色配置文件数据的大小（如果已附加）。

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


获取或设置一个 32 位无符号整数，用于指定颜色配置文件数据的大小（如果已附加）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置一个大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 UTF16-LE 名称和原始数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置一个大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 UTF16-LE 名称和原始数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


获取名称

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


获取原始数据

**Returns:**
byte[]

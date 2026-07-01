---
title: "EmfSetIcmProfileA"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETICMPROFILEA 记录指定了一个颜色配置文件，该文件的名称由用于图形输出的 ASCII 字符组成。"
type: docs
weight: 126
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

该 EMR\_SETICMPROFILEA 记录指定用于图形输出的、文件名由 ASCII 字符组成的颜色配置文件。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetIcmProfileA` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | 获取或设置包含颜色配置文件标志的 32 位无符号整数。 |
| [setDwFlags(int value)](#setDwFlags-int-) | 获取或设置包含颜色配置文件标志的 32 位无符号整数。 |
| [getCbName()](#getCbName--) | 获取或设置指定所需颜色配置文件的 ASCII 名称字节数的 32 位无符号整数。 |
| [setCbName(int value)](#setCbName-int-) | 获取或设置指定所需颜色配置文件的 ASCII 名称字节数的 32 位无符号整数。 |
| [getCbData()](#getCbData--) | 获取或设置指定颜色配置文件数据大小（如果它包含在 Data 字段中）的 32 位无符号整数。 |
| [setCbData(int value)](#setCbData-int-) | 获取或设置指定颜色配置文件数据大小（如果它包含在 Data 字段中）的 32 位无符号整数。 |
| [getData()](#getData--) | 获取或设置大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 ASCII 名称和原始数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 ASCII 名称和原始数据。 |
| [getName()](#getName--) | 获取名称 |
| [getRawData()](#getRawData--) | 获取原始数据 |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


初始化 `EmfSetIcmProfileA` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

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
| 值 | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


获取或设置指定所需颜色配置文件的 ASCII 名称字节数的 32 位无符号整数。

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


获取或设置指定所需颜色配置文件的 ASCII 名称字节数的 32 位无符号整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


获取或设置指定颜色配置文件数据大小（如果它包含在 Data 字段中）的 32 位无符号整数。

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


获取或设置指定颜色配置文件数据大小（如果它包含在 Data 字段中）的 32 位无符号整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 ASCII 名称和原始数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置大小为 (cbName + cbData) 字节的数组，用于指定所需颜色配置文件的 ASCII 名称和原始数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

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

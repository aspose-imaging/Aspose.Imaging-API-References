---
title: "EmfColorMatchToTargetW"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_COLORMATCHTOTargetW 记录指定是否使用文件名为 Unicode 字符的文件中指定的颜色配置文件进行颜色匹配。"
type: docs
weight: 24
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

EMR\_COLORMATCHTOTargetW 记录指定是否使用文件名为 Unicode 字符的颜色配置文件执行颜色匹配。

EMR\_COLORMATCHTOTargetW 记录可用于控制是否在回放设备上下文中应用当前颜色变换。如果 dwAction 值为 CS\_ENABLE，则启用颜色映射，并且应将当前颜色变换应用于后续图形操作。如果 dwAction 设置为 CS\_DISABLE，则不应应用颜色变换。当 dwAction 为 CS\_ENABLE 时启用对目标的颜色映射，但对颜色空间或色域映射的更改不会被应用。然而，当对目标的颜色映射被禁用时，这些更改必须生效。除非已经使用 EMR\_SETICMMODE 记录（第 2.3.11.14 节）启用了颜色管理，否则不应将 dwAction 字段设置为 CS\_DELETE\_TRANSFORM。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfColorMatchToTargetW` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDwAction()](#getDwAction--) | 获取或设置一个 32 位无符号整数，指定来自 ColorSpace 枚举的值（第 2.1.7 节）。 |
| [setDwAction(int value)](#setDwAction-int-) | 获取或设置一个 32 位无符号整数，指定来自 ColorSpace 枚举的值（第 2.1.7 节）。 |
| [getDwFlags()](#getDwFlags--) | 获取或设置一个 32 位无符号整数，指定来自 ColorMatchToTarget 枚举的值（第 2.1.6 节）。 |
| [setDwFlags(int value)](#setDwFlags-int-) | 获取或设置一个 32 位无符号整数，指定来自 ColorMatchToTarget 枚举的值（第 2.1.6 节）。 |
| [getCbName()](#getCbName--) | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。 |
| [setCbName(int value)](#setCbName-int-) | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。 |
| [getCbData()](#getCbData--) | 获取或设置一个 32 位无符号整数，指定目标颜色配置文件的原始数据大小（如果它包含在 Data 字段中）。 |
| [setCbData(int value)](#setCbData-int-) | 获取或设置一个 32 位无符号整数，指定目标颜色配置文件的原始数据大小（如果它包含在 Data 字段中）。 |
| [getData()](#getData--) | 获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [setData(byte[] value)](#setData-byte---) | 获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [getName()](#getName--) | 获取名称 |
| [getRawData()](#getRawData--) | 获取原始数据 |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


初始化 `EmfColorMatchToTargetW` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


获取或设置一个 32 位无符号整数，指定来自 ColorSpace 枚举的值（第 2.1.7 节）。

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


获取或设置一个 32 位无符号整数，指定来自 ColorSpace 枚举的值（第 2.1.7 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


获取或设置一个 32 位无符号整数，指定来自 ColorMatchToTarget 枚举的值（第 2.1.6 节）。

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


获取或设置一个 32 位无符号整数，指定来自 ColorMatchToTarget 枚举的值（第 2.1.6 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

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
| 值 | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


获取或设置一个 32 位无符号整数，指定目标颜色配置文件的原始数据大小（如果它包含在 Data 字段中）。

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


获取或设置一个 32 位无符号整数，指定目标颜色配置文件的原始数据大小（如果它包含在 Data 字段中）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。

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

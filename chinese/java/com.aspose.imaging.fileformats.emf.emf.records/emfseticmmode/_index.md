---
title: "EmfSetIcmMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETICMMODE 记录指定用于图形操作的图像颜色管理 ICM 模式。"
type: docs
weight: 125
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

该 EMR\_SETICMMODE 记录指定用于图形操作的图像颜色管理 (ICM) 模式。

当启用 ICM 模式时，EMF 记录中指定的颜色应进行颜色匹配，而在执行位块传输时应使用回放设备上下文中的默认颜色配置文件。如果不希望使用默认颜色配置文件，应在执行位块传输之前关闭 ICM 模式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetIcmMode` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | 获取或设置一个 32 位无符号整数，用于指定是否启用或禁用 ICM，来自 ICMMode 枚举（第 2.1.18 节）。 |
| [setIcmMode(int value)](#setIcmMode-int-) | 获取或设置一个 32 位无符号整数，用于指定是否启用或禁用 ICM，来自 ICMMode 枚举（第 2.1.18 节）。 |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


初始化 `EmfSetIcmMode` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


获取或设置一个 32 位无符号整数，用于指定是否启用或禁用 ICM，来自 ICMMode 枚举（第 2.1.18 节）。该值是回放设备上下文状态的一部分。

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


获取或设置一个 32 位无符号整数，用于指定是否启用或禁用 ICM，来自 ICMMode 枚举（第 2.1.18 节）。该值是回放设备上下文状态的一部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |


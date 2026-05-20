---
title: "EmfForceUfiMapping"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_FORCEUFIMAPPING 记录强制字体映射器根据其 UniversalFontId（而不是其 LogFont 第 2.2.13 节信息）来匹配字体。"
type: docs
weight: 61
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfForceUfiMapping extends EmfStateRecordType
```

EMR_FORCEUFIMAPPING 记录强制字体映射器优先根据其 UniversalFontId 而非 LogFont（第 2.2.13 节）信息来匹配字体。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfForceUfiMapping(EmfRecord source)](#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfForceUfiMapping` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUfi()](#getUfi--) | 获取或设置要使用的字体 ID，指定为 UniversalFontId（第 2.2.27 节）。 |
| [setUfi(EmfUniversalFontId value)](#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-) | 获取或设置要使用的字体 ID，指定为 UniversalFontId（第 2.2.27 节）。 |
### EmfForceUfiMapping(EmfRecord source) {#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfForceUfiMapping(EmfRecord source)
```


初始化 `EmfForceUfiMapping` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getUfi() {#getUfi--}
```
public EmfUniversalFontId getUfi()
```


获取或设置要使用的字体 ID，指定为 UniversalFontId（第 2.2.27 节）。

**Returns:**
[EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid)
### setUfi(EmfUniversalFontId value) {#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-}
```
public void setUfi(EmfUniversalFontId value)
```


获取或设置要使用的字体 ID，指定为 UniversalFontId（第 2.2.27 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid) |  |


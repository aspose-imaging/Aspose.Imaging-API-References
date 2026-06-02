---
title: "类 EmfSetIcmMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmMode 类。EMR_SETICMMODE 记录指定图形操作的图像颜色管理（ICM）模式。"
type: docs
weight: 4460
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
## EmfSetIcmMode class

该 EMR_SETICMMODE 记录指定图形操作的图像颜色管理 (ICM) 模式。

```csharp
public sealed class EmfSetIcmMode : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetIcmMode](emfseticmmode/)(EmfRecord) | 初始化 `EmfSetIcmMode` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IcmMode](../../aspose.imaging.fileformats.emf.emf.records/emfseticmmode/icmmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定是否启用或禁用 ICM，取值自 ICMMode 枚举（第 2.1.18 节）。该值是播放设备上下文状态的一部分。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

当启用 ICM 模式时，EMF 记录中指定的颜色应进行颜色匹配，而在执行位块传输时应使用播放设备上下文中的默认颜色配置文件。如果不希望使用默认颜色配置文件，则应在执行位块传输之前关闭 ICM 模式。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)



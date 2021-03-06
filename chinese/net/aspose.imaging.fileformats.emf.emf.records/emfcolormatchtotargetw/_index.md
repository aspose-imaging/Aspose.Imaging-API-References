---
title: EmfColorMatchToTargetW
second_title: Aspose.Imaging for .NET API 参考
description: EMR_COLORMATCHTOTargetW 记录指定是否使用在名称由 Unicode 字符组成的文件中指定的颜色 配置文件执行颜色匹配
type: docs
weight: 3330
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
## EmfColorMatchToTargetW class

EMR_COLORMATCHTOTargetW 记录指定是否使用在名称由 Unicode 字符组成的文件中指定的颜色 配置文件执行颜色匹配。

```csharp
public sealed class EmfColorMatchToTargetW : EmfStateRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfColorMatchToTargetW](emfcolormatchtotargetw)(EmfRecord) | 初始化[`EmfColorMatchToTargetW`](../emfcolormatchtotargetw)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbdata) { get; set; } | 获取或设置一个 32 位无符号整数，它指定目标 颜色配置文件的原始数据的大小，如果它包含在数据字段。 |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbname) { get; set; } | 获取或设置一个 32 位无符号整数，它指定所需颜色配置文件的 Unicode UTF16-LE 名称中的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/data) { get; set; } | 获取或设置大小为 (cbName + cbData) 的数组（以字节为单位），它指定所需的 UTF16-LE 名称和原始数据颜色配置文件。 |
| [DwAction](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwaction) { get; set; } | 获取或设置一个 32 位无符号整数，该整数指定 ColorSpace 枚举中的值（第 2.1.7 节）。 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwflags) { get; set; } | 获取或设置一个 32 位无符号整数，该整数指定 ColorMatchToTarget 枚举中的值（第 2.1.6 节）。 |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/name) { get; } | 获取名称 |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/rawdata) { get; } | 获取原始数据 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 评论

EMR_COLORMATCHTOTargetW 记录可用于控制是否应用当前 播放设备上下文中的颜色变换。如果 dwAction 值为 CS_ENABLE，则启用颜色 映射，并且当前颜色变换应该应用于后续图形 操作。如果 dwAction 设置为 CS_DISABLE，颜色变换不应该是 应用的。 虽然到目标的颜色映射由 CS_ENABLE 的 dwAction 值启用，但不会应用对 颜色空间或色域映射的更改。但是，当颜色映射到目标被禁用时，这些更改必须生效 。 dwAction 字段不应设置为 CS_DELETE_TRANSFORM，除非颜色管理 已经使用 EMR_SETICMMODE 记录启用（第 2.3.11.14 节）。

### 也可以看看

* class [EmfStateRecordType](../emfstaterecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

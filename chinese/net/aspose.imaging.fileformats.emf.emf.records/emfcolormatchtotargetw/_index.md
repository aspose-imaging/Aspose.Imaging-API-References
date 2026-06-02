---
title: "类 EmfColorMatchToTargetW"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfColorMatchToTargetW 类。EMR_COLORMATCHTOTargetW 记录指定是否使用文件名由 Unicode 字符组成的文件中指定的颜色配置文件进行颜色匹配。"
type: docs
weight: 3430
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
## EmfColorMatchToTargetW class

EMR_COLORMATCHTOTargetW 记录指定是否使用文件名为 Unicode 字符的颜色配置文件进行颜色匹配。

```csharp
public sealed class EmfColorMatchToTargetW : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfColorMatchToTargetW](emfcolormatchtotargetw/)(EmfRecord) | 初始化 `EmfColorMatchToTargetW` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbdata/) { get; set; } | 获取或设置一个 32 位无符号整数，指定目标颜色配置文件的原始数据大小（如果它包含在 Data 字段中）。 |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/cbname/) { get; set; } | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/data/) { get; set; } | 获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [DwAction](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwaction/) { get; set; } | 获取或设置一个 32 位无符号整数，指定来自 ColorSpace 枚举的值（第 2.1.7 节）。 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/dwflags/) { get; set; } | 获取或设置一个 32 位无符号整数，指定来自 ColorMatchToTarget 枚举的值（第 2.1.6 节）。 |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/name/) { get; } | 获取名称 |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/rawdata/) { get; } | 获取原始数据 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

EMR_COLORMATCHTOTargetW 记录可用于控制是否在回放设备上下文中应用当前颜色变换。如果 dwAction 值为 CS_ENABLE，则启用颜色映射，当前颜色变换应应用于后续图形操作。如果 dwAction 设置为 CS_DISABLE，则不应应用颜色变换。当通过 dwAction 值 CS_ENABLE 启用目标颜色映射时，颜色空间或色域映射的更改不会被应用。然而，当目标颜色映射被禁用时，这些更改必须生效。除非已使用 EMR_SETICMMODE 记录（第 2.3.11.14 节）启用颜色管理，否则 dwAction 字段不应设置为 CS_DELETE_TRANSFORM。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)



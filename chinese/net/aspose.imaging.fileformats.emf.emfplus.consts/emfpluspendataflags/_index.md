---
title: EmfPlusPenDataFlags
second_title: Aspose.Imaging for .NET API 参考
description: PenData 标志指定图形笔的属性包括可选数据字段的存在这些标志可以组合起来指定多个选项
type: docs
weight: 5000
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
## EmfPlusPenDataFlags enumeration

PenData 标志指定图形笔的属性，包括可选数据字段的存在。这些标志可以组合起来指定多个选项。

```csharp
[Flags]
public enum EmfPlusPenDataFlags
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| PenDataTransform | `1` | 如果设置，则必须在Objects的OptionalData字段中指定2x3变换矩阵。EmfPlusPenData对象。 |
| PenDataStartCap | `2` | 如果设置，必须在EmfPlusPenData对象。 |
| PenDataEndCap | `4` | 指示是否必须在EmfPlusPenData对象。 |
| PenDataJoin | `8` | 指示是否必须在EmfPlusPenData的OptionalData字段中指定线连接类型目的。 |
| PenDataMiterLimit | `10` | 指示是否必须在EmfPlusPenData的OptionalData字段中指定斜接限制目的。 |
| PenDataLineStyle | `20` | 指示是否必须在EmfPlusPenData的OptionalData字段中指定线型目的。 |
| PenDataDashedLineCap | `40` | 指示是否必须在EmfPlusPenData的OptionalData字段中指定虚线帽目的。 |
| PenDataDashedLineOffset | `80` | 指示是否必须在EmfPlusPenData的OptionalData字段中指定虚线偏移目的。 |
| PenDataDashedLine | `100` | 指示是否必须在 OptionalData 字段中指定[`EmfPlusDashedLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)对象一个[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata)对象。 |
| PenDataNonCenter | `200` | 指示是否必须在EmfPlusPenData的OptionalData字段中指定笔对齐目的。 |
| PenDataCompoundLine | `400` | 表示[`EmfPlusCompoundLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)对象的长度和内容是否存在于[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata)对象的 OptionalData 字段。 |
| PenDataCustomStartCap | `800` | 指示是否必须在 OptionalData 字段中指定[`EmfPlusCustomStartCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)对象一个[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata)对象。 |
| PenDataCustomEndCap | `1000` | 指示是否必须在 OptionalData 字段中指定[`EmfPlusCustomEndCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)对象一个[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata)对象。 |

### 评论

图形笔由EmfPlusPen对象。

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
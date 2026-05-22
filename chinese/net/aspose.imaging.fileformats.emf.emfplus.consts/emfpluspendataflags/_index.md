---
title: "枚举 EmfPlusPenDataFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPenDataFlags 枚举。PenData 标志指定图形画笔的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。"
type: docs
weight: 5120
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
## EmfPlusPenDataFlags enumeration

PenData 标志指定了图形笔的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。

```csharp
[Flags]
public enum EmfPlusPenDataFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PenDataTransform | `1` | 如果设置，则必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定一个 2x3 变换矩阵。 |
| PenDataStartCap | `2` | 如果设置，则必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定起始线帽的样式。 |
| PenDataEndCap | `4` | 指示是否必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定结束线帽的样式。 |
| PenDataJoin | `8` | 指示是否必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定线段连接类型。 |
| PenDataMiterLimit | `10` | 指示是否必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定斜接限制。 |
| PenDataLineStyle | `20` | 指示是否必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定线条样式。 |
| PenDataDashedLineCap | `40` | 指示是否必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定虚线线帽。 |
| PenDataDashedLineOffset | `80` | 指示是否必须在 [`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/) 对象的 OptionalData 字段中指定虚线偏移。 |
| PenDataDashedLine | `100` | 指示是否必须在[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/)对象的 OptionalData 字段中指定一个[`EmfPlusDashedLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/)对象。 |
| PenDataNonCenter | `200` | 指示是否必须在[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/)对象的 OptionalData 字段中指定笔对齐方式。 |
| PenDataCompoundLine | `400` | 指示是否在[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/)对象的 OptionalData 字段中包含[`EmfPlusCompoundLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/)对象的长度和内容。 |
| PenDataCustomStartCap | `800` | 指示是否必须在[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/)对象的 OptionalData 字段中指定一个[`EmfPlusCustomStartCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/)对象。 |
| PenDataCustomEndCap | `1000` | 指示是否必须在[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/)对象的 OptionalData 字段中指定一个[`EmfPlusCustomEndCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/)对象。 |

## 备注

图形笔由[`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen/)对象指定。

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)



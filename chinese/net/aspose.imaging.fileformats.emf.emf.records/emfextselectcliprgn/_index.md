---
title: "类 EmfExtSelectClipRgn"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtSelectClipRgn 类。EMR_EXTSELECTCLIPRGN 记录使用指定的模式将指定的区域与当前剪裁区域合并。注意，本节未描述的字段在第 2.3.2 节中指定。"
type: docs
weight: 3760
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
## EmfExtSelectClipRgn class

EMR_EXTSELECTCLIPRGN 记录使用指定模式将指定区域与当前裁剪区域合并。注意，本节未描述的字段在第 2.3.2 节中指定。

```csharp
public sealed class EmfExtSelectClipRgn : EmfClippingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfExtSelectClipRgn](emfextselectcliprgn/#constructor)() | 初始化 `EmfExtSelectClipRgn` 类的新实例。 |
| [EmfExtSelectClipRgn](emfextselectcliprgn/#constructor_1)(EmfRecord) | 初始化 `EmfExtSelectClipRgn` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [RegionMode](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/regionmode/) { get; set; } | 获取或设置一个 32 位无符号整数，指定区域的使用方式。该值必须属于 RegionMode（第 2.1.29 节）枚举。 |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndata/) { get; set; } | 获取或设置一个长度为 RgnDataSize 的字节数组，指定以逻辑单位表示的 RegionData 对象。如果 RegionMode 为 RGN_COPY，则可以省略此数据，剪裁区域应设置为默认（NULL）剪裁区域。 |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndatasize/) { get; set; } | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfClippingRecordType](../emfclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)



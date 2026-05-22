---
title: "EmfLogPenEx.StyleEntry"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfLogPenEx 属性。获取或设置一个可选的 32 位无符号整数数组，用于定义当 PenStyle 的值为 PS_USERSTYLE 时此笔绘制的线条中短划线和间隙的长度。该数组包含由 NumStyleEntries 指定的条目数，但使用时视为无限重复。数组的第一条目指定第一个短划线的长度。第二条目指定第一个间隙的长度。此后短划线和间隙的长度交替出现。如果 PenStyle 字段中的笔类型为 PS_GEOMETRIC，则长度以逻辑单位指定；否则以设备单位指定。"
type: docs
weight: 80
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/styleentry/
---
## EmfLogPenEx.StyleEntry property

获取或设置一个可选的 32 位无符号整数数组，用于定义该笔绘制的线条中短划线和间隙的长度，当 PenStyle 的值为笔的 PS_USERSTYLE 线样式时。数组包含由 NumStyleEntries 指定的条目数量，但使用时视为无限重复。数组的第一条目指定第一段短划线的长度。第二条目指定第一段间隙的长度。此后，短划线和间隙的长度交替出现。如果 PenStyle 字段中的笔类型为 PS_GEOMETRIC，则长度以逻辑单位指定；否则，以设备单位指定。

```csharp
public int[] StyleEntry { get; set; }
```

### 另请参见

* class [EmfLogPenEx](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../emflogpenex/)
* assembly [Aspose.Imaging](../../../)



---
title: "类 EmfPlusClear"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusClear 类。EmfPlusClear 记录清除输出坐标空间并使用背景颜色和透明度进行初始化。"
type: docs
weight: 5980
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
## EmfPlusClear class

EmfPlusClear 记录清除输出坐标空间并用背景颜色和透明度进行初始化。

```csharp
public sealed class EmfPlusClear : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusClear](emfplusclear/)(EmfPlusRecord) | 初始化 `EmfPlusClear` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32Color](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/argb32color/) { get; set; } | 获取或设置颜色。一个 EmfPlusARGB 对象（第 2.2.2.1 节），定义用于绘制屏幕的颜色。所有颜色均以 [IEC-RGB] 指定，除非另有说明。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)



---
title: "类 EmfSetRop2"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetRop2 类。EMR_SETROP2 记录定义二进制光栅操作模式。"
type: docs
weight: 4590
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
## EmfSetRop2 class

EMR_SETROP2 记录定义二进制光栅操作模式。

```csharp
public sealed class EmfSetRop2 : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetRop2](emfsetrop2/#constructor)() | 初始化 `EmfSetRop2` 类的新实例。 |
| [EmfSetRop2](emfsetrop2/#constructor_1)(EmfRecord) | 初始化 `EmfSetRop2` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Rop2Mode](../../aspose.imaging.fileformats.emf.emf.records/emfsetrop2/rop2mode/) { get; set; } | 获取或设置一个 32 位无符号整数，用于指定光栅操作模式，且必须属于 WMF 二进制光栅操作枚举（[MS-WMF] 第 2.1.1.2 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

二进制光栅操作混合模式定义了在使用当前笔进行绘制时如何组合源颜色和目标颜色。混合模式是二进制光栅操作码，表示两个变量的所有可能布尔函数，使用二进制操作 AND、OR 和 XOR（异或），以及一元操作 NOT。混合模式仅适用于光栅设备；在矢量设备上不可用。

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)



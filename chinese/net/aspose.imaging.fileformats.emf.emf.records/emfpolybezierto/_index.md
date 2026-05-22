---
title: "类 EmfPolyBezierTo"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyBezierTo 类。EMR_POLYBEZIERTO 记录基于当前位置信息指定一个或多个贝塞尔曲线。"
type: docs
weight: 4080
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/
---
## EmfPolyBezierTo class

EMR_POLYBEZIERTO 记录指定基于当前位置信息的一个或多个贝塞尔曲线。

```csharp
public sealed class EmfPolyBezierTo : EmfPolyShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPolyBezierTo](emfpolybezierto/#constructor)() | 初始化 `EmfPolyBezierTo` 类的新实例。 |
| [EmfPolyBezierTo](emfpolybezierto/#constructor_1)(EmfRecord) | 初始化 `EmfPolyBezierTo` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | 获取或设置 WMF PointL 对象数组（[MS-WMF] 第 2.2.2.15 节），该数组以逻辑单位指定点数据。 |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以设备单位指定边界矩形。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

## 备注

立方贝塞尔曲线使用 aPoints 字段指定的端点和控制点定义。第一条曲线从第一个点绘制到第四个点，使用第二和第三个点作为控制点。序列中的每条后续曲线恰好需要另外三个点：前一条曲线的结束点用作起始点，接下来的两个点为控制点，第三个点为结束点。立方贝塞尔曲线 SHOULD 使用当前笔绘制。

### 另请参见

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)



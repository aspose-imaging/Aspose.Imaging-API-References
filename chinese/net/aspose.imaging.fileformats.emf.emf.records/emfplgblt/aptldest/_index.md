---
title: "EmfPlgBlt.AptlDest"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlgBlt 属性。获取或设置一个包含三个 WMF PointL 对象的数组（MSWMF 第 2.2.2.15 节），指定块传输的平行四边形目标区域的三个角。源矩形的左上角映射到此数组的第一个点，右上角映射到第二个点，左下角映射到第三个点。源矩形的右下角映射到平行四边形中隐含的第四点，该点由前面三个点 A、B、C 视为向量计算得到。D  B  C A"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest/
---
## EmfPlgBlt.AptlDest property

获取或设置一个包含三个 WMF PointL 对象的数组（[MS-WMF] 第 2.2.2.15 节），该数组指定块传输的目标平行四边形的三个角。源矩形的左上角映射到数组中的第一个点，右上角映射到第二个点，左下角映射到第三个点。源矩形的右下角映射到平行四边形中隐含的第四点，该点通过将前三个点（A、B 和 C）视为向量计算得到。D = B + C A

```csharp
public Point[] AptlDest { get; set; }
```

### 另请参见

* struct [Point](../../../aspose.imaging/point/)
* class [EmfPlgBlt](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfplgblt/)
* assembly [Aspose.Imaging](../../../)



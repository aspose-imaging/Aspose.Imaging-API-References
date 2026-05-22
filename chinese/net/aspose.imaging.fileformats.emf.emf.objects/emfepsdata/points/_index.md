---
title: "EmfEpsData.Points"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfEpsData 属性。获取或设置一个包含三个 Point28_4 对象（第 2.2.23 节）的数组，这些对象使用 28.4 位 FIX 表示法定义输出平行四边形的坐标"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/points/
---
## EmfEpsData.Points property

获取或设置一个包含三个 Point28_4 对象（第 2.2.23 节）的数组，使用 28.4 位 FIX 表示法定义输出平行四边形的坐标。

```csharp
public EmfPoint28To4[] Points { get; set; }
```

## 备注

平行四边形的左上角是此数组中的第一个点，右上角是第二个点，左下角是第三个点。平行四边形的右下角通过将前三个点（A、B 和 C）视为向量进行计算得出。

### 另请参见

* class [EmfPoint28To4](../../emfpoint28to4/)
* class [EmfEpsData](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../emfepsdata/)
* assembly [Aspose.Imaging](../../../)



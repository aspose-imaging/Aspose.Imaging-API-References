---
title: "RasterImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。对图像进行伽马校正。"
type: docs
weight: 200
url: /zh/net/aspose.imaging/rasterimage/adjustgamma/
---
## AdjustGamma(float, float, float) {#adjustgamma_1}

图像的伽马校正。

```csharp
public virtual void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | 单精度 | 红色通道的伽马系数 |
| gammaGreen | 单精度 | 绿色通道的伽马系数 |
| gammaBlue | 单精度 | 蓝色通道的伽马系数 |

## 示例

以下示例对图像执行伽马校正，针对颜色分量应用不同的系数。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 为红、绿、蓝通道设置各自的伽马系数。
    rasterImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float) {#adjustgamma}

图像的伽马校正。

```csharp
public virtual void AdjustGamma(float gamma)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gamma | 单精度 | 红、绿、蓝通道的伽马系数 |

## 示例

以下示例对图像执行伽马校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 设置红、绿、蓝通道的伽马系数。
    rasterImage.AdjustGamma(2.5f);
    rasterImage.Save(dir + "sample.AdjustGamma.png");
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)



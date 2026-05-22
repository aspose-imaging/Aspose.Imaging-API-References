---
title: "RasterImage.AnalyzePercentageDigitalSignature"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。计算提取数据与原始密码之间的相似度百分比"
type: docs
weight: 210
url: /zh/net/aspose.imaging/rasterimage/analyzepercentagedigitalsignature/
---
## RasterImage.AnalyzePercentageDigitalSignature method

计算提取数据与原始密码之间的相似度百分比。

```csharp
public virtual int AnalyzePercentageDigitalSignature(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于提取嵌入数据的密码。 |

### 返回值

相似度百分比值。

## 示例

示例说明如何确定图像包含使用指定密码创建的数字签名的概率（0% 到 100%）。

```csharp
[C#]

using (var image = Image.Load(outputPath))
{
    var signedPercentage = image.AnalyzePercentageDigitalSignature(password);
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)



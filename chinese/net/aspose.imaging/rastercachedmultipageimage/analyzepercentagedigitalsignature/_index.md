---
title: "RasterCachedMultipageImage.AnalyzePercentageDigitalSignature"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedMultipageImage 方法。计算提取数据与原始密码之间的相似度百分比"
type: docs
weight: 160
url: /zh/net/aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/
---
## RasterCachedMultipageImage.AnalyzePercentageDigitalSignature method

计算提取数据与原始密码之间的相似度百分比。

```csharp
public override int AnalyzePercentageDigitalSignature(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于提取嵌入数据的密码。 |

### 返回值

相似度百分比值。

### 异常

| 异常 | 条件 |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | 在任何处理问题时抛出。 |

## 备注

由于多页图像，结果表示计算得到的 `MIDDLE AVERAGED signing percentage`

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

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



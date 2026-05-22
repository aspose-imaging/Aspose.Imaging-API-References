---
title: "RasterCachedMultipageImage.IsDigitalSigned"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedMultipageImage 方法。使用提供的密码和阈值快速检查图像是否已数字签名"
type: docs
weight: 280
url: /zh/net/aspose.imaging/rastercachedmultipageimage/isdigitalsigned/
---
## RasterCachedMultipageImage.IsDigitalSigned method

快速检查图像是否已数字签名，使用提供的密码和阈值。

```csharp
public override bool IsDigitalSigned(string password, int percentageThreshold = -1)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于检查签名的密码。 |
| percentageThreshold | Int32 | 阈值（百分比）[0-100] 用于确定图像是否被视为已签名。如果未指定，将使用默认阈值（`75`）。 |

### 返回值

如果图像已签名则为 true，否则为 false。

## 备注

此方法通过利用 !:GetSignPercentage 提供最快的检测。一旦提取的数据达到指定阈值，后续旨在提高检测准确性的提取步骤将被跳过。

仅当多页图像中的所有页都被识别为已签名时，结果才为 `true`；否则，图像被视为未签名。

## 示例

示例演示如何验证嵌入的数字签名是否与提供的密码匹配，并符合指定的概率阈值。

```csharp
[C#]

var threshold = 100;
using (var image = Image.Load(outputPath))
{
    var isSigned = image.IsDigitalSigned(password, threshold);
}
```

### 另请参见

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



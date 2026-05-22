---
title: "RasterCachedMultipageImage.EmbedDigitalSignature"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedMultipageImage 方法。根据提供的密码将数字签名嵌入图像的每一页"
type: docs
weight: 240
url: /zh/net/aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/
---
## RasterCachedMultipageImage.EmbedDigitalSignature method

根据提供的密码将数字签名嵌入图像的每一页。

```csharp
public override void EmbedDigitalSignature(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于生成数字签名数据的密码 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | 在任何处理问题时抛出。 |

## 示例

示例展示了如何根据提供的密码将数字签名嵌入图像像素数据中。

```csharp
[C#]

var imageFilePath = "ball.png";
var password = "veryStr0ngPassword";
using (var image = Image.Load(imageFilePath))
{
    image.EmbedDigitalSignature(password);
    image.Save(outputPath);
}
```

### 另请参见

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



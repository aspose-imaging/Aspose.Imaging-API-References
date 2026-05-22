---
title: "RasterImage.EmbedDigitalSignature"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage method. 根据提供的密码使用隐写技术将数字签名嵌入图像中"
type: docs
weight: 290
url: /zh/net/aspose.imaging/rasterimage/embeddigitalsignature/
---
## RasterImage.EmbedDigitalSignature method

使用隐写技术将基于提供的密码的数字签名嵌入图像中。

```csharp
public virtual void EmbedDigitalSignature(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于生成数字签名数据的密码 |

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

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)



---
title: "SvgResourceKeeperCallback.OnImageResourceReady"
second_title: "Aspose.Imaging for .NET API 参考"
description: "SvgResourceKeeperCallback 方法。当图像资源准备好导出时调用"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/onimageresourceready/
---
## SvgResourceKeeperCallback.OnImageResourceReady method

当图像资源准备导出时调用。

```csharp
public virtual string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
    string suggestedFileName, ref bool useEmbeddedImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | Byte[] | 资源数据。 |
| imageType | SvgImageType | 图像的类型。 |
| suggestedFileName | String | 建议文件的名称。 |
| useEmbeddedImage | Boolean& | 如果设置为 `true`，必须使用嵌入式图像。 |

### 返回值

返回已保存资源的路径。路径应相对于目标 SVG 文档。

### 另请参见

* enum [SvgImageType](../../svgimagetype/)
* class [SvgResourceKeeperCallback](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgresourcekeepercallback/)
* assembly [Aspose.Imaging](../../../)



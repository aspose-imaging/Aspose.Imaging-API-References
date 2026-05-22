---
title: "ISvgResourceKeeperCallback.OnImageResourceReady"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ISvgResourceKeeperCallback 方法。调用时图像资源已准备好导出"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/onimageresourceready/
---
## ISvgResourceKeeperCallback.OnImageResourceReady method

当图像资源准备导出时调用。

```csharp
public string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
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
* interface [ISvgResourceKeeperCallback](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../isvgresourcekeepercallback/)
* assembly [Aspose.Imaging](../../../)



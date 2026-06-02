---
title: "SvgOptions.Compress"
second_title: "Aspose.Imaging for .NET API 参考"
description: "SvgOptions 属性。获取或设置一个值，指示是否需要压缩输出图像"
type: docs
weight: 40
url: /zh/net/aspose.imaging.imageoptions/svgoptions/compress/
---
## SvgOptions.Compress property

获取或设置一个值，指示输出图像是否必须压缩。

```csharp
public bool Compress { get; set; }
```

### Property Value

`true` 表示已压缩；否则为 `false`。

## 示例

以下示例展示了如何将 svg 图像转换为 svgz 格式

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### 另请参见

* class [SvgOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgoptions/)
* assembly [Aspose.Imaging](../../../)



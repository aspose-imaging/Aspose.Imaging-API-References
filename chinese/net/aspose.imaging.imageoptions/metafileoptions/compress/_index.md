---
title: "MetafileOptions.Compress"
second_title: "Aspose.Imaging for .NET API 参考"
description: "MetafileOptions 属性。获取或设置指示此 ICompressedOptions 是否已压缩的值"
type: docs
weight: 20
url: /zh/net/aspose.imaging.imageoptions/metafileoptions/compress/
---
## MetafileOptions.Compress property

获取或设置一个值，指示此 ICompressedOptions 是否已压缩。

```csharp
public bool Compress { get; set; }
```

### Property Value

`true` 表示已压缩；否则为 `false`。

## 示例

以下示例展示了如何将 emf 图像转换为 emz 格式

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

以下示例展示了如何将 wmf 图像转换为 wmz 格式。

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### 另请参见

* class [MetafileOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../metafileoptions/)
* assembly [Aspose.Imaging](../../../)



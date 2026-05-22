---
title: "RasterCachedMultipageImage.PageExportingAction"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedMultipageImage 属性。获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。"
type: docs
weight: 100
url: /zh/net/aspose.imaging/rastercachedmultipageimage/pageexportingaction/
---
## RasterCachedMultipageImage.PageExportingAction property

获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。

```csharp
public virtual PageExportingAction PageExportingAction { get; set; }
```

### Property Value

页面导出操作。

## 示例

以下示例展示了在保存（导出）Tiff 图像之前进行批量转换。

```csharp
[C#]

string fileName = "10MB_Tif.tif";
    string inputFileName = fileName;

    string outputFileNameTif = "output.tif";
    
    //已实现在保存（导出）Tiff 图像之前进行批量转换的可能性。

    using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(inputFileName))
    {
        // 为页面设置批量操作
        tiffImage.PageExportingAction = delegate(int index, Image page)
        {
            // 触发垃圾回收，以避免前一页产生的不必要的垃圾存储
            GC.Collect();

            ((Aspose.Imaging.RasterImage)page).Rotate(90);
        };

        tiffImage.Save(outputFileNameTif);

        /* Attention! In batch mode all pages will be released in this line!
         If you want to further perform operations on the original image, you should reload it from the source to another instance. */
    }
```

### 另请参见

* delegate [PageExportingAction](../../pageexportingaction/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



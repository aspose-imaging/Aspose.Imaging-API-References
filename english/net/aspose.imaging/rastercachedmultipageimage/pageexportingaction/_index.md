---
title: RasterCachedMultipageImage.PageExportingAction
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedMultipageImage property. Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved
type: docs
weight: 100
url: /net/aspose.imaging/rastercachedmultipageimage/pageexportingaction/
---
## RasterCachedMultipageImage.PageExportingAction property

Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

```csharp
public virtual PageExportingAction PageExportingAction { get; set; }
```

### Property Value

The page exporting action.

## Examples

The following example shows batch conversion before saving (exporting) Tiff images.

```csharp
[C#]

string fileName = "10MB_Tif.tif";
    string inputFileName = fileName;

    string outputFileNameTif = "output.tif";
    
    //The possibility of batch conversion before saving (exporting) Tiff images is implemented.

    using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(inputFileName))
    {
        // Set batch operation for pages
        tiffImage.PageExportingAction = delegate(int index, Image page)
        {
            // Fires garbage collection to avoid unnecessary garbage storage from previous pages
            GC.Collect();

            ((Aspose.Imaging.RasterImage)page).Rotate(90);
        };

        tiffImage.Save(outputFileNameTif);

        /* Attention! In batch mode all pages will be released in this line!
         If you want to further perform operations on the original image, you should reload it from the source to another instance. */
    }
```

### See Also

* delegate [PageExportingAction](../../pageexportingaction/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



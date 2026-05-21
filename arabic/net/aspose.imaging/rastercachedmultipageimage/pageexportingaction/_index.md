---
title: "RasterCachedMultipageImage.PageExportingAction"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية RasterCachedMultipageImage. يحصل أو يضبط إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرة قبل حفظ كل صفحة"
type: docs
weight: 100
url: /ar/net/aspose.imaging/rastercachedmultipageimage/pageexportingaction/
---
## RasterCachedMultipageImage.PageExportingAction property

يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة.

```csharp
public virtual PageExportingAction PageExportingAction { get; set; }
```

### Property Value

عملية تصدير الصفحة.

## أمثلة

المثال التالي يوضح التحويل الجماعي قبل حفظ (تصدير) صور Tiff.

```csharp
[C#]

string fileName = "10MB_Tif.tif";
    string inputFileName = fileName;

    string outputFileNameTif = "output.tif";
    
    //تم تنفيذ إمكانية التحويل الجماعي قبل حفظ (تصدير) صور Tiff.

    using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(inputFileName))
    {
        // تعيين عملية جماعية للصفحات
        tiffImage.PageExportingAction = delegate(int index, Image page)
        {
            // يُطلق جمع القمامة لتجنب تخزين القمامة غير الضرورية من الصفحات السابقة
            GC.Collect();

            ((Aspose.Imaging.RasterImage)page).Rotate(90);
        };

        tiffImage.Save(outputFileNameTif);

        /* Attention! In batch mode all pages will be released in this line!
         If you want to further perform operations on the original image, you should reload it from the source to another instance. */
    }
```

### انظر أيضًا

* delegate [PageExportingAction](../../pageexportingaction/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



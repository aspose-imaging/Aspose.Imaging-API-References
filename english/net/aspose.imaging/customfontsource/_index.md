---
title: Delegate CustomFontSource
second_title: Aspose.Imaging for .NET API Reference
description: Custom font source provider function
type: docs
weight: 760
url: /net/aspose.imaging/customfontsource/
---
## CustomFontSource delegate

Custom font source provider function

```csharp
public delegate CustomFontData[] CustomFontSource(params object[] args);
```

| Parameter | Type | Description |
| --- | --- | --- |
| args | Object[] | The arguments. |

### Return Value

The list of specific fonts to render the image

## Examples

This example demonstrates the custom font source providing to use the specific font(s) for image rendering. Unlike FontSettings.SetFontsFolders method works in the image scope and allowing to provide the fonts in multi-user scenarios.

```csharp
[C#]

public void CustomFontSourceTest(string inputPath, string outputPath, string fileName, string fontPath)
{
    var loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.AddCustomFontSource(GetFontSource, fontPath);
    using (var img = Image.Load(System.IO.Path.Combine(inputPath, fileName), loadOptions))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions =
            (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)img.GetDefaultOptions(new object[] { Color.White, img.Width, img.Height });
        vectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        vectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;

        img.Save(System.IO.Path.Combine(outputPath, fileName + ".png"), new Aspose.Imaging.ImageOptions.PngOptions
        {
            VectorRasterizationOptions = vectorRasterizationOptions
        });
    }
}

// The custom fonts provider example. 
private Aspose.Imaging.CustomFontHandler.CustomFontData[] GetFontSource(params object[] args)
{
    string fontsPath = string.Empty;
    if (args.Length > 0)
    {
        fontsPath = args[0].ToString();
    }

    var customFontData = new System.Collections.Generic.List<Aspose.Imaging.CustomFontHandler.CustomFontData>();
    foreach (var font in System.IO.Directory.GetFiles(fontsPath))
    {
        customFontData.Add(new Aspose.Imaging.CustomFontHandler.CustomFontData(Path.GetFileNameWithoutExtension(font), System.IO.File.ReadAllBytes(font)));
    }

    return customFontData.ToArray();
}
```

### See Also

* class [CustomFontData](../../aspose.imaging.customfonthandler/customfontdata/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)



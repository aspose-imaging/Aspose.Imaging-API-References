---
title: CustomFontSource
second_title: Aspose.Imaging for Java API Reference
description: Custom font source provider interface
type: docs
weight: 122
url: /java/com.aspose.imaging/customfontsource/
---```
public interface CustomFontSource
```

Custom font source provider interface
## Methods

| Method | Description |
| --- | --- |
| [get(Object[] args)](#get-java.lang.Object...-) | Custom font source provider method |

## Example: This example demonstrates the custom font source providing to use the specific font(s) for image rendering.
This example demonstrates the custom font source providing to use the specific font(s) for image rendering. Unlike FontSettings.setFontsFolders method works in the image scope and allowing to provide the fonts in multi-user scenarios.
``` java
            
import com.aspose.imaging.Color;
import com.aspose.imaging.Image;
import com.aspose.imaging.customfonthandler.CustomFontData;

import java.io.File;
import java.io.IOException;
import java.nio.file.Files;
import java.util.LinkedList;
import java.util.List;
            
public void customFontSourceTest(String inputPath, String outputPath, String fileName, String fontPath)
{
    com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
    loadOptions.addCustomFontSource((args) -> getFontSource(args), fontPath);
    try (Image img = Image.load(inputPath + fileName, loadOptions))
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions =
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions)img.getDefaultOptions(new Object[] { Color.getWhite(), img.getWidth(), img.getHeight() });
        vectorRasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        vectorRasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);

        img.save(outputPath + fileName + ".png", new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}

// The custom fonts provider example. 
private CustomFontData[] getFontSource(Object ... args)
{
    String fontsPath = "";
    if (args.length > 0)
    {
        fontsPath = args[0].toString();
    }

    List<CustomFontData> customFontData = new LinkedList<>();
    final File[] files = new File(fontsPath).listFiles();
    if (files != null)
    {
        for (File font : files)
        {
            try
            {
                customFontData.add(new CustomFontData(getFileNameWithoutExtension(font), Files.readAllBytes(font.toPath())));
            }
            catch (IOException ignored)
            {
                // Hide it
            }
        }
    }

    return customFontData.toArray(new CustomFontData[0]);
}

private String getFileNameWithoutExtension(File file)
{
    String path = file.getName();
    int p = path.lastIndexOf('.');

    return p < 0 ? path : path.substring(0, p);
}
```

### get(Object[] args) {#get-java.lang.Object...-}
```
public abstract CustomFontData[] get(Object[] args)
```


Custom font source provider method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
com.aspose.imaging.customfonthandler.CustomFontData[] - The array of specific fonts to render the image

---
title: WmfRasterizationOptions
second_title: Aspose.Imaging for Java API Reference
description: The Wmf rasterization options.
type: docs
weight: 55
url: /java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

The Wmf rasterization options.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Initializes a new instance of the `WmfRasterizationOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Gets or sets the WMF render mode. |
| [setRenderMode(int value)](#setRenderMode-int-) | Gets or sets the WMF render mode. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copies this to `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Initializes a new instance of the `WmfRasterizationOptions` class.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Gets or sets the WMF render mode.

Value: The WMF render mode.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Gets or sets the WMF render mode.

Value: The WMF render mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text will be converted to shapes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // The page size.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copies this to `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |


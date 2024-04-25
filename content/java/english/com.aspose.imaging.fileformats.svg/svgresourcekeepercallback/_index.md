---
title: SvgResourceKeeperCallback
second_title: Aspose.Imaging for Java API Reference
description: The resource keeper callback
type: docs
weight: 12
url: /com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

The resource keeper callback
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Methods

| Method | Description |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Called when the image resource is ready for export. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Called when the font resource is ready for export. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Called when the SVG document is ready for export. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Called when the image resource is ready for export.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageData | byte[] | The resource data. |
| imageType | int | Type of the image. |
| suggestedFileName | java.lang.String | Name of the suggested file. |
| useEmbeddedImage | boolean[] | if set to `true` the embedded image must be used. |

**Returns:**
java.lang.String - Returns the path to the saved resource. Path should be relative to target SVG document.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Called when the font resource is ready for export.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | The font storing options. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Called when the SVG document is ready for export.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlData | byte[] | The SVG data. |
| suggestedFileName | java.lang.String | Name of the suggested file. |

**Returns:**
java.lang.String - Returns the path to the saved SVG document.

---
title: IColorConverter
second_title: Aspose.Imaging for Java API Reference
description: The color converter.
type: docs
weight: 126
url: /com.aspose.imaging/icolorconverter/
---```
public interface IColorConverter
```

The color converter.
## Methods

| Method | Description |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.imaging.PixelDataFormat-byte---int-int-int-int-com.aspose.imaging.PixelDataFormat-byte---int-) | Converts the passed data to the output format. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.imaging.PixelDataFormat-byte---int-int-int-int-com.aspose.imaging.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Converts the passed data to the output format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The source format. |
| data | byte[] | The source data. |
| offset | int | The offset in bytes where data copying should begin. |
| bitStart | int | The bit start. Note this value is not byte aligned value instead this is actual bit where copying should begin. |
| samplesCount | int | The samples count. |
| linesCount | int | The lines count. |
| destFormat | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The destination format. |
| outputData | byte[] | The output data. |
| outputOffset | int | The output offset where data copying should start. |

**Returns:**
int - The converted bytes count.

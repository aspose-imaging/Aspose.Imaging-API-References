---
title: IColorConverter.Convert
second_title: Aspose.Imaging for .NET API Reference
description: IColorConverter method. Converts the passed data to the output format
type: docs
weight: 10
url: /net/aspose.imaging/icolorconverter/convert/
---
## IColorConverter.Convert method

Converts the passed data to the output format.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | The source format. |
| data | Byte[] | The source data. |
| offset | Int32 | The offset in bytes where data copying should begin. |
| bitStart | Int32 | The bit start. Note this value is not byte aligned value instead this is actual bit where copying should begin. |
| samplesCount | Int32 | The samples count. |
| linesCount | Int32 | The lines count. |
| destFormat | PixelDataFormat | The destination format. |
| outputData | Byte[] | The output data. |
| outputOffset | Int32 | The output offset where data copying should start. |

### Return Value

The converted bytes count.

### See Also

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.Imaging](../../icolorconverter/)
* assembly [Aspose.Imaging](../../../)



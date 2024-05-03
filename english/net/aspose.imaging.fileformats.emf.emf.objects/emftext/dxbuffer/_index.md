---
title: EmfText.DxBuffer
second_title: Aspose.Imaging for .NET API Reference
description: EmfText property. Gets or sets the optional character spacing buffer UndefinedSpace2 variable An optional number of unused bytes. The OutputDx field is not required to follow immediately the preceding portion of this structure. OutputDx variable An array of 32bit unsigned integers that specify the output spacing between the origins of adjacent character cells in logical units. The location of this field is specified by the value of offDx in bytes from the start of this record. If spacing is defined this field contains the same number of values as characters in the output string. If the Options field of the EmrText object contains the ETO_PDY flag then this buffer contains twice as many values as there are characters in the output string one horizontal and one vertical offset for each in that order. If ETO_RTLREADING is specified characters are laid right to left instead of left to right. No other options affect the interpretation of this field
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.emf.emf.objects/emftext/dxbuffer/
---
## EmfText.DxBuffer property

Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. The OutputDx field is not required to follow immediately the preceding portion of this structure. OutputDx (variable): An array of 32-bit unsigned integers that specify the output spacing between the origins of adjacent character cells in logical units. The location of this field is specified by the value of offDx in bytes from the start of this record. If spacing is defined, this field contains the same number of values as characters in the output string. If the Options field of the EmrText object contains the ETO_PDY flag, then this buffer contains twice as many values as there are characters in the output string, one horizontal and one vertical offset for each, in that order. If ETO_RTLREADING is specified, characters are laid right to left instead of left to right. No other options affect the interpretation of this field.

```csharp
public int[] DxBuffer { get; set; }
```

### See Also

* class [EmfText](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../emftext/)
* assembly [Aspose.Imaging](../../../)



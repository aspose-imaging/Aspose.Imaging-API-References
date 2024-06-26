---
title: ColorPalette.IsCompactPalette
second_title: Aspose.Imaging for .NET API Reference
description: ColorPalette property. Gets or sets a value indicating whether compact palette is used
type: docs
weight: 60
url: /net/aspose.imaging/colorpalette/iscompactpalette/
---
## ColorPalette.IsCompactPalette property

Gets or sets a value indicating whether compact palette is used.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` if compact palette is used; otherwise, `false`.

## Remarks

Compact palette means that image will contain only the specified palette entries if possible or in other words the image will be more compact and occupy less space; otherwise there will be 2^BitsPerPixel entries and image will reserve more space for all possible palette entries. Setting this value to true and changing palette entries may cause performance penalty since data movement may occur so use it carefully.

### See Also

* class [ColorPalette](../)
* namespace [Aspose.Imaging](../../colorpalette/)
* assembly [Aspose.Imaging](../../../)



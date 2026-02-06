---
title: Class EmfPlusLanguageIdentifier
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLanguageIdentifier class. The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural language in a locale including countries geographical regions and administrative districts. Each language identifier is an encoding of a primary language value and sublanguage value
type: docs
weight: 5650
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
## EmfPlusLanguageIdentifier class

The EmfPlusLanguageIdentifier object specifies a language identifier that corresponds to the natural language in a locale, including countries, geographical regions, and administrative districts. Each language identifier is an encoding of a primary language value and sublanguage value.

```csharp
public sealed class EmfPlusLanguageIdentifier : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusLanguageIdentifier](emfpluslanguageidentifier/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Value](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/value/) { get; set; } | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId&#x7C; PrimaryLanguageId &#x7C; SubLanguageId (6 bits): The country, geographic region or administrative district for the natural language specified in the PrimaryLanguageId field. Sublanguage identifiers are vendor-extensible. Vendor-defined sublanguage identifiers MUST be in the range 0x20 to 0x3F, inclusive. PrimaryLanguageId (10 bits): The natural language. Primary language identifiers are vendor-extensible. Vendor-defined primary language identifiers MUST be in the range 0x0200 to 0x03FF, inclusive. |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)



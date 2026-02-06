---
title: Class EmfDesignVector
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfDesignVector class. The DesignVector section 2.2.3 object defines the design vector which specifies values for the font axes of a multiple master font
type: docs
weight: 3030
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
## EmfDesignVector class

The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

```csharp
public sealed class EmfDesignVector : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDesignVector](emfdesignvector/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [NumAxes](../../aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/numaxes/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of elements in the Values array. It MUST be in the range 0 to 16, inclusive |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/signature/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST be set to the value 0x08007664. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/values/) { get; set; } | Gets or sets an optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. The maximum number of values in the array is 16. |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)



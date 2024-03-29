---
title: MetafileData
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in data med variabel längd som specificerar den inbäddade metafilen. Innehållet och dataformatet kan vara olika för varje metafiltyp.
type: docs
weight: 20
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/metafiledata/
---
## EmfPlusMetafile.MetafileData property

Hämtar eller ställer in data med variabel längd som specificerar den inbäddade metafilen. Innehållet och dataformatet kan vara olika för varje metafiltyp.

```csharp
public byte[] MetafileData { get; set; }
```

### Anmärkningar

Grafikbilder specificeras av EmfPlusImage-objekt (avsnitt 2.2.1.4). Ett EmfPlusMetafile-objekt MÅSTE finnas i ImageData-fältet för ett EmfPlusImage-objekt om ImageTypeMetafile anges i dess Type-fält. Detta objekt är generiskt och används för olika typer av data, inklusive: En WMF-metafil [MS-WMF]; WMF-metafil som kan placeras; En EMF-metafil [MS-EMF]; En EMF+-metafil som specificerar grafikoperationer med endast EMF+-poster; and En EMF+-metafil som specificerar grafikoperationer med både EMF+- och EMF-poster. Se avsnitt 2.2.2 för specifikation av ytterligare strukturobjekt.

### Se även

* class [EmfPlusMetafile](../../emfplusmetafile)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusmetafile)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

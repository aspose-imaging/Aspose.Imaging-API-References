---
title: CanLoad
second_title: Aspose.Imaging für .NET-API-Referenz
description: Legt fest ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und verwendet optional dieloadOptions .
type: docs
weight: 10
url: /de/net/aspose.imaging/iimageloaderdescriptor/canload/
---
## IImageLoaderDescriptor.CanLoad method

Legt fest, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann, und verwendet optional die*loadOptions* .

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | StreamContainer | Der Stream-Container. |
| loadOptions | LoadOptions | Die von angegebenen Dateiformatdetails*loadOptions* . Das*loadOptions* kann null sein. |

### Rückgabewert

`Stimmt` wenn der von diesem Deskriptor erstellte Bildlader das Bild aus dem Stream lesen kann; Andernfalls,`FALSCH` .

### Siehe auch

* class [StreamContainer](../../streamcontainer)
* class [LoadOptions](../../loadoptions)
* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor)
* namensraum [Aspose.Imaging](../../iimageloaderdescriptor)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
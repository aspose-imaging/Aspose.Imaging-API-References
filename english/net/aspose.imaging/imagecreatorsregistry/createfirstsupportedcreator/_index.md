---
title: ImageCreatorsRegistry.CreateFirstSupportedCreator
second_title: Aspose.Imaging for .NET API Reference
description: ImageCreatorsRegistry method. Creates the first found creator suitable for the specified
type: docs
weight: 30
url: /net/aspose.imaging/imagecreatorsregistry/createfirstsupportedcreator/
---
## ImageCreatorsRegistry.CreateFirstSupportedCreator method

Creates the first found creator suitable for the specified.

```csharp
public static IImageCreator CreateFirstSupportedCreator(ImageOptionsBase imageOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | The image options. |

### Return Value

The creator which supports the specified or null if no such creator is found.

## Remarks

The first creator will be actually the last registered.

### See Also

* interface [IImageCreator](../../iimagecreator/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageCreatorsRegistry](../)
* namespace [Aspose.Imaging](../../imagecreatorsregistry/)
* assembly [Aspose.Imaging](../../../)



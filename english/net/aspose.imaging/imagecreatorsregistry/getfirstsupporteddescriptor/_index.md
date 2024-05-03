---
title: ImageCreatorsRegistry.GetFirstSupportedDescriptor
second_title: Aspose.Imaging for .NET API Reference
description: ImageCreatorsRegistry method. Gets the fist found supported descriptor suitable for the specified
type: docs
weight: 40
url: /net/aspose.imaging/imagecreatorsregistry/getfirstsupporteddescriptor/
---
## ImageCreatorsRegistry.GetFirstSupportedDescriptor method

Gets the fist found supported descriptor suitable for the specified.

```csharp
public static IImageCreatorDescriptor GetFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | The image options. |

### Return Value

The creator descriptor which supports the specified or null if no such descriptor is found.

## Remarks

The first creator descriptor will be actually the last registered.

### See Also

* interface [IImageCreatorDescriptor](../../iimagecreatordescriptor/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageCreatorsRegistry](../)
* namespace [Aspose.Imaging](../../imagecreatorsregistry/)
* assembly [Aspose.Imaging](../../../)



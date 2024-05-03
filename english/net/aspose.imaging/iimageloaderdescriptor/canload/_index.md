---
title: IImageLoaderDescriptor.CanLoad
second_title: Aspose.Imaging for .NET API Reference
description: IImageLoaderDescriptor method. Determines whether image loader can read a new image from the specified stream and optionally using the loadOptions
type: docs
weight: 10
url: /net/aspose.imaging/iimageloaderdescriptor/canload/
---
## IImageLoaderDescriptor.CanLoad method

Determines whether image loader can read a new image from the specified stream and optionally using the *loadOptions*.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | StreamContainer | The stream container. |
| loadOptions | LoadOptions | The file format details specified by *loadOptions*. The *loadOptions* may be null. |

### Return Value

`true` if image loader created by this descriptor can read image from stream; otherwise, `false`.

### See Also

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.Imaging](../../iimageloaderdescriptor/)
* assembly [Aspose.Imaging](../../../)



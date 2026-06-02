---
title: "接口 IImageCreatorDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.IImageCreatorDescriptor 接口。图像创建器描述符，指定创建器属性。使用创建器描述符可以避免在内存中保留每个图像创建器实例以及多线程问题。"
type: docs
weight: 9660
url: /zh/net/aspose.imaging/iimagecreatordescriptor/
---
## IImageCreatorDescriptor interface

指定创建器属性的图像创建器描述符。使用创建器描述符可以避免在内存中保留每个图像创建器实例以及多线程问题。

```csharp
public interface IImageCreatorDescriptor : IImageDescriptor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CanCreate](../../aspose.imaging/iimagecreatordescriptor/cancreate/)(ImageOptionsBase) | 确定图像创建器是否可以使用 *imageOptions* 创建新图像。 |
| [CreateInstance](../../aspose.imaging/iimagecreatordescriptor/createinstance/)() | 创建一个新的创建器实例。 |

### 另请参见

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)



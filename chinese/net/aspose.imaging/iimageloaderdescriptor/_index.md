---
title: IImageLoaderDescriptor
second_title: Aspose.Imaging for .NET API 参考
description: 指定加载器属性的图像加载器描述符加载器描述符用于克服 在内存中包含每个图像加载器实例的必要性和多线程问题
type: docs
weight: 9520
url: /zh/net/aspose.imaging/iimageloaderdescriptor/
---
## IImageLoaderDescriptor interface

指定加载器属性的图像加载器描述符。加载器描述符用于克服 在内存中包含每个图像加载器实例的必要性和多线程问题。

```csharp
public interface IImageLoaderDescriptor : IImageDescriptor
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CanLoad](../../aspose.imaging/iimageloaderdescriptor/canload)(StreamContainer, LoadOptions) | 确定图像加载器是否可以从指定的流中读取新图像，并且可以选择使用*loadOptions* . |
| [CreateInstance](../../aspose.imaging/iimageloaderdescriptor/createinstance)() | 创建一个新的加载器实例。 |

### 也可以看看

* interface [IImageDescriptor](../iimagedescriptor)
* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

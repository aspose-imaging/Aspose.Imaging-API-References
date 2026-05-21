---
title: "IImageCreatorDescriptor"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定创建器属性的图像创建器描述符。"
type: docs
weight: 129
url: /zh/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

image creator descriptor 指定创建器属性。creator descriptor 用于克服在内存中保留每个 image creator 实例以及多线程问题的必要性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | 确定 image creator 是否可以使用 `imageOptions` 创建新图像。 |
| [createInstance()](#createInstance--) | 创建新的 creator 实例。 |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


确定 image creator 是否可以使用 `imageOptions` 创建新图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | 图像选项。 |

**Returns:**
boolean - 如果由此 descriptor 创建的 image creator 能使用指定的 `imageOptions` 创建图像数据，则为 `true`；否则为 `false`。
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


创建新的 creator 实例。

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

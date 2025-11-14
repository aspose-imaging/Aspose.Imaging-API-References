---
title: IGifBlockLoaderDescriptor
second_title: Aspose.Imaging for Java API Reference
description: Gif block Loader descriptor.
type: docs
weight: 15
url: /java/com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor/
---```
public interface IGifBlockLoaderDescriptor
```

Gif block Loader descriptor.
## Methods

| Method | Description |
| --- | --- |
| [canLoad(StreamContainer streamContainer)](#canLoad-com.aspose.imaging.StreamContainer-) | Determines whether loader can load the specified data. |
| [load(StreamContainer streamContainer, IColorPalette containerPalette)](#load-com.aspose.imaging.StreamContainer-com.aspose.imaging.IColorPalette-) | Loads the gif block. |
### canLoad(StreamContainer streamContainer) {#canLoad-com.aspose.imaging.StreamContainer-}
```
public abstract boolean canLoad(StreamContainer streamContainer)
```


Determines whether loader can load the specified data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container to load data from. |

**Returns:**
boolean - `true` loader can load the specified data; otherwise, `false`.
### load(StreamContainer streamContainer, IColorPalette containerPalette) {#load-com.aspose.imaging.StreamContainer-com.aspose.imaging.IColorPalette-}
```
public abstract IGifBlock load(StreamContainer streamContainer, IColorPalette containerPalette)
```


Loads the gif block.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The container palette. |

**Returns:**
[IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) - A new gif block.

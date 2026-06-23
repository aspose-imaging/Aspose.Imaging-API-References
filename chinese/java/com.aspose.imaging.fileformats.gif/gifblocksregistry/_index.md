---
title: "GifBlocksRegistry"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 gif 块打开器注册表。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.gif/gifblocksregistry/
---
**Inheritance:**
java.lang.Object
```
public final class GifBlocksRegistry
```

表示 gif 块打开器注册表。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | 获取已注册的描述符。 |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | 根据类型名称获取第一个受支持的描述符。 |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) |  |
| [loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)](#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-) |  |
| [registerOpener(IGifBlockLoaderDescriptor openerDescriptor)](#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | 注册打开器。 |
| [unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)](#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-) | 注销打开器。 |
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IGifBlockLoaderDescriptor[] getRegisteredDescriptors()
```


获取已注册的描述符。

值：已注册的描述符。

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor[]
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


根据类型名称获取第一个受支持的描述符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | 描述符类型名称。 |

第一个打开器描述符实际上是最后注册的。 |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IGifBlockLoaderDescriptor getFirstSupportedDescriptor(InputStream stream)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream |  |

**Returns:**
[IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor)
### loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette) {#loadBlockByFirstSupportedDescriptor-java.io.InputStream-com.aspose.imaging.IColorPalette-}
```
public static IGifBlock loadBlockByFirstSupportedDescriptor(InputStream stream, IColorPalette containerPalette)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream |  |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) |  |

**Returns:**
[IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
### registerOpener(IGifBlockLoaderDescriptor openerDescriptor) {#registerOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void registerOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


注册打开器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | 要注册的打开器描述符。 |

### unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor) {#unregisterOpener-com.aspose.imaging.fileformats.gif.IGifBlockLoaderDescriptor-}
```
public static void unregisterOpener(IGifBlockLoaderDescriptor openerDescriptor)
```


注销打开器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| openerDescriptor | [IGifBlockLoaderDescriptor](../../com.aspose.imaging.fileformats.gif/igifblockloaderdescriptor) | 要注销的打开器描述符。 |


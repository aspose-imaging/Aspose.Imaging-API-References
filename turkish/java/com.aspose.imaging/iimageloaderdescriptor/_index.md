---
title: "IImageLoaderDescriptor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Yükleyici özelliklerini belirten görüntü yükleyici tanımlayıcısı."
type: docs
weight: 134
url: /tr/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Yükleyici özelliklerini belirten görüntü yükleyici tanımlayıcısı. Yükleyici tanımlayıcısı, her görüntü yükleyici örneğinin bellekte tutulması ve çok iş parçacıklı sorunların gerekliliğini aşmak için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Görüntü yükleyicinin belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak `loadOptions` kullanıp kullanmayacağını belirler. |
| [createInstance()](#createInstance--) | Yeni bir yükleyici örneği oluşturur. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Görüntü yükleyicinin belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak `loadOptions` kullanıp kullanmayacağını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | `loadOptions` tarafından belirtilen dosya formatı ayrıntıları. `loadOptions` null olabilir. |

**Returns:**
boolean - `true` eğer bu tanımlayıcı tarafından oluşturulan görüntü yükleyici akıştan görüntüyü okuyabiliyorsa; aksi takdirde `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Yeni bir yükleyici örneği oluşturur.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.

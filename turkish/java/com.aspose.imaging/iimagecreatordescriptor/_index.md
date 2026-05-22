---
title: "IImageCreatorDescriptor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Oluşturucu özelliklerini belirten görüntü oluşturucu tanımlayıcısı."
type: docs
weight: 129
url: /tr/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Oluşturucu özelliklerini belirten görüntü oluşturucu tanımlayıcısı. Oluşturucu tanımlayıcısı, her görüntü oluşturucu örneğinin bellekte tutulması ve çok iş parçacıklı sorunların gerekliliğini aşmak için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Görüntü oluşturucunun `imageOptions` kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler. |
| [createInstance()](#createInstance--) | Yeni bir oluşturucu örneği oluşturur. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Görüntü oluşturucunun `imageOptions` kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Görüntü seçenekleri. |

**Returns:**
boolean - Bu tanımlayıcı tarafından oluşturulan görüntü oluşturucu, belirtilen `imageOptions` kullanarak görüntü verisi oluşturabiliyorsa `true`; aksi takdirde `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Yeni bir oluşturucu örneği oluşturur.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

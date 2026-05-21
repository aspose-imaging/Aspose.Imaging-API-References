---
title: "IImageExporterDescriptor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü dışa aktarıcı tanımlayıcısını temsil eder."
type: docs
weight: 132
url: /tr/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Görüntü dışa aktarıcı tanımlayıcısını temsil eder. Dışa aktarıcı tanımlayıcı, her dışa aktarıcı örneğinin bellekte tutulması ve çok iş parçacıklı sorunların üstesinden gelmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Görüntü dışa aktarıcının, belirtilen görüntüyü kaydetme seçenekleriyle belirtilen görüntü formatına dışa aktarabilip aktaramadığını belirler. |
| [createInstance()](#createInstance--) | Yeni bir dışa aktarıcı örneği oluşturur. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Görüntü dışa aktarıcının, belirtilen görüntüyü kaydetme seçenekleriyle belirtilen görüntü formatına dışa aktarabilip aktaramadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dışa aktarılacak görüntü. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Seçeneklerin temeli. |

**Returns:**
boolean - bu tanımlayıcı tarafından oluşturulan dışa aktarıcı, belirtilen görüntüyü belirtilen dosya formatına dışa aktarabiliyorsa `true`; aksi takdirde `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Yeni bir dışa aktarıcı örneği oluşturur.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.

---
title: "IImageExporterDescriptor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثّل وصف مُصدّر الصورة."
type: docs
weight: 132
url: /ar/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

يمثل واصف مُصدّر الصور. يُستخدم واصف المُصدّر لتجاوز الحاجة إلى احتواء كل مثال من المُصدّر في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | يحدد ما إذا كان مُصدّر الصور يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ. |
| [createInstance()](#createInstance--) | ينشئ مثالًا جديدًا للمُصدّر. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


يحدد ما إذا كان مُصدّر الصور يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة المراد تصديرها. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | قاعدة الخيارات. |

**Returns:**
منطقي - `true` إذا كان المُصدّر الذي تم إنشاؤه بواسطة هذا الوصف يمكنه تصدير الصورة المحددة إلى تنسيق الملف المحدد؛ وإلا `false`.
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


ينشئ مثالًا جديدًا للمُصدّر.

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.

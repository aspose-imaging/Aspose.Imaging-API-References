---
title: "IImageCreatorDescriptor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "وصف منشئ الصورة الذي يحدد خصائص المنشئ."
type: docs
weight: 129
url: /ar/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

وصف منشئ الصورة الذي يحدد خصائص المنشئ. يُستخدم وصف المنشئ لتجاوز الحاجة إلى احتواء كل مثيل لمنشئ الصورة في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام `imageOptions`. |
| [createInstance()](#createInstance--) | ينشئ مثيلًا جديدًا للمنشئ. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام `imageOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الصورة. |

**Returns:**
منطقية - `true` إذا كان منشئ الصورة الذي تم إنشاؤه بواسطة هذا الوصف يمكنه إنشاء بيانات الصورة باستخدام `imageOptions` المحدد؛ وإلا `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


ينشئ مثيلًا جديدًا للمنشئ.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

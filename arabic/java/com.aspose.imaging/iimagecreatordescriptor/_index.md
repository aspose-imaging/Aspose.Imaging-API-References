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

المُعرّف الخاص بمنشئ الصورة الذي يحدد خصائص المنشئ. يُستخدم مُعرّف المنشئ لتجاوز الحاجة إلى احتواء كل مثال من منشئ الصورة في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام `imageOptions`. |
| [createInstance()](#createInstance--) | ينشئ مثال منشئ جديد. |
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
منطقي - `true` إذا كان منشئ الصورة الذي تم إنشاؤه بواسطة هذا الوصف يمكنه إنشاء بيانات الصورة باستخدام `imageOptions` المحدد؛ وإلا `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


ينشئ مثال منشئ جديد.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

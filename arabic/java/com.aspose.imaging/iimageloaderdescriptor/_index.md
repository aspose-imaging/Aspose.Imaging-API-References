---
title: "IImageLoaderDescriptor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "وصف محمل الصورة الذي يحدد خصائص المحمل."
type: docs
weight: 134
url: /ar/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

وصف محمل الصورة الذي يحدد خصائص المحمل. يُستخدم وصف المحمل لتجاوز الحاجة إلى احتواء كل مثال من محمل الصورة في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام `loadOptions` اختياريًا. |
| [createInstance()](#createInstance--) | ينشئ مثالًا جديدًا للمحمّل. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام `loadOptions` اختياريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | تفاصيل تنسيق الملف المحددة بواسطة `loadOptions`. قد يكون `loadOptions` فارغًا. |

**Returns:**
منطقي - `true` إذا كان محمل الصورة الذي أنشئ بواسطة هذا الوصف يمكنه قراءة الصورة من الدفق؛ وإلا، `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


ينشئ مثالًا جديدًا للمحمّل.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.

---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ FileCreateSource. يهيئ مثيلاً جديداً من الفئة FileCreateSource"
type: docs
weight: 10
url: /ar/net/aspose.imaging.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

يهيئ مثيلاً جديداً من الفئة [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للإنشاء. |

## أمثلة

هذا المثال ينشئ ملف صورة جديد في موقع قرص معين كما هو محدد بواسطة خاصية Source في كائن BmpOptions. إذا لم يتم تمرير المعامل الثاني إلى منشئ FileCreateSource، فسيكون الملف الذي سيتم إنشاؤه افتراضيًا لديه الخاصية IsTemporal مضبوطة على True. عندما تكون IsTemporal مضبوطة على True، لن يتم حفظ أي ملف على القرص في نهاية التنفيذ.

```csharp
[C#]

//ينشئ مثيلاً من BmpOptions ويضبط خصائصه المختلفة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//إذا لم يتم تمرير المعامل الثاني، فسيكون الملف افتراضيًا لديه IsTemporal مضبوطة على True
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp");

//ينشئ مثيلاً من Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

### انظر أيضًا

* class [FileCreateSource](../)
* namespace [Aspose.Imaging.Sources](../../filecreatesource/)
* assembly [Aspose.Imaging](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

يهيئ مثيلاً جديداً من الفئة [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للإنشاء. |
| isTemporal | Boolean | إذا تم ضبطه على `true` فإن الملف المُنشأ سيكون مؤقتًا. |

## أمثلة

هذا المثال ينشئ ملف صورة جديد في موقع على القرص كما هو محدد بواسطة خاصية Source لكائن BmpOptions. يتم تعيين عدة خصائص لكائن BmpOptions قبل إنشاء الصورة الفعلية. خاصةً خاصية Source التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

//أنشئ مثيلاً من BmpOptions وعيّن خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//إنشاء كائن من نوع Image وتهيئته بكائن BmpOptions عن طريق استدعاء طريقة Create.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* class [FileCreateSource](../)
* namespace [Aspose.Imaging.Sources](../../filecreatesource/)
* assembly [Aspose.Imaging](../../../)



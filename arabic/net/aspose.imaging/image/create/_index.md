---
title: "Image.Create"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تنشئ صورة جديدة باستخدام خيارات الإنشاء المحددة"
type: docs
weight: 10
url: /ar/net/aspose.imaging/image/create/
---
## Create(ImageOptionsBase, int, int) {#create_1}

ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | خيارات الصورة. |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

### قيمة الإرجاع

الصورة التي تم إنشاؤها حديثًا.

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(ImageOptionsBase, int, int, int[]) {#create_2}

ينشئ كائنًا من [`RasterImage`](../../rasterimage/) من مصفوفة البكسلات المقدمة. يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل. لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | الخيارات المستخدمة لإنشاء [`RasterImage`](../../rasterimage/). |
| width | Int32 | عرض [`RasterImage`](../../rasterimage/). |
| height | Int32 | ارتفاع [`RasterImage`](../../rasterimage/). |
| البكسلات | Int32[] | مصفوفة قيم البكسل المستخدمة لملء الصورة. |

### قيمة الإرجاع

[`RasterImage`](../../rasterimage/) مُعبأ ببيانات البكسل المقدمة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [ImageCreateException](../../../aspose.imaging.coreexceptions/imagecreateexception/) | يُرمى إذا لم تتطابق أبعاد الصورة مع حجم مصفوفة البكسل، أو إذا فشل إنشاء الصورة بسبب *imageOptions* المحددة، أو إذا تم استدعاء الطريقة عندما لا تكون المكتبة في وضع الترخيص. |

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(Image[]) {#create_3}

ينشئ صورة جديدة باستخدام الصور المحددة كصفحات

```csharp
public static Image Create(Image[] images)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الصور | Image[] | الصور. |

### قيمة الإرجاع

الصورة كـ IMultipageImage

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(MultipageCreateOptions) {#create}

ينشئ خيارات الإنشاء المتعددة الصفحات المحددة.

```csharp
public static Image Create(MultipageCreateOptions multipageCreateOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| multipageCreateOptions | MultipageCreateOptions | خيارات إنشاء الصفحات المتعددة. |

### قيمة الإرجاع

الصورة المتعددة الصفحات

### انظر أيضًا

* class [MultipageCreateOptions](../../../aspose.imaging.imageoptions/multipagecreateoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(string[], bool) {#create_6}

ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة.

```csharp
public static Image Create(string[] files, bool throwExceptionOnLoadError)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الملفات | String[] | الملفات. |
| throwExceptionOnLoadError | Boolean | إذا تم تعيينه إلى `true` [ارمِ استثناءً عند خطأ التحميل]. |

### قيمة الإرجاع

الصورة المتعددة الصفحات

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(string[]) {#create_5}

ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة.

```csharp
public static Image Create(string[] files)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الملفات | String[] | الملفات. |

### قيمة الإرجاع

الصورة المتعددة الصفحات

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(Image[], bool) {#create_4}

ينشئ صورة جديدة باستخدام الصور المحددة كصفحات.

```csharp
public static Image Create(Image[] images, bool disposeImages)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الصور | Image[] | الصور. |
| disposeImages | Boolean | إذا تم تعيينه إلى `true` [تخلص من الصور]. |

### قيمة الإرجاع

الصورة كـ IMultipageImage

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)



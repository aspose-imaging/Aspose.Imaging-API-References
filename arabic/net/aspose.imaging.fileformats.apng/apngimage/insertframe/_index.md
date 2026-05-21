---
title: "ApngImage.InsertFrame"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ApngImage. إدراج إطار جديد بسهولة في مجموعة الإطارات الخاصة بك في الموضع المحدد باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في التحكم الدقيق في ترتيب الإطارات في الرسوم المتحركة للصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية."
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.apng/apngimage/insertframe/
---
## InsertFrame(int) {#insertframe}

أدرج إطارًا جديدًا بسهولة في مجموعة الإطارات الخاصة بك في الموضع المحدد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون إلى تحكم دقيق في ترتيب الإطارات في رسومهم المتحركة للصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية.

```csharp
public ApngFrame InsertFrame(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | Int32 | الفهرس. |

### قيمة الإرجاع

الإطار APNG الجديد الذي تم إنشاؤه.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *index* أصغر من 0. أو *index* أكبر من [`PageCount`](../pagecount/). |

### انظر أيضًا

* class [ApngFrame](../../apngframe/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## InsertFrame(int, RasterImage) {#insertframe_1}

يدرج إطارًا جديدًا في مجموعة الإطارات الخاصة بالمستخدم عند الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

```csharp
public void InsertFrame(int index, RasterImage frameImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | Int32 | الفهرس. |
| frameImage | RasterImage | صورة الإطار. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *index* أصغر من 0. أو *index* أكبر من [`PageCount`](../pagecount/). |
| ArgumentNullException | frameImage هو null. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## InsertFrame(int, RasterImage, uint) {#insertframe_2}

يدرج إطارًا جديدًا في مجموعة الإطارات الخاصة بالمستخدم عند الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

```csharp
public void InsertFrame(int index, RasterImage frameImage, uint frameTime)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | Int32 | الفهرس. |
| frameImage | RasterImage | صورة الإطار. |
| frameTime | UInt32 | مدة الإطار، بالمللي ثانية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *index* أصغر من 0. أو *index* أكبر من [`PageCount`](../pagecount/). |
| ArgumentNullException | frameImage هو null. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)



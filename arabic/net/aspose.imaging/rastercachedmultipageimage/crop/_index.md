---
title: "RasterCachedMultipageImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedMultipageImage. قص الصورة"
type: docs
weight: 220
url: /ar/net/aspose.imaging/rastercachedmultipageimage/crop/
---
## Crop(Rectangle) {#crop}

قص الصورة.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

قص الصورة مع إزاحات.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | Int32 | الإزاحة اليسرى. |
| rightShift | Int32 | الإزاحة اليمنى. |
| topShift | Int32 | الإزاحة العلوية. |
| bottomShift | Int32 | الإزاحة السفلية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | المستطيل غير صحيح. - يجب أن يكون المستطيل أو Rectangle داخل حدود الصورة. - المستطيل |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | لا يمكن قص الصورة. فهرس الإطار: " + frameIndex أو لا يمكن قص الصورة. |

### انظر أيضًا

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)



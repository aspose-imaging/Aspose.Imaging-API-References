---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CmykColorHelper. تقوم بتحويل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة"
type: docs
weight: 140
url: /ar/net/aspose.imaging/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البكسلات | Int32[] | ألوان RGB مقدمة كقيم صحيحة 32-بت. |
| startIndex | Int32 | فهرس البداية للون RGB. |
| length | Int32 | عدد بكسلات RGB التي سيتم تحويلها. |
| rgbIccStream | Stream | دفق ملف تعريف RGB. |
| cmykIccStream | Stream | دفق ملف تعريف CMYK. |

### قيمة الإرجاع

ألوان CMYK مقدمة كمصفوفة بايت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)



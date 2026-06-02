---
title: "تعداد WmfBinaryRasterOperation"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfBinaryRasterOperation تعداد. قسم تعداد BinaryRasterOperation يسرد رموز عمليات الرستر الثنائية. رموز عمليات الرستر تحدد كيفية دمج معالجة ملف الميتا للبتات من القلم المحدد مع البتات في صورة البت المستهدفة."
type: docs
weight: 8280
url: /ar/net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
## WmfBinaryRasterOperation enumeration

قسم تعداد BinaryRasterOperation يسرد رموز عملية النقطية الثنائية. تحدد رموز عملية النقطية كيف يجمع معالجة الميتافايل البتات من القلم المحدد مع البتات في بت ماب الوجهة.

```csharp
public enum WmfBinaryRasterOperation
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Black | `1` | 0، البكسل دائمًا 0. |
| Notmergepen | `2` | DPon، البكسل هو عكس لون MERGEPEN |
| Masknotpen | `3` | DPna، البكسل هو مزيج من لون الشاشة وعكس لون القلم. |
| Notcopypen | `4` | Pn، البكسل هو عكس لون القلم. |
| Maskpennot | `5` | PDna، البكسل هو مزيج من الألوان المشتركة بين القلم وعكس الشاشة. |
| Not | `6` | Dn، البكسل هو عكس لون الشاشة. |
| Xorpen | `7` | DPx، البكسل هو مزيج من الألوان في القلم أو في الشاشة، لكن ليس في كليهما. |
| Notmaskpen | `8` | DPan، البكسل هو عكس لون MASKPEN. |
| Maskpen | `9` | DPa، البكسل هو مزيج من الألوان المشتركة بين القلم والشاشة. |
| Notxorpen | `10` | DPxn، البكسل هو عكس لون XORPEN. |
| Nop | `11` | D، البكسل يبقى دون تغيير. |
| Mergenotpen | `12` | DPno، Pixel هو مزيج من الألوان المشتركة بين الشاشة وعكس القلم. |
| Copypen | `13` | P، Pixel هو لون القلم. |
| Mergepennot | `14` | PDno، Pixel هو مزيج من لون القلم وعكس لون الشاشة. |
| Mergepen | `15` | DPo، Pixel هو مزيج من لون القلم ولون الشاشة. |
| White | `16` | 1، Pixel دائمًا يساوي 1 |

## ملاحظات

كل رمز عملية نقطية (raster-operation) يمثل عملية منطقية حيث يتم دمج قيم البكسلات في القلم المحدد وبيتماب الوجهة. فيما يلي العاملان المستخدمان في هذه العمليات. العامل معنى P القلم المحدد D بيتماب الوجهة a عملية AND البتية n عملية NOT البتية (العكس) o عملية OR البتية x عملية XOR البتية الحصرية

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)



---
title: "الفئة EmfSmallTextOut"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSmallTextOut. سجل EMR_SMALLTEXTOUT يخرج سلسلة."
type: docs
weight: 4690
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
## EmfSmallTextOut class

سجل EMR_SMALLTEXTOUT يخرج سلسلة نصية.

```csharp
public sealed class EmfSmallTextOut : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSmallTextOut](emfsmalltextout/)(EmfRecord) | يُنشئ مثيلًا جديدًا للفئة `EmfSmallTextOut`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL اختياري 128‑بت ([MS-WMF] القسم 2.2.2.19) يحدد المستطيل الحدودي بوحدات الجهاز. |
| [CChars](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/cchars/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف 16‑بت في السلسلة. السلسلة ليست منتهية بـ null. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/exscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه x. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/eyscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار تكبير النص في اتجاه y. |
| [FuOptions](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/fuoptions/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد خيارات إخراج النص المراد استخدامها. تُحدد هذه الخيارات بقيمة واحدة أو مجموعة من القيم من تعداد ExtTextOutOptions (القسم 2.1.11). |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/igraphicsmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات، من تعداد GraphicsMode (القسم 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [TextString](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/textstring/) { get; set; } | يحصل أو يعيّن سلسلة بطول متغيّر تحتوي على نص الرسم، إما بأكواد أحرف 8‑بت أو 16‑بت، وفقًا لقيمة الحقل fuOptions. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [X](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/x/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي x لمكان وضع السلسلة. |
| [Y](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/y/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد إحداثي y لمكان وضع السلسلة. |

## ملاحظات

إذا تم تعيين ETO_SMALL_CHARS في حقل fuOptions، فإن TextString يحتوي على أكواد 8‑بت للأحرف، مستمدة من البايتات المنخفضة لأكواد Unicode UTF16-LE 16‑بت، حيث يُفترض أن البايت العالي يساوي 0. إذا تم تعيين ETO_NO_RECT في حقل fuOptions، فإن حقل Bounds لا يُضمّن في السجل.

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)



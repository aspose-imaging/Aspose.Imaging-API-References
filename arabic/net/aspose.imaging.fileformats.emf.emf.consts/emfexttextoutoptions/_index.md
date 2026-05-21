---
title: "Enum EmfExtTextOutOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfExtTextOutOptions enum. تحدد تعداد ExtTextOutOptions المعلمات التي تتحكم في جوانب مختلفة من إخراج النص بواسطة سجلات EMR_SMALLTEXTOUTsection 2.3.5.37 وفي كائنات EmrText."
type: docs
weight: 2720
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
## EmfExtTextOutOptions enumeration

تعداد ExtTextOutOptions يحدد المعلمات التي تتحكم في جوانب مختلفة من إخراج النص بواسطة سجلات EMR_SMALLTEXTOUT (القسم 2.3.5.37) وفي كائنات EmrText.

```csharp
[Flags]
public enum EmfExtTextOutOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ETO_OPAQUE | `2` | هذه البت تشير إلى أنه يجب استخدام لون الخلفية الحالي لملء المستطيل |
| ETO_CLIPPED | `4` | هذه البت تشير إلى أنه يجب قص النص إلى المستطيل. |
| ETO_GLYPH_INDEX | `10` | هذه البت تشير إلى أن الرموز الخاصة بالأحرف في سلسلة نصية ناتجة هي في الواقع فهارس لأشكال الأحرف في خط TrueType. فهارس الأشكال خاصة بالخط، لذا لعرض الأحرف الصحيحة عند التشغيل، يجب أن يكون الخط المستخدم مطابقًا للخط المستخدم لإنشاء الفهارس. |
| ETO_RTLREADING | `80` | هذه البت تشير إلى أنه يجب ترتيب النص من اليمين إلى اليسار بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. يجب تطبيق ذلك فقط عندما يكون الخط المختار في سياق جهاز التشغيل إما عبريًا أو عربيًا |
| ETO_NO_RECT | `100` | هذه البت تشير إلى أن السجل لا يحدد مستطيلًا محيطًا لإخراج النص. |
| ETO_SMALL_CHARS | `200` | هذه البت تشير إلى أن الرموز الخاصة بالأحرف في سلسلة نصية ناتجة هي 8 بتات، مستمدة من البايتات المنخفضة لرموز Unicode UTF16-LE ذات 16 بت، حيث يُفترض أن البايت العالي يساوي 0. |
| ETO_NUMERICSLOCAL | `400` | هذه البت تشير إلى أنه يجب استخدام الأرقام المناسبة للمنطقة عند عرض الأعداد. |
| ETO_NUMERICSLATIN | `800` | هذه البت تشير إلى أنه يجب استخدام الأرقام الأوروبية عند عرض الأعداد. |
| ETO_IGNORELANGUAGE | `1000` | هذه البت تشير إلى أنه لا يجب تنفيذ أي معالجة خاصة بنظام التشغيل لتحديد موضع الأشكال على سلاسل من اليمين إلى اليسار؛ أي أن جميع تموضع الأشكال يجب أن يتم بواسطة سجلات الرسم والحالة في ملف الميتا. |
| ETO_PDY | `2000` | هذه البت تشير إلى أنه يجب توفير قيم إزاحة الأحرف الأفقية والعمودية. |
| ETO_REVERSE_INDEX_MAP | `10000` | هذه البت محجوزة ولا يجب استخدامها. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)



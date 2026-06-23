---
title: "EmfExtTextOutOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد ExtTextOutOptions المعلمات التي تتحكم في جوانب مختلفة من إخراج النص بواسطة سجلات EMR_SMALLTEXTOUTsection 2.3.5.37 وفي كائنات EmrText."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

تعداد ExtTextOutOptions يحدد المعلمات التي تتحكم في جوانب مختلفة من إخراج النص بواسطة سجلات EMR\_SMALLTEXTOUT (القسم 2.3.5.37) وفي كائنات EmrText.
## الحقول

| حقل | الوصف |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | تشير هذه البتة إلى أنه يجب استخدام لون الخلفية الحالي لملء المستطيل. |
| [ETO_CLIPPED](#ETO-CLIPPED) | تشير هذه البتة إلى أنه يجب قص النص إلى المستطيل. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | تشير هذه البتة إلى أن رموز الأحرف في سلسلة نصية مُخرجة هي في الواقع فهارس لأشكال الأحرف في خط TrueType. |
| [ETO_RTLREADING](#ETO-RTLREADING) | تشير هذه البتة إلى أنه يجب ترتيب النص من اليمين إلى اليسار بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. |
| [ETO_NO_RECT](#ETO-NO-RECT) | تشير هذه البتة إلى أن السجل لا يحدد مستطيلًا محيطًا لإخراج النص. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | تشير هذه البتة إلى أن رموز الأحرف في سلسلة نصية مُخرجة هي 8 بتات، مستمدة من البايتات المنخفضة لرموز Unicode UTF16-LE ذات 16 بت، حيث يُفترض أن البايت العالي يساوي 0. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | تشير هذه البتة إلى أنه يجب استخدام الأرقام المناسبة للمنطقة عند عرض الأعداد. |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | تشير هذه البتة إلى أنه يجب استخدام الأرقام الأوروبية عند عرض الأعداد. |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | تشير هذه البتة إلى أنه لا ينبغي تنفيذ أي معالجة خاصة من نظام التشغيل لتحديد موضع الأشكال في السلاسل من اليمين إلى اليسار؛ أي أن جميع تحديد موضع الأشكال يجب أن يتولى الرسم وسجلات الحالة في ملف التعريف. |
| [ETO_PDY](#ETO-PDY) | تشير هذه البت إلى أنه يجب توفير قيم إزاحة الأحرف الأفقية والعمودية |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | هذه البت محجوزة ولا يجب استخدامها |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


تشير هذه البتة إلى أنه يجب استخدام لون الخلفية الحالي لملء المستطيل.

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


تشير هذه البتة إلى أنه يجب قص النص إلى المستطيل.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


تشير هذه البت إلى أن الرموز الخاصة بالأحرف في سلسلة نصية ناتجة هي في الواقع فهارس لأشكال الأحرف في خط TrueType. فهارس الأشكال خاصة بالخط، لذا لعرض الأحرف الصحيحة أثناء التشغيل، يجب أن يكون الخط المستخدم مطابقًا للخط المستخدم لإنشاء الفهارس.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


تشير هذه البت إلى أنه يجب تنسيق النص بترتيب القراءة من اليمين إلى اليسار، بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. يجب تطبيق ذلك فقط عندما يكون الخط المحدد في سياق جهاز التشغيل إما عبريًا أو عربيًا

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


تشير هذه البتة إلى أن السجل لا يحدد مستطيلًا محيطًا لإخراج النص.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


تشير هذه البتة إلى أن رموز الأحرف في سلسلة نصية مُخرجة هي 8 بتات، مستمدة من البايتات المنخفضة لرموز Unicode UTF16-LE ذات 16 بت، حيث يُفترض أن البايت العالي يساوي 0.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


تشير هذه البتة إلى أنه يجب استخدام الأرقام المناسبة للمنطقة عند عرض الأعداد.

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


تشير هذه البتة إلى أنه يجب استخدام الأرقام الأوروبية عند عرض الأعداد.

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


تشير هذه البتة إلى أنه لا ينبغي تنفيذ أي معالجة خاصة من نظام التشغيل لتحديد موضع الأشكال في السلاسل من اليمين إلى اليسار؛ أي أن جميع تحديد موضع الأشكال يجب أن يتولى الرسم وسجلات الحالة في ملف التعريف.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


تشير هذه البت إلى أنه يجب توفير قيم إزاحة الأحرف الأفقية والعمودية

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


هذه البت محجوزة ولا يجب استخدامها


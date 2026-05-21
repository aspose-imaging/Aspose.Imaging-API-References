---
title: "EmfPlusStringFormatFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد أعلام StringFormat خيارات تخطيط النص الرسومي بما في ذلك الاتجاه والقص ومعالجة الخط."
type: docs
weight: 50
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

تحدد أعلام StringFormat خيارات تخطيط النص الرسومي، بما في ذلك الاتجاه والقص ومعالجة الخط. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | إذا تم تعيينه، يجب أن يكون ترتيب قراءة السلسلة من اليمين إلى اليسار. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | إذا تم تعيينه، يجب رسم أسطر النص الفردية عموديًا على جهاز العرض. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | إذا تم تعيينه، يجب السماح لأجزاء الأحرف بالتمدد خارج مستطيل تخطيط النص. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | إذا تم تعيينه، يجب أن تظهر الأحرف التحكمية في المخرجات كرموز يونيكود تمثيلية. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | إذا تم تعيينه، يجب استخدام خط بديل للأحرف التي لا يدعمها الخط المطلوب. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | إذا تم تعيينه، يجب تضمين المسافة في نهاية كل سطر في قياسات طول السلسلة. |
| [StringFormatNoWrap](#StringFormatNoWrap) | إذا تم تعيينه، يجب عدم لف السلسلة التي تتجاوز نهاية مستطيل تخطيط النص إلى السطر التالي. |
| [StringFormatLineLimit](#StringFormatLineLimit) | إذا تم تعيينه، يجب إخراج الأسطر الكاملة للنص ويجب عدم قصها بواسطة مستطيل تخطيط السلسلة. |
| [StringFormatNoClip](#StringFormatNoClip) | إذا تم تعيينه، يجب السماح بإظهار النص الذي يمتد خارج مستطيل تخطيط السلسلة. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | يمكن استخدام هذا العلم لتحديد عملية خاصة بالتنفيذ لتصيير النص. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


إذا تم تعيينه، يجب أن يكون ترتيب قراءة السلسلة من اليمين إلى اليسار. بالنسبة للنص الأفقي، يعني ذلك أن الأحرف تُقرأ من اليمين إلى اليسار. بالنسبة للنص العمودي، يعني ذلك أن الأعمدة تُقرأ من اليمين إلى اليسار. إذا لم يتم تعيينه، يجب قراءة النص الأفقي أو العمودي من اليسار إلى اليمين.

--------------------

يتم تحديد تخطيط النص الرسومي بواسطة كائنات [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat)

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


إذا تم تعيينه، يجب رسم أسطر النص الفردية عموديًا على جهاز العرض. إذا لم يتم تعيينه، يجب رسم أسطر النص الفردية أفقيًا، بحيث يكون كل سطر جديد أسفل السطر السابق.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


إذا تم تعيينه، يجب السماح لأجزاء الأحرف بالتمدد خارج مستطيل تخطيط النص. إذا لم يتم تعيينه، يجب إعادة تموضع الأحرف التي تتجاوز حدود مستطيل تخطيط النص لتجنب التمدد. الحرف المائل "f" مثال على حرف يمكن أن يحتوي على أجزاء متمتدة.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


إذا تم تعيينه، يجب أن تظهر الأحرف التحكمية في المخرجات كرموز يونيكود تمثيلية.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


إذا تم تعيينه، يجب استخدام خط بديل للأحرف التي لا يدعمها الخط المطلوب. إذا لم يتم تعيينه، يجب أن يظهر الحرف المفقود من الخط المطلوب كحرف "خط مفقود"، والذي قد يكون مربعًا مفتوحًا.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


إذا تم تعيينه، يجب تضمين المسافة في نهاية كل سطر في قياسات طول السلسلة. إذا لم يتم تعيينه، يجب استبعاد المسافة في نهاية كل سطر من قياسات طول السلسلة.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


إذا تم تعيينه، يجب عدم لف السلسلة التي تتجاوز نهاية مستطيل تخطيط النص إلى السطر التالي. إذا لم يتم تعيينه، يجب قطع السلسلة التي تتجاوز نهاية مستطيل تخطيط النص عند آخر حد كلمة داخل المستطيل، ويجب لف باقي السلسلة إلى السطر التالي.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


إذا تم تعيينه، يجب إخراج الأسطر الكاملة للنص ويجب عدم قصها بواسطة مستطيل تخطيط السلسلة. إذا لم يتم تعيينه، يجب أن يستمر تخطيط النص حتى يتم إخراج جميع الأسطر، أو حتى تصبح الأسطر الإضافية غير مرئية نتيجة القص. يمكن استخدام هذا العلم إما لمنع أو السماح بطمس جزء من سطر النص بواسطة مستطيل تخطيط لا يكون مضاعفًا لارتفاع السطر. لكي يكون كل النص مرئيًا، يجب أن يكون مستطيل التخطيط بطول لا يقل عن ارتفاع سطر واحد.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


إذا تم تعيينه، يجب السماح بإظهار النص الذي يمتد خارج مستطيل تخطيط السلسلة. إذا لم يتم تعيينه، يجب قص كل النص الذي يمتد خارج مستطيل التخطيط.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


يمكن استخدام هذا العلم لتحديد عملية خاصة بالتنفيذ لتصيير النص.


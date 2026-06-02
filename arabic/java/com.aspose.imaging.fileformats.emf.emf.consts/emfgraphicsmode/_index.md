---
title: "EmfGraphicsMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يتم استخدام تعداد GraphicsMode لتحديد كيفية تفسير بيانات الشكل مثل إحداثيات المستطيل."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

يتم استخدام تعداد GraphicsMode لتحديد كيفية تفسير بيانات الشكل مثل إحداثيات المستطيل.
## الحقول

| حقل | الوصف |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | يجب كتابة نص TrueType من اليسار إلى اليمين وبالوجه الصحيح، حتى إذا تم تدوير باقي الرسومات حول محور x أو محور y بسبب تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. |
| [GM_ADVANCED](#GM-ADVANCED) | يجب أن يتطابق إخراج نص TrueType تمامًا مع تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


يجب كتابة نص TrueType من اليسار إلى اليمين وبالوجه الصحيح، حتى إذا تم تدوير باقي الرسومات حول محور x أو محور y بسبب تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. يجب أن يتم تعديل ارتفاع النص فقط. يجب رسم الأقواس باستخدام اتجاه القوس الحالي في سياق جهاز التشغيل، ولكن يجب ألا تحترم تحويل العالم إلى الجهاز الحالي، الذي قد يتطلب تدويرًا حول محور x أو محور y. يجب تعديل تحويل العالم إلى الجهاز فقط عن طريق تغيير أبعاد ونقاط أصل النافذة ومنطقة العرض، باستخدام سجلات EMR\_SETWINDOWEXTEX (القسم 2.3.11.30) و EMR\_SETVIEWPORTEXTEX (القسم 2.3.11.28)، وسجلات EMR\_SETWINDOWORGEX (القسم 2.3.11.31) و EMR\_SETVIEWPORTORGEX (القسم 2.3.11.30) على التوالي. قد لا يكون تغيير التحويل مباشرةً باستخدام سجلات EMR\_MODIFYWORLDTRANSFORM (القسم 2.3.12.1) أو EMR\_SETWORLDTRANSFORM (القسم 2.3.12.2) مدعومًا. في وضع الرسومات GM\_COMPATIBLE، يجب استبعاد الحواف السفلية واليمنى عند رسم المستطيلات

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


يجب أن يتطابق إخراج نص TrueType تمامًا مع تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. يجب رسم الأقواس في اتجاه عكس عقارب الساعة في الفضاء العالمي؛ ومع ذلك، يجب أن تحترم كل من نقاط تحكم القوس والأقواس نفسها تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل بالكامل. قد يتم تعديل تحويل العالم إلى الجهاز مباشرةً باستخدام سجلات EMR\_MODIFYWORLDTRANSFORM أو EMR\_SETWORLDTRANSFORM، أو بشكل غير مباشر عن طريق تغيير أبعاد ونقاط أصل النافذة ومنطقة العرض، باستخدام سجلات EMR\_SETWINDOWEXTEX (القسم 2.3.11.30) و EMR\_SETVIEWPORTEXTEX (القسم 2.3.11.28)، وسجلات EMR\_SETWINDOWORGEX (القسم 2.3.11.31) و EMR\_SETVIEWPORTORGEX (القسم 2.3.11.30) على التوالي. في وضع الرسومات GM\_ADVANCED، يجب تضمين الحواف السفلية واليمنى عند رسم المستطيلات.


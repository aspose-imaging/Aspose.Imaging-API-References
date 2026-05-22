---
title: "EmfGraphicsMode تعداد"
type: docs
weight: 150
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

يُستخدم تعداد GraphicsMode لتحديد كيفية تفسير بيانات الشكل مثل إحداثيات المستطيل.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| GM_ADVANCED | يجب أن يتطابق إخراج نص TrueType بالكامل مع تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل.<br/>            يجب رسم الأقواس في اتجاه عكس عقارب الساعة في فضاء العالم؛ ومع ذلك، يجب أن تحترم كل من نقاط التحكم في القوس <br/>            والأقواس نفسها بالكامل تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل.<br/>            قد يتم تعديل تحويل العالم إلى الجهاز مباشرةً باستخدام سجلات EMR_MODIFYWORLDTRANSFORM أو <br/>            EMR_SETWORLDTRANSFORM، أو بشكل غير مباشر عن طريق تغيير امتدادات ونقاط أصل النافذة وعرض المنظر، <br/>            باستخدام سجلات EMR_SETWINDOWEXTEX (القسم 2.3.11.30) و EMR_SETVIEWPORTEXTEX (القسم 2.3.11.28)، <br/>            وسجلات EMR_SETWINDOWORGEX (القسم 2.3.11.31) و EMR_SETVIEWPORTORGEX (القسم 2.3.11.30) على التوالي.<br/>            في وضع الرسومات GM_ADVANCED، يجب تضمين الحواف السفلية واليمينية عند رسم المستطيلات |
| GM_COMPATIBLE | يجب كتابة نص TrueType من اليسار إلى اليمين وبالجانب الأيمن للأعلى، حتى إذا تم تدوير بقية الرسومات حول محور x أو محور y بسبب تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. يجب أن يتم تعديل ارتفاع النص فقط. يجب رسم الأقواس باستخدام اتجاه القوس الحالي في سياق جهاز التشغيل، ولكن يجب ألا تحترم تحويل العالم إلى الجهاز الحالي، والذي قد يتطلب تدويرًا حول محور x أو محور y.<br/>            يجب تعديل تحويل العالم إلى الجهاز فقط عن طريق تغيير امتدادات ونقاط أصل النافذة وعرض المنظر، باستخدام سجلات EMR_SETWINDOWEXTEX (القسم 2.3.11.30) و EMR_SETVIEWPORTEXTEX (القسم 2.3.11.28)، وسجلات EMR_SETWINDOWORGEX (القسم 2.3.11.31) و EMR_SETVIEWPORTORGEX (القسم 2.3.11.30) على التوالي. bChanging التحويل مباشرةً باستخدام سجلات EMR_MODIFYWORLDTRANSFORM (القسم 2.3.12.1) أو EMR_SETWORLDTRANSFORM (القسم 2.3.12.2) قد لا يكون مدعومًا.<br/>            في وضع الرسومات GM_COMPATIBLE، يجب استبعاد الحواف السفلية واليمينية عند رسم المستطيلات |

---
title: "Enum EmfGraphicsMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfGraphicsMode enum. تُستخدم تعداد GraphicsMode لتحديد كيفية تفسير بيانات الشكل مثل إحداثيات المستطيل"
type: docs
weight: 2770
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
## EmfGraphicsMode enumeration

تعداد GraphicsMode يُستخدم لتحديد كيفية تفسير بيانات الشكل مثل إحداثيات المستطيل.

```csharp
public enum EmfGraphicsMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| GM_COMPATIBLE | `1` | يجب كتابة نص TrueType من اليسار إلى اليمين وبالوجه الصحيح، حتى إذا تم تدوير باقي الرسومات حول محور x أو محور y بسبب تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. يجب أن يتم تعديل ارتفاع النص فقط. يجب رسم الأقواس باستخدام اتجاه القوس الحالي في سياق جهاز التشغيل، ولكن يجب ألا تحترم تحويل العالم إلى الجهاز الحالي، والذي قد يتطلب تدويرًا حول محور x أو محور y. يجب تعديل تحويل العالم إلى الجهاز فقط عن طريق تغيير امتدادات النافذة وعرض المنظر وأصولهما، باستخدام سجلات EMR_SETWINDOWEXTEX (القسم 2.3.11.30) و EMR_SETVIEWPORTEXTEX (القسم 2.3.11.28)، وسجلات EMR_SETWINDOWORGEX (القسم 2.3.11.31) و EMR_SETVIEWPORTORGEX (القسم 2.3.11.30) على التوالي. قد لا يكون تغيير التحويل مباشرةً باستخدام سجلات EMR_MODIFYWORLDTRANSFORM (القسم 2.3.12.1) أو EMR_SETWORLDTRANSFORM (القسم 2.3.12.2) مدعومًا. في وضع الرسومات GM_COMPATIBLE، يجب استبعاد الحواف السفلية واليمنى عند رسم المستطيلات. |
| GM_ADVANCED | `2` | يجب أن يتطابق إخراج نص TrueType تمامًا مع تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. يجب رسم الأقواس في اتجاه عكس عقارب الساعة في فضاء العالم؛ ومع ذلك، يجب أن تحترم كل من نقاط التحكم في القوس والأقواس نفسها تمامًا تحويل العالم إلى الجهاز الحالي في سياق جهاز التشغيل. قد يتم تعديل تحويل العالم إلى الجهاز مباشرةً باستخدام سجلات EMR_MODIFYWORLDTRANSFORM أو EMR_SETWORLDTRANSFORM، أو بشكل غير مباشر عن طريق تغيير امتدادات النافذة وعرض المنظر وأصولهما، باستخدام سجلات EMR_SETWINDOWEXTEX (القسم 2.3.11.30) و EMR_SETVIEWPORTEXTEX (القسم 2.3.11.28)، وسجلات EMR_SETWINDOWORGEX (القسم 2.3.11.31) و EMR_SETVIEWPORTORGEX (القسم 2.3.11.30) على التوالي. في وضع الرسومات GM_ADVANCED، يجب تضمين الحواف السفلية واليمنى عند رسم المستطيلات. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)



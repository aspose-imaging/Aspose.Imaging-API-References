---
title: "EmfPlusPathPointFlags Enumeration"
type: docs
weight: 290
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يعرفها هذا الكائن.<br/>            C (1 بت): إذا تم تعيينه، فإن مصفوفة PathPoints تحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت.<br/>            إذا لم يتم تعيينه، فإن مصفوفة PathPoints تحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت.<br/>            ملاحظة: إذا تم تعيين علم P (أدناه)، قد يكون هذا العلم غير مفعّل ويجب تجاهله.<br/>            R (1 بت): إذا تم تعيينه، فإن أنواع النقاط في مصفوفة PathPointTypes تُحدد بواسطة كائنات EmfPlusPathPointTypeRle (القسم 2.2.2.32)، <br/>            التي تستخدم ضغط الترميز بطول المتسلسلة (RLE)، و/أو كائنات EmfPlusPathPointType (القسم 2.2.2.31). راجع قسم [MS-WMF] 3.1.6 لمزيد من المعلومات حول ضغط RLE.<br/>            إذا لم يتم تعيينه، فإن أنواع النقاط في مصفوفة PathPointTypes تُحدد بواسطة كائنات EmfPlusPathPointType.<br/>            P (1 بت): إذا تم تعيينه، فإن كل عنصر في مصفوفة PathPoints يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى<br/>            الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PathPoints، يُفترض وجود موقع سابق عند الإحداثيات (0,0).<br/>            إذا لم يتم تعيينه، فإن كل عنصر في مصفوفة PathPoints يحدد موقعًا مطلقًا.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| C | العلم c |
| P | العلم p |
| R | العلم r |

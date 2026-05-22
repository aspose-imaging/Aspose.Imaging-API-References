---
title: "الفئة EmfUniversalFontId"
type: docs
weight: 280
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | يُنشئ نسخة جديدة من الفئة EmfUniversalFontId |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| checksum | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت هو مجموع التحقق للخط.<br/>            قيمة مجموع التحقق لها المعاني التالية.<br/>            0x00000000  الكائن هو خط جهاز. <br/>            0x00000001  الكائن هو خط Type 1 تم تثبيته على جهاز العميل وتم <br/>            تعدادُه بواسطة برنامج تشغيل طابعة PostScript كخط جهاز. <br/>            0x00000002  الكائن ليس خطًا بل هو محول نقطي Type 1. <br/>            3 ≤ القيمة   الكائن هو خط bitmap أو vector أو TrueType، أو خط Type 1 محول نقطيًا تم <br/>            إنشاؤه بواسطة محول Type 1. |
| index | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت هو فهرس مرتبط بكائن الخط. الـ<br/>            معنى هذا الحقل يُحدَّد بنوع الخط. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

يُنشئ نسخة جديدة من الفئة EmfUniversalFontId


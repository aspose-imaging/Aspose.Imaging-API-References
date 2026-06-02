---
title: "DicomImageInfo.DicomInfo"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية DicomImageInfo. تحصل على معلومات الترويسة لملف DICOM"
type: docs
weight: 50
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimageinfo/dicominfo/
---
## DicomImageInfo.DicomInfo property

تحصل على معلومات رأس ملف DICOM.

```csharp
public ReadOnlyCollection<string> DicomInfo { get; }
```

## أمثلة

المثال التالي يوضح كيفية قراءة معلومات الترويسة لصورة DICOM.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3628";
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, "ttfm.dcm")))
{
    foreach (string s in image.FileInfo.DicomInfo)
    {
        System.Console.WriteLine(s);
    }
}

// STDOUT:
//معرف فئة وسائط التخزين Sop: 1.2.840.10008.5.1.4.1.1.3.1
//معرف مثيل وسائط التخزين Sop: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//معرف صيغة النقل: 1.2.840.10008.1.2.4.70
//معرف فئة التنفيذ: 1.2.840.114236
//مجموعة الأحرف المحددة: ISO_IR 100
//نوع الصورة: \SECONDARY\INTRAOPERATIVE
//معرف فئة Sop: 1.2.840.10008.5.1.4.1.1.3.1
//معرف مثيل Sop: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//تاريخ الدراسة: 20110824
//تاريخ السلسلة: 20110824
//تاريخ المحتوى: 20110824
//وقت الدراسة: 094836.214743984
//وقت السلسلة: 094836.214743984
//وقت المحتوى: 100451.214743816
//النمط: US
//الشركة المصنعة: Medistim
//اسم المؤسسة: Hospital Name
//عنوان المؤسسة: Hospital Address or Department
//اسم المحطة: VERIQ
//اسم الطبيب المنفذ: CA Prof. Debus
//اسم طراز الشركة المصنعة: VeriQ C
//معدل الإطارات الموصى به للعرض: 1
//اسم المريض: Femoral trombenarterectomy^تقرير الحالة:
//معرف المريض: تقرير الحالة 1
//جنس المريض: M
//حجم المريض: 0
//وزن المريض: 0
//تعليقات المريض: راجع تقرير الحالة على www.medistim.com
//معدل السينما: 1
//المدة الفعالة: 1
//الرقم التسلسلي للجهاز: 0
//إصدارات البرنامج: 3.3.0 RC0 تم بناؤه 02 / 23 / 12  09:50:45
//وقت الإطار: 1000
//معرف نسخة الدراسة: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//معرف نسخة السلسلة: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//رقم السلسلة: 1
//رقم النسخة: 1
//عينات لكل بكسل: 3
//تفسير فوتومتري: RGB
//تكوين المستوى: 0
//عدد الإطارات: 1
//مؤشر زيادة الإطار:
//الصفوف: 768
//الأعمدة: 1024
//عدد البتات المخصصة: 8
//عدد البتات المخزنة: 8
//البت العالي: 7
//تمثيل البكسل: 0
//ضغط الصورة الفاقد: 00
//بيانات البكسل: 1492
```

### انظر أيضًا

* class [DicomImageInfo](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimageinfo/)
* assembly [Aspose.Imaging](../../../)



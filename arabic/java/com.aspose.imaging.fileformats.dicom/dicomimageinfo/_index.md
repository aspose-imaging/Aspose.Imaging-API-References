---
title: "DicomImageInfo"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على جميع البيانات الوصفية من رأس ملف DICOM"
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

يحتوي على جميع البيانات الوصفية من رأس ملف DICOM
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | يحصل على معلومات رأس الـ DICOM بالبايتات. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | يحصل على تكوين المستوى. |
| [getSignedImage()](#getSignedImage--) | يحصل على قيمة تشير إلى ما إذا كان "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | يحصل على معلومات الرأس لملف DICOM. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | يحصل على قيمة "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | يحصل على قيمة "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | يحصل على عدد البتات المخزنة. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | يحصل على قيمة "PhotoInterpretation". |
| [getWidth()](#getWidth--) | يحصل على العرض. |
| [getHeight()](#getHeight--) | يحصل على الارتفاع. |
| [getWindowCentre()](#getWindowCentre--) | يحصل على مركز النافذة. |
| [getWindowWidth()](#getWindowWidth--) | يحصل على عرض النافذة. |
| [getPixelRepresentation()](#getPixelRepresentation--) | يحصل على قيمة "pixelRepresentation" للبكسل. |
| [getRescaleIntercept()](#getRescaleIntercept--) | يحصل على قيمة "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | يحصل على قيمة "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | يحصل على عدد الإطارات. |
| [isLittleEndian()](#isLittleEndian--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن little endian. |
| [getReds()](#getReds--) | يحصل على مصفوفة ألوان الأحمر. |
| [getGreens()](#getGreens--) | يحصل على مصفوفة ألوان الأخضر. |
| [getBlues()](#getBlues--) | يحصل على مصفوفة ألوان الأزرق. |
| [getOffset()](#getOffset--) | يحصل على الإزاحة. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | أضف علامة Dicom جديدة. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | أضف علامة Dicom جديدة. |
| [removeTagAt(int index)](#removeTagAt-int-) | أزل علامة موجودة. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | أزل علامة موجودة. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | حدّث علامة موجودة. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | حدّث علامة موجودة. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


يحصل على معلومات رأس الـ DICOM بالبايتات.

القيمة: معلومات رأس الـ dicom بالبايتات.

**Returns:**
byte[] - معلومات رأس الـ dicom بالبايتات.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


يحصل على تكوين المستوى.

القيمة: التكوين المستوي.

**Returns:**
int - تكوين المستوى.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


يحصل على قيمة تشير إلى ما إذا كان "signedImage".

**Returns:**
boolean - قيمة تشير إلى ما إذا كان "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


يحصل على معلومات الرأس لملف DICOM.

**Returns:**
java.util.List<java.lang.String> - معلومات رأس ملف DICOM.

**Example: The following example shows how to read the header information of a DICOM image.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1489\\";
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "ttfm.dcm");
try {
    for (String s : image.getFileInfo().getDicomInfo()) {
        System.out.println(s);
    }
}
finally {
    image.close();
}

// STDOUT:
//معرف فئة تخزين الوسائط Sop: 1.2.840.10008.5.1.4.1.1.3.1
//معرف مثيل تخزين الوسائط Sop: 2.16.840.1.114488.0.4.123489834087.1330071425.2
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
//اسم المريض: Femoral trombenarterectomy^Case Report:
//معرّف المريض: تقرير الحالة 1
//جنس المريض: م
//حجم المريض: 0
//وزن المريض: 0
//تعليقات المريض: راجع تقرير الحالة على www.medistim.com
//معدل السين: 1
//المدة الفعّالة: 1
//الرقم التسلسلي للجهاز: 0
//إصدارات البرنامج: 3.3.0 RC0 تم بناءه 02 / 23 / 12  09:50:45
//وقت الإطار: 1000
//معرّف نسخة الدراسة: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//معرّف نسخة السلسلة: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//رقم السلسلة: 1
//رقم النسخة: 1
//عينات لكل بكسل: 3
//التفسير الضوئي: RGB
//تكوين المستوى: 0
//عدد الإطارات: 1
//مؤشر زيادة الإطار:
//الصفوف: 768
//الأعمدة: 1024
//البتات المخصصة: 8
//البتات المخزنة: 8
//البت العالي: 7
//تمثيل البكسل: 0
//ضغط الصورة الفاقد: 00
//بيانات البكسل: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


يحصل على قيمة "samplesPerPixel".

القيمة: قيمة "samplesPerPixel".

**Returns:**
int - قيمة "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


يحصل على قيمة "bitsAllocated".

القيمة: قيمة "bitsAllocated".

**Returns:**
int - قيمة "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


يحصل على عدد البتات المخزنة.

**Returns:**
int - عدد البتات المخزنة.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


يحصل على قيمة "PhotoInterpretation".

**Returns:**
java.lang.String - قيمة "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على العرض.

القيمة: قيمة العرض.

**Returns:**
int - العرض.
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على الارتفاع.

القيمة: قيمة الارتفاع.

**Returns:**
int - الارتفاع.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


يحصل على مركز النافذة.

القيمة: قيمة مركز النافذة.

**Returns:**
double - مركز النافذة.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


يحصل على عرض النافذة.

القيمة: عرض النافذة.

**Returns:**
double - عرض النافذة.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


يحصل على قيمة "pixelRepresentation" للبكسل.

القيمة: قيمة "pixelRepresentation".

**Returns:**
int - قيمة "pixelRepresentation" للبكسل.
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


يحصل على قيمة "rescaleIntercept".

القيمة: قيمة "rescaleIntercept".

**Returns:**
double - قيمة "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


يحصل على قيمة "rescaleSlope".

القيمة: قيمة "rescaleSlope".

**Returns:**
double - قيمة "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


يحصل على عدد الإطارات.

القيمة: عدد الإطارات.

**Returns:**
int - عدد الإطارات.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن little endian.

القيمة: `true` إذا كان هذا الكائن little endian؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا الكائن little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


يحصل على مصفوفة ألوان الأحمر.

القيمة: الأحمر.

**Returns:**
byte[] - مصفوفة ألوان الأحمر
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


يحصل على مصفوفة ألوان الأخضر.

القيمة: لون الأحمر.

**Returns:**
byte[] - مصفوفة ألوان الأخضر
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


يحصل على مصفوفة ألوان الأزرق.

القيمة: اللون الأزرق.

**Returns:**
byte[] - مصفوفة ألوان الأزرق
### getOffset() {#getOffset--}
```
public int getOffset()
```


يحصل على الإزاحة.

القيمة: قيمة الإزاحة.

**Returns:**
int - الإزاحة.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


أضف علامة Dicom جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagDescription | java.lang.String | وصف العلامة. لا يمكن أن يكون فارغًا أو مسافة بيضاء. |
| القيمة | java.lang.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


أضف علامة Dicom جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagDescription | java.lang.String | وصف العلامة. لا يمكن أن يكون فارغًا أو مسافة بيضاء. |
| القيمة | java.lang.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

**Returns:**
boolean - نتيجة العملية.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


أزل علامة موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة التي سيتم تحديثها. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


أزل علامة موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة التي سيتم تحديثها. |

**Returns:**
boolean - نتيجة العملية.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


حدّث علامة موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة التي سيتم تحديثها. |
| newValue | java.lang.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


حدّث علامة موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة التي سيتم تحديثها. |
| newValue | java.lang.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

**Returns:**
boolean - نتيجة العملية.

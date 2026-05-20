---
title: "PdfCoreOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الخيارات الشائعة للتحويل إلى PDF"
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

الخيارات الشائعة للتحويل إلى PDF
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | يحدد عدد مستويات عناصر المخطط لتضمينها في مخطط المستند. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | يحدد عدد مستويات عناصر المخطط لتضمينها في مخطط المستند. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | يحدد عدد المستويات في مخطط المستند التي يتم عرضها موسعة عند عرض ملف PDF. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | يحدد عدد المستويات في مخطط المستند التي يتم عرضها موسعة عند عرض ملف PDF. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | يحدد المستوى الذي يتم فيه عرض كائنات الإشارات المرجعية في مخطط المستند. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | يحدد المستوى الذي يتم فيه عرض كائنات الإشارات المرجعية في مخطط المستند. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة ضغط JPEG للصور (إذا تم استخدام ضغط JPEG). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدد جودة ضغط JPEG للصور (إذا تم استخدام ضغط JPEG). |
| [getPdfCompliance()](#getPdfCompliance--) | يحصل على توافق PDF. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | يضبط توافق PDF. |
| [getCompression()](#getCompression--) | يسترجع الضغط. |
| [setCompression(int value)](#setCompression-int-) | يعيّن الضغط. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


يحدد عدد مستويات عناصر المخطط لتضمينها في مخطط المستند. 0 - لا مخطط، 1 - مستوى مخطط واحد وهكذا. القيمة الافتراضية هي 0.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


يحدد عدد مستويات عناصر المخطط لتضمينها في مخطط المستند. 0 - لا مخطط، 1 - مستوى مخطط واحد وهكذا. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


يحدد عدد المستويات في مخطط المستند التي يتم عرضها موسعة عند عرض ملف PDF. 0 - مخطط المستند غير موسع. 1 - عناصر المستوى الأول في المستند موسعة وهكذا. القيمة الافتراضية هي 0.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


يحدد عدد المستويات في مخطط المستند التي يتم عرضها موسعة عند عرض ملف PDF. 0 - مخطط المستند غير موسع. 1 - عناصر المستوى الأول في المستند موسعة وهكذا. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


يحدد المستوى الذي يتم فيه عرض كائنات الإشارات المرجعية في مخطط المستند. 0 - غير معروض. 1 - المستوى الأول وهكذا. القيمة الافتراضية هي 0.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


يحدد المستوى الذي يتم فيه عرض كائنات الإشارات المرجعية في مخطط المستند. 0 - غير معروض. 1 - المستوى الأول وهكذا. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


يحدد جودة ضغط JPEG للصور (إذا تم استخدام ضغط JPEG). القيمة الافتراضية هي 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


يحدد جودة ضغط JPEG للصور (إذا تم استخدام ضغط JPEG). القيمة الافتراضية هي 95.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


يحصل على توافق PDF.

**Returns:**
int - توافق PDF.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


يضبط توافق PDF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | توافق PDF. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


يسترجع الضغط.

القيمة: الضغط.

**Returns:**
int - الضغط.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


يعيّن الضغط.

القيمة: الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الضغط. |


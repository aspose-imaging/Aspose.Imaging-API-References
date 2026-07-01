---
title: "IcoOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنشئ ملفات صور ICO مخصصة لأيقونات التطبيقات بسهولة باستخدام API الخاص بنا، مما يمكنك من تمثيل برنامجك بسلاسة."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.imageoptions/icooptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class IcoOptions extends ImageOptionsBase
```

أنشئ ملفات صور ICO مخصصة لأيقونات التطبيقات بسهولة باستخدام API الخاص بنا، مما يمكنك من تمثيل برنامجك بسلاسة. يدعم API الخاص بنا إطارات صور PNG و BMP مع قيم مختلفة لعدد البتات لكل بكسل، مما يضمن التنوع والتوافق لاحتياجات إنشاء الأيقونات الخاصة بك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [IcoOptions()](#IcoOptions--) | يقوم بتهيئة نسخة جديدة من الفئة [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) مع تنسيق إطار ICO يساوي Png و bitsPerPixel يساوي 32. |
| [IcoOptions(IcoOptions options)](#IcoOptions-com.aspose.imaging.imageoptions.IcoOptions-) |  |
| [IcoOptions(long format)](#IcoOptions-long-) | يقوم بتهيئة نسخة جديدة من الفئة [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) مع تنسيق إطار ICO يساوي [`format`] و bitsPerPixel يساوي 32. |
| [IcoOptions(long format, int bitsPerPixel)](#IcoOptions-long-int-) | يقوم بتهيئة نسخة جديدة من الفئة [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) | يحصل على تنسيق إطار ICO. |
| [setFormat(long value)](#setFormat-long-) | يضبط تنسيق إطار ICO. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على قيمة البتات لكل بكسل. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | يضبط قيمة البتات لكل بكسل. |
### IcoOptions() {#IcoOptions--}
```
public IcoOptions()
```


يقوم بتهيئة نسخة جديدة من الفئة [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) مع تنسيق إطار ICO يساوي Png و bitsPerPixel يساوي 32.

### IcoOptions(IcoOptions options) {#IcoOptions-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoOptions(IcoOptions options)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) |  |

### IcoOptions(long format) {#IcoOptions-long-}
```
public IcoOptions(long format)
```


يقوم بتهيئة نسخة جديدة من الفئة [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) مع تنسيق إطار ICO يساوي [`format`] و bitsPerPixel يساوي 32.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | long | تنسيق إطار ICO. لاحظ أن صورة ICO تدعم فقط صور [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png) و [FileFormat.Bmp](../../com.aspose.imaging/fileformat\#Bmp) كمدخلات. |

### IcoOptions(long format, int bitsPerPixel) {#IcoOptions-long-int-}
```
public IcoOptions(long format, int bitsPerPixel)
```


يقوم بتهيئة نسخة جديدة من الفئة [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | long | تنسيق إطار ICO. لاحظ أن صورة ICO تدعم فقط صور [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png) و [FileFormat.Bmp](../../com.aspose.imaging/fileformat\#Bmp) كمدخلات. |
| bitsPerPixel | int | قيمة البتات لكل بكسل. |

### getFormat() {#getFormat--}
```
public final long getFormat()
```


يحصل على تنسيق إطار ICO.

**Returns:**
long - تنسيق إطار ICO.
### setFormat(long value) {#setFormat-long-}
```
public final void setFormat(long value)
```


يضبط تنسيق إطار ICO.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | تنسيق إطار ICO. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


يحصل على قيمة البتات لكل بكسل.

**Returns:**
int - قيمة البتات لكل بكسل.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


يضبط قيمة البتات لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | قيمة البتات لكل بكسل. |


---
title: "BitmapV5Header"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "بنية BitmapV5Header هي ملف رأس معلومات البت ماب."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

هيكلية BitmapV5Header هي ملف رأس معلومات البت ماب. إنها نسخة موسعة من هيكلية BITMAPINFOHEADER.

إذا كان bV5Height سالبًا، مما يشير إلى DIB من الأعلى إلى الأسفل، يجب أن يكون bV5Compression إما BI\_RGB أو BI\_BITFIELDS. لا يمكن ضغط DIBs من الأعلى إلى الأسفل. تسمح واجهة إدارة اللون المستقلة (ICM) 2.0 بربط أو تضمين ملفات تعريف اللون الخاصة بـ International Color Consortium (ICC) في DIBs (DIBs). راجع Using Structures لمزيد من المعلومات. عندما يتم تحميل DIB إلى الذاكرة، يجب أن تتبع بيانات الملف التعريفي (إن وجدت) جدول الألوان، ويجب أن يوفر bV5ProfileData إزاحة بيانات الملف التعريفي من بداية هيكلية BITMAPV5HEADER. القيمة المخزنة في bV5ProfileData ستكون مختلفة عن القيمة التي يُرجعها معامل sizeof عند إعطاء وسيط BITMAPV5HEADER، لأن bV5ProfileData هي الإزاحة بالبايتات من بداية هيكلية BITMAPV5HEADER إلى بداية بيانات الملف التعريفي. (لا تتبع بتات البت ماب جدول الألوان في الذاكرة). يجب على التطبيقات تعديل العضو bV5ProfileData بعد تحميل DIB إلى الذاكرة. بالنسبة لـ DIBs المعبأة، يجب أن تتبع بيانات الملف التعريفي بتات البت ماب مشابهة لتنسيق الملف. يجب أن يظل العضو bV5ProfileData يعطي إزاحة بيانات الملف التعريفي من بداية BITMAPV5HEADER. يجب على التطبيقات الوصول إلى بيانات الملف التعريفي فقط عندما يكون bV5Size مساويًا لحجم BITMAPV5HEADER وbV5CSType يساوي PROFILE\_EMBEDDED أو PROFILE\_LINKED.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | ينشئ مثيلاً جديدًا من الفئة `BitmapV5Header`. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | ينشئ مثيلاً جديدًا من الفئة `BitmapV5Header`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIntent()](#getIntent--) | يحصل على نية العرض للبت ماب. |
| [setIntent(long value)](#setIntent-long-) | يعيّن نية العرض للبت ماب. |
| [getProfileData()](#getProfileData--) | يحصل على بيانات الملف التعريفي. |
| [setProfileData(long value)](#setProfileData-long-) | يضبط بيانات الملف الشخصي. |
| [getProfileSize()](#getProfileSize--) | يحصل على حجم الملف الشخصي. |
| [setProfileSize(long value)](#setProfileSize-long-) | يضبط حجم الملف الشخصي. |
| [getReserved()](#getReserved--) | يحصل على العضو المحجوز. |
| [setReserved(long value)](#setReserved-long-) | يضبط العضو المحجوز. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


ينشئ مثيلاً جديدًا من الفئة `BitmapV5Header`.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


ينشئ مثيلاً جديدًا من الفئة `BitmapV5Header`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


يحصل على نية العرض للبت ماب.

**Returns:**
long - النية.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


يعيّن نية العرض للبت ماب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | النية. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


يحصل على بيانات الملف التعريفي.

**Returns:**
long - بيانات الملف الشخصي.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


يضبط بيانات الملف الشخصي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | بيانات الملف الشخصي. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


يحصل على حجم الملف الشخصي.

**Returns:**
long - حجم الملف الشخصي.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


يضبط حجم الملف الشخصي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | حجم الملف الشخصي. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


يحصل على العضو المحجوز.

**Returns:**
long - القيمة المحجوزة.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


يضبط العضو المحجوز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | القيمة المحجوزة. |


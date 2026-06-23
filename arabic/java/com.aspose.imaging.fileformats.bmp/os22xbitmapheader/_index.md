---
title: "Os22XBitmapHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "رأس OS/2 2.x OS22XBITMAPHEADER المعروف أيضًا باسم BITMAPCOREHEADER2."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

رأس OS/2 2.x OS22XBITMAPHEADER المعروف أيضًا باسم BITMAPCOREHEADER2.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getUnits()](#getUnits--) | يحصل على الوحدات. |
| [getReserved()](#getReserved--) | يحصل على المحجوز. |
| [getRecording()](#getRecording--) | يحصل على التسجيل. |
| [getRendering()](#getRendering--) | يحصل على العرض. |
| [getSize1()](#getSize1--) | يحصل على الحجم1. |
| [getSize2()](#getSize2--) | يحصل على الحجم2. |
| [getColorEncoding()](#getColorEncoding--) | يحصل على ترميز اللون. |
| [getIdentifier()](#getIdentifier--) | يحصل على المعرف. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


يحصل على الوحدات.

**Returns:**
int - نوع الوحدات المستخدمة لقياس الدقة
### getReserved() {#getReserved--}
```
public int getReserved()
```


يحصل على المحجوز.

**Returns:**
int - حشو البنية إلى حد 4 بايت
### getRecording() {#getRecording--}
```
public int getRecording()
```


يحصل على التسجيل.

**Returns:**
int - خوارزمية التسجيل
### getRendering() {#getRendering--}
```
public int getRendering()
```


يحصل على العرض.

**Returns:**
int - خوارزمية التظليل المستخدمة
### getSize1() {#getSize1--}
```
public int getSize1()
```


يحصل على الحجم1.

**Returns:**
int - محجوز لاستخدام خوارزمية التظليل
### getSize2() {#getSize2--}
```
public int getSize2()
```


يحصل على الحجم2.

**Returns:**
int - محجوز لاستخدام خوارزمية التظليل
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


يحصل على ترميز اللون.

**Returns:**
int - نموذج اللون المستخدم في الصورة النقطية
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


يحصل على المعرف.

**Returns:**
int - محجوز لاستخدام التطبيق

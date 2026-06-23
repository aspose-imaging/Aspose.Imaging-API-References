---
title: "XmpPackageBaseCollection"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مجموعة من XmpPackage."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

يمثل مجموعة من `XmpPackage`.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | يُنشئ مثلاً جديداً من الفئة `XmpPackageBaseCollection`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد العناصر في المجموعة. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | يضيف مثلاً جديداً من `XmpPackage`. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | يزيل حزمة XMP المحددة. |
| [getPackages()](#getPackages--) | احصل على مصفوفة من `XmpPackage`. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | يحصل على `XmpPackage` بواسطة namespaceURI الخاص به. |
| [clear()](#clear--) | امسح جميع `XmpPackage` داخل المجموعة. |
| [iterator()](#iterator--) | يرجع عدّادًا يتنقل عبر مجموعة. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


يُنشئ مثلاً جديداً من الفئة `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


يحصل على عدد العناصر في المجموعة.

القيمة: عدد العناصر في المجموعة.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


يضيف مثلاً جديداً من `XmpPackage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | حزمة XMP\_ المراد إضافتها. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


يزيل حزمة XMP المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | حزمة XMP\_ لإزالتها. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


احصل على مصفوفة من `XmpPackage`.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - إرجاع مصفوفة من حزم XMP.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


يحصل على `XmpPackage` بواسطة namespaceURI الخاص به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| namespaceUri | java.lang.String | معرف URI للمساحة الاسمية للحصول على حزمة\_. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


امسح جميع `XmpPackage` داخل المجموعة.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


يرجع عدّادًا يتنقل عبر مجموعة.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - كائن `System.Collections.IEnumerator` يمكن استخدامه للتنقل عبر المجموعة.

---
title: "ComplexTypeBase"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل التجريد الأساسي لنوع القيمة المعقدة XMP."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.xmp.types.complex/complextypebase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

يمثل التجريد الأساسي لنوع القيمة المعقدة XMP.

انظر المزيد: XMP Specification Part 2, Chapter 1.2.2
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة `ComplexTypeBase`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPrefix()](#getPrefix--) | يحصل على البادئة. |
| [getNamespaceUri()](#getNamespaceUri--) | يحصل على URI مساحة الاسم الافتراضية. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


يقوم بتهيئة نسخة جديدة من الفئة `ComplexTypeBase`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بادئة | java.lang.String | البادئة. |
| namespaceUri | java.lang.String | URI مساحة الاسم. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


يحصل على البادئة.

**Returns:**
java.lang.String - البادئة.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


يحصل على URI مساحة الاسم الافتراضية.

**Returns:**
java.lang.String - URI مساحة الاسم الافتراضية.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.

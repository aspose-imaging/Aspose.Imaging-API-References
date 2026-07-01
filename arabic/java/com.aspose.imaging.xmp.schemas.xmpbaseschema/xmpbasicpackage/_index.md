---
title: "XmpBasicPackage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثّل مساحة الاسم الأساسية لـ XMP."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

يمثّل مساحة الاسم الأساسية لـ XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | ينشئ مثيلاً جديدًا للفئة `XmpBasicPackage`. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | ينشئ مثيلاً جديدًا للفئة `XmpBasicPackage`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | قيمة التقييم المرفوضة. |
| [RATING_MIN](#RATING-MIN) | قيمة الحد الأدنى للتقييم. |
| [RATING_MAX](#RATING-MAX) | قيمة الحد الأقصى للتقييم. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | يضبط التسمية. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | يضيف خاصية نصية. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | يضيف تاريخ إنشاء المورد. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | يضيف تاريخ إنشاء المورد. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | يضبط أداة الإنشاء. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | يضبط المعرّف. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | يضيف تاريخ آخر تعديل للمورد. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | يضيف تاريخ آخر تعديل للمورد. |
| [setRating(int choice)](#setRating-int-) | يضبط التقييم. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


ينشئ مثيلاً جديدًا للفئة `XmpBasicPackage`.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


ينشئ مثيلاً جديدًا للفئة `XmpBasicPackage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السابقة | java.lang.String | السابقة. |
| namespaceUri | java.lang.String | معرّف URI للمساحة الاسمية. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


قيمة التقييم المرفوضة.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


قيمة الحد الأدنى للتقييم.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


قيمة الحد الأقصى للتقييم.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


يضبط التسمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تسمية | java.lang.String | التسمية. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


يضيف خاصية نصية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | التمثيل النصي للمفتاح الذي يتم التعرف عليه بالقيمة المضافة. |
| value | java.lang.String | القيمة النصية. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


يضيف تاريخ إنشاء المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createdDate | java.util.Date | تاريخ الإنشاء. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


يضيف تاريخ إنشاء المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createdDate | java.lang.String | تاريخ الإنشاء. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


يضبط أداة الإنشاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| creatorTool | java.lang.String | اسم الأداة. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


يضبط المعرّف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| معرف | java.lang.String[] | المعرف. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


يضيف تاريخ آخر تعديل للبيانات الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadataDate | java.util.Date | تاريخ البيانات الوصفية. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


يضيف تاريخ آخر تعديل للبيانات الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadataDate | java.lang.String | تاريخ البيانات الوصفية. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


يضيف تاريخ آخر تعديل للمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| modifiedDate | java.util.Date | تاريخ آخر تعديل. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


يضيف تاريخ آخر تعديل للمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| modifiedDate | java.lang.String | تاريخ آخر تعديل. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


يضبط التقييم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اختيار | int | من -1 إلى 5 |


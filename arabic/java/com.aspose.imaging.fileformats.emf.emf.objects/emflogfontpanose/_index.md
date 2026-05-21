---
title: "EmfLogFontPanose"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LogFontPanose يحدد خصائص PANOSE لخط منطقي."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

كائن LogFontPanose يحدد خصائص PANOSE لخط منطقي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | يُنشئ نسخة جديدة من الفئة `EmfLogFontPanose`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFullName()](#getFullName--) | يحصل أو يعيّن سلسلة مكوّنة من 64 حرف يونيكود تُعرّف الاسم الكامل للخط. |
| [setFullName(String value)](#setFullName-java.lang.String-) | يحصل أو يعيّن سلسلة مكوّنة من 64 حرف يونيكود تُعرّف الاسم الكامل للخط. |
| [getStyle()](#getStyle--) | الحصول أو التعيين لسلسلة مكوّنة من 32 حرف يونيكود تحدد نمط الخط. |
| [setStyle(String value)](#setStyle-java.lang.String-) | الحصول أو التعيين لسلسلة مكوّنة من 32 حرف يونيكود تحدد نمط الخط. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن. يجب تجاهل هذا الحقل. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يعيّن. يجب تجاهل هذا الحقل. |
| [getStyleSize()](#getStyleSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم النقطة الذي يُجرى فيه تحسين الخط. |
| [setStyleSize(int value)](#setStyleSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم النقطة الذي يُجرى فيه تحسين الخط. |
| [getMatch()](#getMatch--) | يحصل أو يعيّن. يجب تجاهل هذا الحقل. |
| [setMatch(int value)](#setMatch-int-) | يحصل أو يعيّن. يجب تجاهل هذا الحقل. |
| [getVendorId()](#getVendorId--) | يحصل أو يعيّن. يجب تجاهل هذا الحقل. |
| [setVendorId(int value)](#setVendorId-int-) | يحصل أو يعيّن. يجب تجاهل هذا الحقل. |
| [getCulture()](#getCulture--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يجب أن يُضبط على الصفر ويجب تجاهله. |
| [setCulture(int value)](#setCulture-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يجب أن يُضبط على الصفر ويجب تجاهله. |
| [getPanose()](#getPanose--) | يحصل أو يعيّن كائن Panose (القسم 2.2.21) الذي يحدد خصائص PANOSE للخط المنطقي. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | يحصل أو يعيّن كائن Panose (القسم 2.2.21) الذي يحدد خصائص PANOSE للخط المنطقي. |
| [getPadding()](#getPadding--) | يحصل أو يعيّن حقلًا موجودًا فقط لضمان محاذاة 32-بت لهذا الهيكل. |
| [setPadding(short value)](#setPadding-short-) | يحصل أو يعيّن حقلًا موجودًا فقط لضمان محاذاة 32-بت لهذا الهيكل. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


يُنشئ نسخة جديدة من الفئة `EmfLogFontPanose`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | الخط الأساسي المسجَّل. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


يحصل أو يعيّن سلسلة مكوّنة من 64 حرف يونيكود تُعرّف الاسم الكامل للخط. إذا كان طول هذه السلسلة أقل من 64 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


يحصل أو يعيّن سلسلة مكوّنة من 64 حرف يونيكود تُعرّف الاسم الكامل للخط. إذا كان طول هذه السلسلة أقل من 64 حرفًا، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


الحصول أو التعيين لسلسلة مكوّنة من 32 حرف يونيكود تحدد نمط الخط. إذا كان طول هذه السلسلة أقل من 32 حرفاً، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي هذا الحقل.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


الحصول أو التعيين لسلسلة مكوّنة من 32 حرف يونيكود تحدد نمط الخط. إذا كان طول هذه السلسلة أقل من 32 حرفاً، يجب أن يكون هناك NULL نهائي، وبعده يجب تجاهل باقي هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يحصل أو يعيّن. يجب تجاهل هذا الحقل.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يحصل أو يعيّن. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم النقطة الذي يُجرى فيه تحسين الخط. إذا تم ضبطه على الصفر، يُجرى تحسين الخط بحجم النقطة المقابل لحقل Height في كائن LogFont داخل حقل LogFont.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم النقطة الذي يُجرى فيه تحسين الخط. إذا تم ضبطه على الصفر، يُجرى تحسين الخط بحجم النقطة المقابل لحقل Height في كائن LogFont داخل حقل LogFont.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


يحصل أو يعيّن. يجب تجاهل هذا الحقل.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


يحصل أو يعيّن. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


يحصل أو يعيّن. يجب تجاهل هذا الحقل.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


يحصل أو يعيّن. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يجب أن يُضبط على الصفر ويجب تجاهله.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يجب أن يُضبط على الصفر ويجب تجاهله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


يحصل أو يعيّن كائن Panose (القسم 2.2.21) الذي يحدد خصائص PANOSE للخط المنطقي. إذا كانت جميع حقول هذا الكائن صفرًا، يجب تجاهله.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


يحصل أو يعيّن كائن Panose (القسم 2.2.21) الذي يحدد خصائص PANOSE للخط المنطقي. إذا كانت جميع حقول هذا الكائن صفرًا، يجب تجاهله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


يحصل أو يعيّن حقلًا موجودًا فقط لضمان محاذاة 32-بت لهذا الهيكل. يجب تجاهله

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


يحصل أو يعيّن حقلًا موجودًا فقط لضمان محاذاة 32-بت لهذا الهيكل. يجب تجاهله

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |


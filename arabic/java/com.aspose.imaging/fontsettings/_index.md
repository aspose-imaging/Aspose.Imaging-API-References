---
title: "FontSettings"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إعدادات خطوط عارض صيغ المتجهات العامة للتصوير."
type: docs
weight: 49
url: /ar/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

إعدادات خطوط عارض صيغ المتجهات العامة للتصوير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | يحصل على قيمة تشير إلى ما إذا كان [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | يضبط قيمة تشير إلى ما إذا كان [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | يحصل على اسم الخط الافتراضي. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | يضبط اسم الخط الافتراضي. |
| [getFontsFolders()](#getFontsFolders--) | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Imaging عن خطوط TrueType. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | يحصل على مجلدات الخطوط الافتراضية. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | تجاوز قائمة مجلد الخطوط لـ `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | تجاوز قائمة مجلد الخطوط لـ `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | يضبط المجلدات التي يتم تحميل خطوط TrueType منها ويمسح جميع الخطوط المحملة. |
| [reset()](#reset--) | يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى الإعداد الافتراضي للنظام. |
| [updateFonts()](#updateFonts--) | يحدّث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | يضيف `fontFolder` إلى قائمة دليل الخطوط ويحدده كأول مجلد للبحث عن الخطوط |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | يزيل `folder` من قائمة المجلدات |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


يحصل على قيمة تشير إلى ما إذا كان [get alternative font].

القيمة: `true` إذا كان [get alternative font]؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [get alternative font].

القيمة: `true` إذا كان [get alternative font]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


يحصل على اسم الخط الافتراضي.

**Returns:**
java.lang.String - اسم الخط الافتراضي
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


يضبط اسم الخط الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | الاسم الافتراضي للخط. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Imaging عن خطوط TrueType.

القيمة المرجعة هي نسخة من البيانات التي يستخدمها Aspose.Imaging. إذا قمت بتغيير العناصر في المصفوفة المرجعة، فلن يؤثر ذلك على عرض المستند. لتحديد مواقع خطوط جديدة استخدم الطريقة `setFontsFolders`.

**Returns:**
java.lang.String[] - نسخة من مواقع الخطوط الحالية.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


يحصل على مجلدات الخطوط الافتراضية.

**Returns:**
java.lang.String[] - يُعيد مجلد النظام
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


تجاوز قائمة مجلد الخطوط لـ `folder`

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folder | java.lang.String | مجلد يحتوي على خطوط TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


تجاوز قائمة مجلد الخطوط لـ `folders`

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folders | java.lang.String[] | مصفوفة من المجلدات |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


يضبط المجلدات التي يتم تحميل خطوط TrueType منها ويُمسح جميع الخطوط المحملة. لا يتم إجراء أي فحوصات على مجلدات الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folders | java.lang.String[] | مجلدات الخطوط. |
| recursive | boolean | إذا تم تعيينه إلى `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى الإعداد الافتراضي للنظام.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


يحدّث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. تضمن هذه الطريقة أن الخطوط من المجلد fontsFolder باستخدام الطريقة FontSettings.setFontsFolder(fontsFolder) أو بعد إعادة ضبط الخطوط باستخدام FontSettings.reset() سيتم أخذها في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة يتم فيها استدعاء FontSettings.setFontsFolder(fontsFolder) أو FontSettings.reset() لصور PSD. دون استدعاء هذه الطريقة لا توجد ضمانات بتحديث الخطوط.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


يضيف `fontFolder` إلى قائمة دليل الخطوط ويحدده كأول مجلد للبحث عن الخطوط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFolder | java.lang.String | المجلد يحتوي على خطوط TrueType أو مسار ملف خط واحد. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


يزيل `folder` من قائمة المجلدات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folder | java.lang.String | المجلد المراد إزالته |


---
title: "فئة FontSettings"
type: docs
weight: 4850
url: /ar/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | يحصل أو يعيّن الاسم الافتراضي للخط. |
| get_system_alternative_font [static] | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font]. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | يحصل على مجلدات الخطوط الافتراضية. |
| [get_fonts_folders()](#get_fonts_folders__2) | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Words عن خطوط TrueType. |
| reset() | يعيد تعيين مجلد الخطوط والاسم الافتراضي للخط إلى الإعداد الافتراضي للنظام. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | هذا اختصار إلى [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) لتعيين دليل خط واحد فقط.<br/>            لا يتم إجراء أي فحوصات على مجلد الخطوط. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | يعيّن المجلدات التي يتم تحميل خطوط TrueType منها ويزيل جميع الخطوط المحملة.<br/>            لا يتم إجراء أي فحوصات على مجلدات الخطوط. |
| update_fonts() | يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. يضمن هذه الطريقة أن الخطوط من المجلد fontsFolder باستخدام<br/>            الطريقة FontSettings.SetFontsFolder(fontsFolder) أو بعد إعادة تعيين الخطوط باستخدام FontSettings.Reset() سيتم أخذها في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة يتم فيها <br/>            استدعاء FontSettings.SetFontsFolder(fontsFolder) أو FontSettings.Reset() لصور PSD. بدون استدعاء هذه الطريقة لا يوجد ضمان بأن الخطوط سيتم تحديثها. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

يحصل على مجلدات الخطوط الافتراضية.

**Returns**

| نوع | الوصف |
| :- | :- |
| string[] | يعيد مجلد النظام |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Words عن خطوط TrueType.

**Returns**

| نوع | الوصف |
| :- | :- |
| string[] | نسخة من مواقع الخط الحالية. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

هذا اختصار إلى [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) لتعيين دليل خط واحد فقط.<br/>            لا يتم إجراء أي فحوصات على مجلد الخطوط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_folder | string | مجلد الخط. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

يعيّن المجلدات التي يتم تحميل خطوط TrueType منها ويزيل جميع الخطوط المحملة.<br/>            لا يتم إجراء أي فحوصات على مجلدات الخطوط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| fonts_folders | string[] | مجلدات الخطوط. |
| recursive | bool | إذا تم تعيينه إلى <c>true</c> [recursive]. |


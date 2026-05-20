---
title: "SvgResourceKeeperCallback"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "استدعاء رد النداء لمُحافظ الموارد"
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

استدعاء رد النداء لمُحافظ الموارد
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | يتم الاستدعاء عندما يكون مورد الصورة جاهزًا للتصدير. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | يتم الاستدعاء عندما يكون مورد الخط جاهزًا للتصدير. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | يتم الاستدعاء عندما يكون مستند SVG جاهزًا للتصدير. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


يتم الاستدعاء عندما يكون مورد الصورة جاهزًا للتصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageData | byte[] | بيانات المورد. |
| imageType | int | نوع الصورة. |
| suggestedFileName | java.lang.String | اسم الملف المقترح. |
| useEmbeddedImage | boolean[] | إذا تم تعيينه إلى `true` يجب استخدام الصورة المدمجة. |

**Returns:**
java.lang.String - يُرجع المسار إلى المورد المحفوظ. يجب أن يكون المسار نسبيًا إلى مستند SVG الهدف.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


يتم الاستدعاء عندما يكون مورد الخط جاهزًا للتصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | خيارات تخزين الخط. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


يتم الاستدعاء عندما يكون مستند SVG جاهزًا للتصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlData | byte[] | بيانات SVG. |
| suggestedFileName | java.lang.String | اسم الملف المقترح. |

**Returns:**
java.lang.String - يُرجع المسار إلى مستند SVG المحفوظ.

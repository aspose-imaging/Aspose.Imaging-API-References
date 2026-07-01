---
title: "EmfPlusGraphicsVersion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الكائن EmfPlusGraphicsVersion يحدد نسخة رسومات نظام التشغيل التي تُستخدم لإنشاء ملف تعريف EMF."
type: docs
weight: 44
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

كائن EmfPlusGraphicsVersion يحدد إصدار رسومات نظام التشغيل المستخدم لإنشاء ملف تعريف EMF+.

إصدارات الرسومات قابلة للتوسيع من قبل البائع؛ ومع ذلك، لضمان التوافقية، يجب تنفيذ أي امتداد من هذا النوع في كل من العملاء والخوادم لملفات تعريف EMF+.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | يحصل على MetafileSignature (20 بت): قيمة تحدد نوع ملف التعريف. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | يحصل على MetafileSignature (20 بت): قيمة تحدد نوع ملف التعريف. |
| [getGraphicsVersion()](#getGraphicsVersion--) | يحصل على GraphicsVersion (12 بت): نسخة رسومات نظام التشغيل. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | يحصل على GraphicsVersion (12 بت): نسخة رسومات نظام التشغيل. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


يحصل على MetafileSignature (20 بت): قيمة تحدد نوع ملف التعريف. القيمة لملف تعريف EMF+ هي 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


يحصل على MetafileSignature (20 بت): قيمة تحدد نوع ملف التعريف. القيمة لملف تعريف EMF+ هي 0xDBC01.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


يحصل على GraphicsVersion (12 بت): نسخة رسومات نظام التشغيل. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusGraphicsVersion`

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


يحصل على GraphicsVersion (12 بت): نسخة رسومات نظام التشغيل. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusGraphicsVersion`

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


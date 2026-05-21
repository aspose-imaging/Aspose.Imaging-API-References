---
title: "EmfPlusLanguageIdentifier"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusLanguageIdentifier يحدد معرف لغة يتطابق مع اللغة الطبيعية في إعداد إقليمي يشمل البلدان والمناطق الجغرافية والدوائر الإدارية."
type: docs
weight: 50
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

كائن EmfPlusLanguageIdentifier يحدد معرف لغة يتطابق مع اللغة الطبيعية في إعداد إقليمي، بما في ذلك البلدان والمناطق الجغرافية والدوائر الإدارية. كل معرف لغة هو ترميز لقيمة لغة أساسية وقيمة لغة فرعية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 بت): البلد أو المنطقة الجغرافية أو الدائرة الإدارية للغة الطبيعية المحددة في حقل PrimaryLanguageId. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 بت): البلد أو المنطقة الجغرافية أو الدائرة الإدارية للغة الطبيعية المحددة في حقل PrimaryLanguageId. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


يحصل أو يعيّن قيمة الحقل 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 بت): البلد أو المنطقة الجغرافية أو الدائرة الإدارية للغة الطبيعية المحددة في حقل PrimaryLanguageId. معرفات اللغة الفرعية قابلة للتوسيع من قبل البائع. يجب أن تكون معرفات اللغة الفرعية المعرفة من قبل البائع في النطاق 0x20 إلى 0x3F، شاملًا. PrimaryLanguageId (10 بت): اللغة الطبيعية. معرفات اللغة الأساسية قابلة للتوسيع من قبل البائع. يجب أن تكون معرفات اللغة الأساسية المعرفة من قبل البائع في النطاق 0x0200 إلى 0x03FF، شاملًا.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


يحصل أو يعيّن قيمة الحقل 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 بت): البلد أو المنطقة الجغرافية أو الدائرة الإدارية للغة الطبيعية المحددة في حقل PrimaryLanguageId. معرفات اللغة الفرعية قابلة للتوسيع من قبل البائع. يجب أن تكون معرفات اللغة الفرعية المعرفة من قبل البائع في النطاق 0x20 إلى 0x3F، شاملًا. PrimaryLanguageId (10 بت): اللغة الطبيعية. معرفات اللغة الأساسية قابلة للتوسيع من قبل البائع. يجب أن تكون معرفات اللغة الأساسية المعرفة من قبل البائع في النطاق 0x0200 إلى 0x03FF، شاملًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |


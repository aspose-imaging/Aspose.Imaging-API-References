---
title: "GifBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تنفيذ كتلة gif الافتراضي."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

تنفيذ كتلة gif الافتراضي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | مُدخل الامتداد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isChanged()](#isChanged--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الكتلة قد تغيرت وتحتاج إلى حفظ. |
| [setChanged(boolean value)](#setChanged-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الكتلة قد تغيرت وتحتاج إلى حفظ. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | يحفظ الكتلة إلى الدفق المحدد. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


مُدخل الامتداد.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الكتلة قد تغيرت وتحتاج إلى حفظ.

القيمة: `true` إذا تغيرت الكتلة؛ وإلا `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الكتلة قد تغيرت وتحتاج إلى حفظ.

القيمة: `true` إذا تغيرت الكتلة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


يحفظ الكتلة إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | الدفق لحفظ البيانات إليه. |


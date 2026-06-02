---
title: "WmfEscapeEnhancedMetafile"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل Escape Enhanced Meta file."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

سجل Escape Enhanced Meta file.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | يحصل أو يعيّن معرف التعليق. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | يحصل أو يعيّن معرف التعليق. |
| [getCommentType()](#getCommentType--) | يحصل أو يعيّن نوع التعليق. |
| [setCommentType(int value)](#setCommentType-int-) | يحصل أو يعيّن نوع التعليق. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن الإصدار. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يعيّن الإصدار. |
| [getChecksum()](#getChecksum--) | يحصل أو يعيّن المجموع الاختباري. |
| [setChecksum(int value)](#setChecksum-int-) | يحصل أو يعيّن المجموع الاختباري. |
| [getFlags()](#getFlags--) | يحصل أو يضبط العلامات. |
| [setFlags(int value)](#setFlags-int-) | يحصل أو يضبط العلامات. |
| [getCommentRecordCount()](#getCommentRecordCount--) | يحصل أو يعيّن عدد سجلات التعليق. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | يحصل أو يعيّن عدد سجلات التعليق. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | يحصل أو يعيّن حجم السجل الحالي. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | يحصل أو يعيّن حجم السجل الحالي. |
| [getRemainingBytes()](#getRemainingBytes--) | يحصل أو يعيّن عدد البايتات المتبقية. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | يحصل أو يعيّن عدد البايتات المتبقية. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | يحصل أو يعيّن حجم بيانات ملف الميتافيل المحسّن. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | يحصل أو يعيّن حجم بيانات ملف الميتافيل المحسّن. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | يحصل أو يعيّن بيانات ملف الميتافيل المحسّن. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | يحصل أو يعيّن بيانات ملف الميتافيل المحسّن. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


يحصل أو يعيّن معرف التعليق.

القيمة: عدد صحيح غير موقع 32‑بت يحدد هذا السجل كـ WMF Comment record. يجب أن تكون هذه القيمة 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


يحصل أو يعيّن معرف التعليق.

القيمة: عدد صحيح غير موقع 32‑بت يحدد هذا السجل كـ WMF Comment record. يجب أن تكون هذه القيمة 0x43464D57.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


يحصل أو يعيّن نوع التعليق.

القيمة: عدد صحيح غير موقع 32‑بت يحدد نوع التعليق في هذا السجل. يجب أن تكون هذه القيمة 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


يحصل أو يعيّن نوع التعليق.

القيمة: عدد صحيح غير موقع 32‑بت يحدد نوع التعليق في هذا السجل. يجب أن تكون هذه القيمة 0x00000001.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يحصل أو يعيّن الإصدار.

القيمة: عدد صحيح غير موقع 32‑بت يحدد توافق ملف تعريف EMF. ينبغي أن يكون هذا 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يحصل أو يعيّن الإصدار.

القيمة: عدد صحيح غير موقع 32‑بت يحدد توافق ملف تعريف EMF. ينبغي أن يكون هذا 0x00010000.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


يحصل أو يعيّن المجموع الاختباري.

القيمة: عدد صحيح غير موقع 16‑بت يُستخدم للتحقق من صحة تدفق EMF المضمّن. يجب أن تكون هذه القيمة متممة الواحد للنتيجة التي تُحصل عليها بتطبيق عملية XOR على جميع WORDs في تدفق EMF.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


يحصل أو يعيّن المجموع الاختباري.

القيمة: عدد صحيح غير موقع 16‑بت يُستخدم للتحقق من صحة تدفق EMF المضمّن. يجب أن تكون هذه القيمة متممة الواحد للنتيجة التي تُحصل عليها بتطبيق عملية XOR على جميع WORDs في تدفق EMF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


يحصل أو يضبط العلامات.

القيمة: هذا العدد الصحيح غير الموقع 32‑بت غير مستخدم ويجب تعيينه إلى الصفر.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


يحصل أو يضبط العلامات.

القيمة: هذا العدد الصحيح غير الموقع 32‑بت غير مستخدم ويجب تعيينه إلى الصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


يحصل أو يعيّن عدد سجلات التعليق.

القيمة: عدد صحيح غير موقع 32‑بت يحدد العدد الإجمالي لسجلات META\_ESCAPE\_ENHANCED\_METAFILE المتتالية التي تحتوي على ملف EMF المضمّن.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


يحصل أو يعيّن عدد سجلات التعليق.

القيمة: عدد صحيح غير موقع 32‑بت يحدد العدد الإجمالي لسجلات META\_ESCAPE\_ENHANCED\_METAFILE المتتالية التي تحتوي على ملف EMF المضمّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


يحصل أو يعيّن حجم السجل الحالي.

القيمة: عدد صحيح غير موقع 32‑بت يحدد حجم حقل EnhancedMetafileData بالبايت. يجب أن تكون هذه القيمة أقل من أو تساوي 8,192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


يحصل أو يعيّن حجم السجل الحالي.

القيمة: عدد صحيح غير موقع 32‑بت يحدد حجم حقل EnhancedMetafileData بالبايت. يجب أن تكون هذه القيمة أقل من أو تساوي 8,192.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


يحصل أو يعيّن عدد البايتات المتبقية.

القيمة: عدد صحيح غير موقع 32‑بت يحدد عدد البايتات في تدفق EMF المتبقية للمعالجة بعد هذا السجل. يجب أن تتبع تلك البايتات الإضافية من EMF في حقول EnhancedMetafileData لسجلات META\_ESCAPE\_ENHANDED\_METAFILE اللاحقة.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


يحصل أو يعيّن عدد البايتات المتبقية.

القيمة: عدد صحيح غير موقع 32‑بت يحدد عدد البايتات في تدفق EMF المتبقية للمعالجة بعد هذا السجل. يجب أن تتبع تلك البايتات الإضافية من EMF في حقول EnhancedMetafileData لسجلات META\_ESCAPE\_ENHANDED\_METAFILE اللاحقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


يحصل أو يعيّن حجم بيانات ملف الميتافيل المحسّن.

القيمة: عدد صحيح غير موقع 32‑بت يحدد الحجم الكلي لتدفق EMF المضمّن في هذه السلسلة من سجلات META\_ESCAPE\_ENHANCED\_METAFILE.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


يحصل أو يعيّن حجم بيانات ملف الميتافيل المحسّن.

القيمة: عدد صحيح غير موقع 32‑بت يحدد الحجم الكلي لتدفق EMF المضمّن في هذه السلسلة من سجلات META\_ESCAPE\_ENHANCED\_METAFILE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


يحصل أو يعيّن بيانات ملف الميتافيل المحسّن.

القيمة: جزء من ملف EMF. يجب ربط البايتات في سجلات META\_ESCAPE\_ENHANCED\_METAFILE المتتالية لتمثيل ملف EMF المضمّن بالكامل.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


يحصل أو يعيّن بيانات ملف الميتافيل المحسّن.

القيمة: جزء من ملف EMF. يجب ربط البايتات في سجلات META\_ESCAPE\_ENHANCED\_METAFILE المتتالية لتمثيل ملف EMF المضمّن بالكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |


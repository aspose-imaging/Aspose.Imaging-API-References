---
title: "Jpeg2000LoadOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات تحميل JPEG2000"
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.imageloadoptions/jpeg2000loadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

خيارات تحميل JPEG2000
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | ينشئ مثيلاً جديدًا من الفئة `Jpeg2000LoadOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | يحصل على الحد الأقصى لوقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع توقف العملية عند معالجة صور كبيرة جدًا - الدقة أكثر من 5500x6500 بكسل). |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | يضبط الحد الأقصى لوقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع توقف العملية عند معالجة صور كبيرة جدًا - الدقة أكثر من 5500x6500 بكسل). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | يحصل على الحد الأقصى لوقت فك الترميز للقطعة. |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | يضبط الحد الأقصى لوقت فك الترميز للقطعة. |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


ينشئ مثيلاً جديدًا من الفئة `Jpeg2000LoadOptions`.

### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


يحصل على الحد الأقصى لوقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع توقف العملية عند معالجة صور كبيرة جدًا - الدقة أكثر من 5500x6500 بكسل).

**Returns:**
int - الحد الأقصى لوقت فك الترميز.
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


يضبط الحد الأقصى لوقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع توقف العملية عند معالجة صور كبيرة جدًا - الدقة أكثر من 5500x6500 بكسل).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الحد الأقصى لوقت فك الترميز. |

### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


يحصل على الحد الأقصى لوقت فك الترميز للقطعة.

القيمة: الحد الأقصى لوقت فك الترميز للقطعة.

**Returns:**
int - الحد الأقصى لوقت فك الترميز للقطعة.
### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


يضبط الحد الأقصى لوقت فك الترميز للقطعة.

القيمة: الحد الأقصى لوقت فك الترميز للقطعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الحد الأقصى لوقت فك الترميز للقطعة. |


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
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000LoadOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | يحصل على أقصى وقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع التوقف أثناء معالجة الصور الكبيرة - الدقة أكثر من 5500x6500 بكسل). |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | يضبط أقصى وقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع التوقف أثناء معالجة الصور الكبيرة - الدقة أكثر من 5500x6500 بكسل). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | يحصل على أقصى وقت فك الترميز للقطعة. |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | يضبط أقصى وقت فك الترميز للقطعة. |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000LoadOptions`.

### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


يحصل على أقصى وقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع التوقف أثناء معالجة الصور الكبيرة - الدقة أكثر من 5500x6500 بكسل).

**Returns:**
int - أقصى وقت فك الترميز.
### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


يضبط أقصى وقت فك الترميز بالثواني (يمكن استخدام هذا الخيار على الأجهزة البطيئة جدًا في الذاكرة لمنع التوقف أثناء معالجة الصور الكبيرة - الدقة أكثر من 5500x6500 بكسل).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | أقصى وقت فك الترميز. |

### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


يحصل على أقصى وقت فك الترميز للقطعة.

القيمة: أقصى وقت فك الترميز للقطعة.

**Returns:**
int - أقصى وقت فك الترميز للقطعة.
### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


يضبط أقصى وقت فك الترميز للقطعة.

القيمة: أقصى وقت فك الترميز للقطعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | أقصى وقت فك الترميز للقطعة. |


---
title: "IntRange"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة لتمثيل تسلسل العناصر"
type: docs
weight: 64
url: /ar/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

فئة لتمثيل تسلسل العناصر
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | يُنشئ مثيلاً جديدًا للفئة `IntRange`. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | يُنشئ مثيلاً جديدًا للفئة `IntRange`. |
| [IntRange(int[] range)](#IntRange-int---) | يُنشئ مثيلاً جديدًا للفئة `IntRange`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRange()](#getRange--) | يحصل على النطاق. |
| [setRange(int[] value)](#setRange-int---) | يضبط النطاق. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | يرجع مصفوفة عنصر واحد من الفهرس المحدد |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | يحصل على نطاق العد لعناصر int بدءًا من start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


يُنشئ مثيلاً جديدًا للفئة `IntRange`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| start | int | البداية. |
| count | int | العدد. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


يُنشئ مثيلاً جديدًا للفئة `IntRange`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| start | int | البداية. |
| count | int | العدد. |
| delta | int | الفرق. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


يُنشئ مثيلاً جديدًا للفئة `IntRange`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| range | int[] | النطاق. |

### getRange() {#getRange--}
```
public int[] getRange()
```


يحصل على النطاق.

**Returns:**
int[] - النطاق.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


يضبط النطاق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | النطاق. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


يرجع مصفوفة عنصر واحد من الفهرس المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس النطاق. |

**Returns:**
int[] - المصفوفة من `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


يحصل على نطاق العد لعناصر int بدءًا من start

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| start | int | البداية. |
| count | int | العدد. |
| delta | int | الفرق. |

**Returns:**
int[] - مصفوفة العناصر

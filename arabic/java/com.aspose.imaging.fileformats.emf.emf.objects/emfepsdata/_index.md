---
title: "EmfEpsData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EpsData هو حاوية لبيانات EPS"
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

كائن EpsData هو حاوية لبيانات EPS
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSizeData()](#getSizeData--) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد الحجم الكلي لهذا الكائن، بالبايت |
| [setSizeData(int value)](#setSizeData-int-) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد الحجم الكلي لهذا الكائن، بالبايت |
| [getVersion()](#getVersion--) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد مستوى لغة PostScript. |
| [setVersion(int value)](#setVersion-int-) | يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد مستوى لغة PostScript. |
| [getPoints()](#getPoints--) | يتم الحصول على أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات متوازي الأضلاع الناتج باستخدام ترميز FIX 28.4 بت |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | يتم الحصول على أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات متوازي الأضلاع الناتج باستخدام ترميز FIX 28.4 بت |
| [getPostScriptData()](#getPostScriptData--) | يتم الحصول على أو تعيين مصفوفة من البايتات لبيانات PostScript. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | يتم الحصول على أو تعيين مصفوفة من البايتات لبيانات PostScript. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد الحجم الكلي لهذا الكائن، بالبايت

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد الحجم الكلي لهذا الكائن، بالبايت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد مستوى لغة PostScript. يجب أن تكون هذه القيمة 0x00000001

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يتم الحصول على أو تعيين عدد صحيح غير موقع 32‑بت يحدد مستوى لغة PostScript. يجب أن تكون هذه القيمة 0x00000001

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


يتم الحصول على أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات متوازي الأضلاع الناتج باستخدام ترميز FIX 28.4 بت

الزاوية العليا اليسرى لمتوازي الأضلاع هي النقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى هي النقطة الثانية، والزاوية السفلى اليسرى هي النقطة الثالثة. يتم حساب الزاوية السفلى اليمنى لمتوازي الأضلاع من النقاط الثلاث الأولى (A، B، وC) باعتبارها متجهات.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


يتم الحصول على أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات متوازي الأضلاع الناتج باستخدام ترميز FIX 28.4 بت

الزاوية العليا اليسرى لمتوازي الأضلاع هي النقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى هي النقطة الثانية، والزاوية السفلى اليسرى هي النقطة الثالثة. يتم حساب الزاوية السفلى اليمنى لمتوازي الأضلاع من النقاط الثلاث الأولى (A، B، وC) باعتبارها متجهات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


يتم الحصول على أو تعيين مصفوفة من البايتات لبيانات PostScript. يمكن حساب طول هذه المصفوفة من حقل SizeData. قد تُستخدم هذه البيانات لتصوير صورة.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


يتم الحصول على أو تعيين مصفوفة من البايتات لبيانات PostScript. يمكن حساب طول هذه المصفوفة من حقل SizeData. قد تُستخدم هذه البيانات لتصوير صورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |


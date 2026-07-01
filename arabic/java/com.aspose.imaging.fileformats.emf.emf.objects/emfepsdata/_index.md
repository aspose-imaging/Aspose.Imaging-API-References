---
title: "EmfEpsData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EpsData هو حاوية لبيانات EPS"
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
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
| [getSizeData()](#getSizeData--) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد الحجم الكلي لهذا الكائن، بالبايت. |
| [setSizeData(int value)](#setSizeData-int-) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد الحجم الكلي لهذا الكائن، بالبايت. |
| [getVersion()](#getVersion--) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد مستوى لغة PostScript. |
| [setVersion(int value)](#setVersion-int-) | يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد مستوى لغة PostScript. |
| [getPoints()](#getPoints--) | يقوم بالحصول أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات المتوازي الأضلاع الناتج باستخدام تدوين FIX 28.4 بت. |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | يقوم بالحصول أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات المتوازي الأضلاع الناتج باستخدام تدوين FIX 28.4 بت. |
| [getPostScriptData()](#getPostScriptData--) | يقوم بالحصول أو تعيين مصفوفة من بايتات بيانات PostScript. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | يقوم بالحصول أو تعيين مصفوفة من بايتات بيانات PostScript. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد الحجم الكلي لهذا الكائن، بالبايت.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد الحجم الكلي لهذا الكائن، بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد مستوى لغة PostScript. يجب أن تكون هذه القيمة 0x00000001.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


يقوم بالحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد مستوى لغة PostScript. يجب أن تكون هذه القيمة 0x00000001.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


يقوم بالحصول أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات المتوازي الأضلاع الناتج باستخدام تدوين FIX 28.4 بت.

الزاوية العليا اليسرى للمتوازي الأضلاع هي النقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى هي النقطة الثانية، والزاوية السفلى اليسرى هي النقطة الثالثة. يتم حساب الزاوية السفلى اليمنى للمتوازي الأضلاع من النقاط الثلاث الأولى (A، B، و C) عن طريق معالجتها كمتجهات.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


يقوم بالحصول أو تعيين مصفوفة من ثلاثة كائنات Point28\_4 (القسم 2.2.23) التي تحدد إحداثيات المتوازي الأضلاع الناتج باستخدام تدوين FIX 28.4 بت.

الزاوية العليا اليسرى للمتوازي الأضلاع هي النقطة الأولى في هذه المصفوفة، والزاوية العليا اليمنى هي النقطة الثانية، والزاوية السفلى اليسرى هي النقطة الثالثة. يتم حساب الزاوية السفلى اليمنى للمتوازي الأضلاع من النقاط الثلاث الأولى (A، B، و C) عن طريق معالجتها كمتجهات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


يقوم بالحصول أو تعيين مصفوفة من بايتات بيانات PostScript. يمكن حساب طول هذه المصفوفة من حقل SizeData. قد تُستخدم هذه البيانات لتصوير صورة.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


يقوم بالحصول أو تعيين مصفوفة من بايتات بيانات PostScript. يمكن حساب طول هذه المصفوفة من حقل SizeData. قد تُستخدم هذه البيانات لتصوير صورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |


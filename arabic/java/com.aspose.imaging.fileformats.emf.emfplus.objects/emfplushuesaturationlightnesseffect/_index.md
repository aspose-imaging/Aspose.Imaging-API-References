---
title: "EmfPlusHueSaturationLightnessEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن HueSaturationLightnessEffect يحدد تعديلات على درجة اللون والتشبع والإضاءة لصورة."
type: docs
weight: 46
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushuesaturationlightnesseffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusHueSaturationLightnessEffect extends EmfPlusImageEffectsObjectType
```

كائن HueSaturationLightnessEffect يحدد تعديلات على درجة اللون، التشبع، والإضاءة لصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusHueSaturationLightnessEffect()](#EmfPlusHueSaturationLightnessEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHueLevel()](#getHueLevel--) | يحصل أو يحدد التعديل على درجة اللون. |
| [setHueLevel(int value)](#setHueLevel-int-) | يحصل أو يحدد التعديل على درجة اللون. |
| [getSaturationLevel()](#getSaturationLevel--) | يحصل أو يحدد التعديل على التشبع. |
| [setSaturationLevel(int value)](#setSaturationLevel-int-) | يحصل أو يحدد التعديل على التشبع. |
| [getLightnessLevel()](#getLightnessLevel--) | يحصل أو يعيّن المحدد لتعديل الإضاءة. |
| [setLightnessLevel(int value)](#setLightnessLevel-int-) | يحصل أو يعيّن المحدد لتعديل الإضاءة. |
### EmfPlusHueSaturationLightnessEffect() {#EmfPlusHueSaturationLightnessEffect--}
```
public EmfPlusHueSaturationLightnessEffect()
```


### getHueLevel() {#getHueLevel--}
```
public int getHueLevel()
```


يحصل أو يعيّن المحدد لتعديل اللون. -180 \\u2264 value < 0 القيم السالبة تحدد دورانًا باتجاه عقارب الساعة على عجلة الألوان. 0 قيمة 0 تحدد أن اللون يجب ألا يتغير. 0 < value \\u2264 180 القيم الموجبة تحدد دورانًا عكس اتجاه عقارب الساعة على عجلة الألوان.

القيمة: مستوى اللون.

**Returns:**
int
### setHueLevel(int value) {#setHueLevel-int-}
```
public void setHueLevel(int value)
```


يحصل أو يعيّن المحدد لتعديل اللون. -180 \\u2264 value < 0 القيم السالبة تحدد دورانًا باتجاه عقارب الساعة على عجلة الألوان. 0 قيمة 0 تحدد أن اللون يجب ألا يتغير. 0 < value \\u2264 180 القيم الموجبة تحدد دورانًا عكس اتجاه عقارب الساعة على عجلة الألوان.

القيمة: مستوى اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSaturationLevel() {#getSaturationLevel--}
```
public int getSaturationLevel()
```


يحصل أو يعيّن المحدد لتعديل التشبع. -100 \\u2264 value < 0 القيم السالبة تحدد تقليل التشبع. 0 قيمة 0 تحدد أن التشبع يجب ألا يتغير. 0 < value \\u2264 100 القيم الموجبة تحدد زيادة التشبع.

القيمة: مستوى التشبع.

**Returns:**
int
### setSaturationLevel(int value) {#setSaturationLevel-int-}
```
public void setSaturationLevel(int value)
```


يحصل أو يعيّن المحدد لتعديل التشبع. -100 \\u2264 value < 0 القيم السالبة تحدد تقليل التشبع. 0 قيمة 0 تحدد أن التشبع يجب ألا يتغير. 0 < value \\u2264 100 القيم الموجبة تحدد زيادة التشبع.

القيمة: مستوى التشبع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLightnessLevel() {#getLightnessLevel--}
```
public int getLightnessLevel()
```


يحصل أو يعيّن المحدد لتعديل الإضاءة. -100 \\u2264 value < 0 القيم السالبة تحدد تقليل الإضاءة. 0 قيمة 0 تحدد أن الإضاءة يجب ألا تتغير. 0 < value \\u2264 100 القيم الموجبة تحدد زيادة الإضاءة.

القيمة: مستوى الإضاءة.

**Returns:**
int
### setLightnessLevel(int value) {#setLightnessLevel-int-}
```
public void setLightnessLevel(int value)
```


يحصل أو يعيّن المحدد لتعديل الإضاءة. -100 \\u2264 value < 0 القيم السالبة تحدد تقليل الإضاءة. 0 قيمة 0 تحدد أن الإضاءة يجب ألا تتغير. 0 < value \\u2264 100 القيم الموجبة تحدد زيادة الإضاءة.

القيمة: مستوى الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


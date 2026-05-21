---
title: "EmfPlusHueSaturationLightnessEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن HueSaturationLightnessEffect يحدد تعديلات على درجة اللون والتشبع والإضاءة لصورة."
type: docs
weight: 46
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushuesaturationlightnesseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusHueSaturationLightnessEffect extends EmfPlusImageEffectsObjectType
```

كائن HueSaturationLightnessEffect يحدد التعديلات على درجة اللون، التشبع، والإضاءة لصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusHueSaturationLightnessEffect()](#EmfPlusHueSaturationLightnessEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHueLevel()](#getHueLevel--) | الحصول أو تعيين يحدد التعديل على درجة اللون. |
| [setHueLevel(int value)](#setHueLevel-int-) | الحصول أو تعيين يحدد التعديل على درجة اللون. |
| [getSaturationLevel()](#getSaturationLevel--) | الحصول أو تعيين يحدد التعديل على التشبع. |
| [setSaturationLevel(int value)](#setSaturationLevel-int-) | الحصول أو تعيين يحدد التعديل على التشبع. |
| [getLightnessLevel()](#getLightnessLevel--) | الحصول أو تعيين يحدد التعديل على الإضاءة. |
| [setLightnessLevel(int value)](#setLightnessLevel-int-) | الحصول أو تعيين يحدد التعديل على الإضاءة. |
### EmfPlusHueSaturationLightnessEffect() {#EmfPlusHueSaturationLightnessEffect--}
```
public EmfPlusHueSaturationLightnessEffect()
```


### getHueLevel() {#getHueLevel--}
```
public int getHueLevel()
```


الحصول أو تعيين يحدد التعديل على درجة اللون. -180 \\u2264 القيمة < 0 القيم السلبية تحدد دورانًا باتجاه عقارب الساعة على عجلة اللون. 0 قيمة 0 تحدد أن درجة اللون MUST NOT تتغير. 0 < القيمة \\u2264 180 القيم الإيجابية تحدد دورانًا عكس اتجاه عقارب الساعة على عجلة اللون.

القيمة: مستوى درجة اللون.

**Returns:**
int
### setHueLevel(int value) {#setHueLevel-int-}
```
public void setHueLevel(int value)
```


الحصول أو تعيين يحدد التعديل على درجة اللون. -180 \\u2264 القيمة < 0 القيم السلبية تحدد دورانًا باتجاه عقارب الساعة على عجلة اللون. 0 قيمة 0 تحدد أن درجة اللون MUST NOT تتغير. 0 < القيمة \\u2264 180 القيم الإيجابية تحدد دورانًا عكس اتجاه عقارب الساعة على عجلة اللون.

القيمة: مستوى درجة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSaturationLevel() {#getSaturationLevel--}
```
public int getSaturationLevel()
```


الحصول أو تعيين يحدد التعديل على التشبع. -100 \\u2264 القيمة < 0 القيم السلبية تحدد انخفاض التشبع. 0 قيمة 0 تحدد أن التشبع MUST NOT يتغير. 0 < القيمة \\u2264 100 القيم الإيجابية تحدد زيادة التشبع.

القيمة: مستوى التشبع.

**Returns:**
int
### setSaturationLevel(int value) {#setSaturationLevel-int-}
```
public void setSaturationLevel(int value)
```


الحصول أو تعيين يحدد التعديل على التشبع. -100 \\u2264 القيمة < 0 القيم السلبية تحدد انخفاض التشبع. 0 قيمة 0 تحدد أن التشبع MUST NOT يتغير. 0 < القيمة \\u2264 100 القيم الإيجابية تحدد زيادة التشبع.

القيمة: مستوى التشبع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLightnessLevel() {#getLightnessLevel--}
```
public int getLightnessLevel()
```


الحصول أو تعيين يحدد التعديل على الإضاءة. -100 \\u2264 القيمة < 0 القيم السلبية تحدد انخفاض الإضاءة. 0 قيمة 0 تحدد أن الإضاءة MUST NOT تتغير. 0 < القيمة \\u2264 100 القيم الإيجابية تحدد زيادة الإضاءة.

القيمة: مستوى الإضاءة.

**Returns:**
int
### setLightnessLevel(int value) {#setLightnessLevel-int-}
```
public void setLightnessLevel(int value)
```


الحصول أو تعيين يحدد التعديل على الإضاءة. -100 \\u2264 القيمة < 0 القيم السلبية تحدد انخفاض الإضاءة. 0 قيمة 0 تحدد أن الإضاءة MUST NOT تتغير. 0 < القيمة \\u2264 100 القيم الإيجابية تحدد زيادة الإضاءة.

القيمة: مستوى الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |


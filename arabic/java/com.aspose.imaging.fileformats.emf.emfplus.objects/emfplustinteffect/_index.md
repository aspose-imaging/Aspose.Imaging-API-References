---
title: "EmfPlusTintEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن TintEffect يحدد إضافة الأسود أو الأبيض إلى درجة لون محددة في الصورة."
type: docs
weight: 79
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

كائن TintEffect يحدد إضافة الأسود أو الأبيض إلى درجة لون محددة في الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHue()](#getHue--) | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد درجة اللون التي يُطبق عليها تأثير الصبغة. |
| [setHue(int value)](#setHue-int-) | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد درجة اللون التي يُطبق عليها تأثير الصبغة. |
| [getAmount()](#getAmount--) | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد مقدار تعزيز أو إضعاف درجة اللون. |
| [setAmount(int value)](#setAmount-int-) | يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد مقدار تعزيز أو إضعاف درجة اللون. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد درجة اللون التي يُطبق عليها تأثير الصبغة. -180 \\u2264 value < 0 اللون عند دوران عكس عقارب الساعة المحدد لعجلة الألوان، بدءًا من اللون الأزرق. 0 قيمة 0 تحدد اللون الأزرق على عجلة الألوان. 0 < value \\u2264 180 اللون عند دوران مع عقارب الساعة المحدد لعجلة الألوان، بدءًا من اللون الأزرق

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد درجة اللون التي يُطبق عليها تأثير الصبغة. -180 \\u2264 value < 0 اللون عند دوران عكس عقارب الساعة المحدد لعجلة الألوان، بدءًا من اللون الأزرق. 0 قيمة 0 تحدد اللون الأزرق على عجلة الألوان. 0 < value \\u2264 180 اللون عند دوران مع عقارب الساعة المحدد لعجلة الألوان، بدءًا من اللون الأزرق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد مقدار تعزيز أو إضعاف درجة اللون. -100 \\u2264 value < 0 القيم السلبية تحدد مقدار إضعاف درجة اللون، وهو ما يعادل إضافة اللون الأسود. 0 قيمة 0 تحدد أن الصبغة لا يجب أن تتغير. 0 < value \\u2264 100 القيم الإيجابية تحدد مقدار تعزيز درجة اللون، وهو ما يعادل إضافة اللون الأبيض.

القيمة: المقدار.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


يحصل أو يضبط عددًا صحيحًا موقّعًا 32-بت يحدد مقدار تعزيز أو إضعاف درجة اللون. -100 \\u2264 value < 0 القيم السلبية تحدد مقدار إضعاف درجة اللون، وهو ما يعادل إضافة اللون الأسود. 0 قيمة 0 تحدد أن الصبغة لا يجب أن تتغير. 0 < value \\u2264 100 القيم الإيجابية تحدد مقدار تعزيز درجة اللون، وهو ما يعادل إضافة اللون الأبيض.

القيمة: المقدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


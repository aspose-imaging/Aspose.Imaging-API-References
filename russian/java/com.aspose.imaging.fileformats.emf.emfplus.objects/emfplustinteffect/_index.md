---
title: "EmfPlusTintEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект TintEffect указывает добавление чёрного или белого к указанному оттенку изображения."
type: docs
weight: 79
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

Объект TintEffect указывает добавление чёрного или белого к указанному оттенку изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getHue()](#getHue--) | Получает или задает 32-битное знаковое целое, которое указывает оттенок, к которому применяется эффект тонирования. |
| [setHue(int value)](#setHue-int-) | Получает или задает 32-битное знаковое целое, которое указывает оттенок, к которому применяется эффект тонирования. |
| [getAmount()](#getAmount--) | Получает или задает 32-битное знаковое целое, которое указывает степень усиления или ослабления оттенка. |
| [setAmount(int value)](#setAmount-int-) | Получает или задает 32-битное знаковое целое, которое указывает степень усиления или ослабления оттенка. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Получает или задает 32-битное знаковое целое, которое указывает оттенок, к которому применяется эффект тонирования. -180 \\u2264 value < 0 Цвет при заданном вращении цветового круга против часовой стрелки, начиная с синего. 0 Значение 0 указывает синий цвет на цветовом круге. 0 < value \\u2264 180 Цвет при заданном вращении цветового круга по часовой стрелке, начиная с синего.

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает оттенок, к которому применяется эффект тонирования. -180 \\u2264 value < 0 Цвет при заданном вращении цветового круга против часовой стрелки, начиная с синего. 0 Значение 0 указывает синий цвет на цветовом круге. 0 < value \\u2264 180 Цвет при заданном вращении цветового круга по часовой стрелке, начиная с синего.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Получает или задает 32-битное знаковое целое, которое указывает степень усиления или ослабления оттенка. -100 \\u2264 value < 0 Отрицательные значения указывают, насколько оттенок ослаблен, что эквивалентно добавлению черного. 0 Значение 0 указывает, что тонирование НЕ ДОЛЖНО изменяться. 0 < value \\u2264 100 Положительные значения указывают, насколько оттенок усилен, что эквивалентно добавлению белого.

Value: Величина.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает степень усиления или ослабления оттенка. -100 \\u2264 value < 0 Отрицательные значения указывают, насколько оттенок ослаблен, что эквивалентно добавлению черного. 0 Значение 0 указывает, что тонирование НЕ ДОЛЖНО изменяться. 0 < value \\u2264 100 Положительные значения указывают, насколько оттенок усилен, что эквивалентно добавлению белого.

Value: Величина.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


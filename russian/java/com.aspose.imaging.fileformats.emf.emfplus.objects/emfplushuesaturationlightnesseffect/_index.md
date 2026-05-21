---
title: "EmfPlusHueSaturationLightnessEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект HueSaturationLightnessEffect определяет корректировки оттенка, насыщенности и яркости изображения."
type: docs
weight: 46
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushuesaturationlightnesseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusHueSaturationLightnessEffect extends EmfPlusImageEffectsObjectType
```

Объект HueSaturationLightnessEffect определяет коррекцию оттенка, насыщенности и яркости изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusHueSaturationLightnessEffect()](#EmfPlusHueSaturationLightnessEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getHueLevel()](#getHueLevel--) | Получает или задает корректировку оттенка. |
| [setHueLevel(int value)](#setHueLevel-int-) | Получает или задает корректировку оттенка. |
| [getSaturationLevel()](#getSaturationLevel--) | Получает или задает корректировку насыщенности. |
| [setSaturationLevel(int value)](#setSaturationLevel-int-) | Получает или задает корректировку насыщенности. |
| [getLightnessLevel()](#getLightnessLevel--) | Получает или задает корректировку яркости. |
| [setLightnessLevel(int value)](#setLightnessLevel-int-) | Получает или задает корректировку яркости. |
### EmfPlusHueSaturationLightnessEffect() {#EmfPlusHueSaturationLightnessEffect--}
```
public EmfPlusHueSaturationLightnessEffect()
```


### getHueLevel() {#getHueLevel--}
```
public int getHueLevel()
```


Получает или задает корректировку оттенка. -180 \\u2264 value < 0 Отрицательные значения указывают вращение по часовой стрелке на цветовом круге. 0 Значение 0 указывает, что оттенок НЕ ДОЛЖЕН изменяться. 0 < value \\u2264 180 Положительные значения указывают вращение против часовой стрелки на цветовом круге.

Значение: уровень оттенка.

**Returns:**
int
### setHueLevel(int value) {#setHueLevel-int-}
```
public void setHueLevel(int value)
```


Получает или задает корректировку оттенка. -180 \\u2264 value < 0 Отрицательные значения указывают вращение по часовой стрелке на цветовом круге. 0 Значение 0 указывает, что оттенок НЕ ДОЛЖЕН изменяться. 0 < value \\u2264 180 Положительные значения указывают вращение против часовой стрелки на цветовом круге.

Значение: уровень оттенка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSaturationLevel() {#getSaturationLevel--}
```
public int getSaturationLevel()
```


Получает или задает корректировку насыщенности. -100 \\u2264 value < 0 Отрицательные значения указывают снижение насыщенности. 0 Значение 0 указывает, что насыщенность НЕ ДОЛЖНА изменяться. 0 < value \\u2264 100 Положительные значения указывают увеличение насыщенности.

Значение: уровень насыщенности.

**Returns:**
int
### setSaturationLevel(int value) {#setSaturationLevel-int-}
```
public void setSaturationLevel(int value)
```


Получает или задает корректировку насыщенности. -100 \\u2264 value < 0 Отрицательные значения указывают снижение насыщенности. 0 Значение 0 указывает, что насыщенность НЕ ДОЛЖНА изменяться. 0 < value \\u2264 100 Положительные значения указывают увеличение насыщенности.

Значение: уровень насыщенности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLightnessLevel() {#getLightnessLevel--}
```
public int getLightnessLevel()
```


Получает или задает корректировку яркости. -100 \\u2264 value < 0 Отрицательные значения указывают снижение яркости. 0 Значение 0 указывает, что яркость НЕ ДОЛЖНА изменяться. 0 < value \\u2264 100 Положительные значения указывают увеличение яркости.

Значение: уровень яркости.

**Returns:**
int
### setLightnessLevel(int value) {#setLightnessLevel-int-}
```
public void setLightnessLevel(int value)
```


Получает или задает корректировку яркости. -100 \\u2264 value < 0 Отрицательные значения указывают снижение яркости. 0 Значение 0 указывает, что яркость НЕ ДОЛЖНА изменяться. 0 < value \\u2264 100 Положительные значения указывают увеличение яркости.

Значение: уровень яркости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


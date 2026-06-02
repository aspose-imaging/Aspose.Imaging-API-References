---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект BrightnessContrastEffect указывает расширение или сжатие самых светлых и самых тёмных областей изображения."
type: docs
weight: 23
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

Объект BrightnessContrastEffect указывает расширение или сжатие самых светлых и самых тёмных областей изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Получает или задает 32-битное знаковое целое, определяющее уровень яркости. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Получает или задает 32-битное знаковое целое, определяющее уровень яркости. |
| [getContrastLevel()](#getContrastLevel--) | Получает или задает 32-битное знаковое целое, определяющее уровень контрастности. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Получает или задает 32-битное знаковое целое, определяющее уровень контрастности. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Получает или задает 32-битное знаковое целое, которое указывает уровень яркости. Это значение ДОЛЖНО быть в диапазоне от -255 до 255, с эффектами следующим образом: -255 \\u2264 value < 0 По мере уменьшения значения яркость изображения ДОЛЖНА уменьшаться. 0 Значение 0 указывает, что яркость НЕ ДОЛЖНА изменяться. 0 < value \\u2264 255 По мере увеличения значения яркость изображения ДОЛЖНА увеличиваться.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает уровень яркости. Это значение ДОЛЖНО быть в диапазоне от -255 до 255, с эффектами следующим образом: -255 \\u2264 value < 0 По мере уменьшения значения яркость изображения ДОЛЖНА уменьшаться. 0 Значение 0 указывает, что яркость НЕ ДОЛЖНА изменяться. 0 < value \\u2264 255 По мере увеличения значения яркость изображения ДОЛЖНА увеличиваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Получает или задает 32-битное знаковое целое, которое указывает уровень контрастности. Это значение ДОЛЖНО быть в диапазоне от -100 до 100, с эффектами следующим образом: -100 \\u2264 value < 0 По мере уменьшения значения контрастность изображения ДОЛЖНА уменьшаться. 0 Значение 0 указывает, что контрастность НЕ ДОЛЖНА изменяться. 0 < value \\u2264 100 По мере увеличения значения контрастность изображения ДОЛЖНА увеличиваться.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает уровень контрастности. Это значение ДОЛЖНО быть в диапазоне от -100 до 100, с эффектами следующим образом: -100 \\u2264 value < 0 По мере уменьшения значения контрастность изображения ДОЛЖНА уменьшаться. 0 Значение 0 указывает, что контрастность НЕ ДОЛЖНА изменяться. 0 < value \\u2264 100 По мере увеличения значения контрастность изображения ДОЛЖНА увеличиваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


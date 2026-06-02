---
title: "FeatheringSettings"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс настроек растушевки."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

Класс настроек растушевки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Инициализирует новый экземпляр класса [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает размер растушевки. |
| [setSize(int value)](#setSize-int-) | Устанавливает размер растушевки. |
| [getMode()](#getMode--) | Получает режим алгоритма растушевки. |
| [setMode(int value)](#setMode-int-) | Устанавливает режим алгоритма растушевки. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Создайте новую маску с помощью инструмента magic wand, основанную на тоне и цвете пикселя (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Объедините существующую маску с указанной, созданной инструментом magic wand.
            .union(new MagicWandSettings(416, 387))
            // Инвертируйте существующую маску
            .invert()
            // Вычтите указанную маску, созданную инструментом magic wand с заданным порогом, из существующей.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Вычтите четыре указанных прямоугольных маски из существующей маски одну за другой.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Смягчите маску с указанными настройками.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Примените маску к изображению
            .apply();

    // Сохранить изображение
    image.save(outputFilePath);
}

```

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Инициализирует новый экземпляр класса [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

### getSize() {#getSize--}
```
public final int getSize()
```


Получает размер растушевки.

Значение: Размер кисти растушевки в пикселях.

**Returns:**
int - размер растушевки.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Устанавливает размер растушевки.

Значение: Размер кисти растушевки в пикселях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | размер растушевки. |

### getMode() {#getMode--}
```
public final int getMode()
```


Получает режим алгоритма растушевки.

Значение: Режим алгоритма растушевки.

**Returns:**
int - режим алгоритма растушевки.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Устанавливает режим алгоритма растушевки.

Значение: Режим алгоритма растушевки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | режим алгоритма растушевки. |


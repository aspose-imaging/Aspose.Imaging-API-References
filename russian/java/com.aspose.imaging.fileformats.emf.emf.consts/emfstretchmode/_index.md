---
title: "EmfStretchMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление StretchMode используется для указания того, как цветовые данные добавляются в растровые изображения или удаляются из них при растягивании или сжатии."
type: docs
weight: 43
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

Перечисление StretchMode используется для указания того, как цветовые данные добавляются в растровые изображения или удаляются из них при растягивании или сжатии.
## Поля

| Поле | Описание |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Выполняет логическую операцию AND, используя цветовые значения для удалённых и существующих пикселей. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Выполняет логическую операцию OR, используя цветовые значения для удалённых и существующих пикселей. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Удаляет пиксели. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Отображает пиксели из исходного прямоугольника в блоки пикселей в целевом прямоугольнике. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Выполняет логическую операцию И, используя цветовые значения для удалённых и существующих пикселей. Если растровое изображение монохромное, этот режим сохраняет чёрные пиксели за счёт белых пикселей

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Выполняет логическую операцию ИЛИ, используя цветовые значения для удалённых и существующих пикселей. Если растровое изображение монохромное, этот режим сохраняет белые пиксели за счёт чёрных пикселей.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Удаляет пиксели. Этот режим удаляет все устранённые линии пикселей, не пытаясь сохранять их информацию.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Отображает пиксели из исходного прямоугольника в блоки пикселей в целевом прямоугольнике. Средний цвет блока целевых пикселей приближён к цвету исходных пикселей.


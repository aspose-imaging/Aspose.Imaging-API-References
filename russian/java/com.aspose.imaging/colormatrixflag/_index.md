---
title: "ColorMatrixFlag"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает типы изображений и цветов, которые будут затронуты настройками коррекции цвета и градаций серого."
type: docs
weight: 27
url: /ru/java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Указывает типы изображений и цветов, которые будут затронуты настройками коррекции цвета и градаций серого у [ImageAttributes](../../com.aspose.imaging/imageattributes).
## Поля

| Поле | Описание |
| --- | --- |
| [Default](#Default) | Все значения цветов, включая серые оттенки, корректируются одной и той же матрицей коррекции цвета. |
| [SkipGrays](#SkipGrays) | Все цвета корректируются, но серые оттенки не корректируются. |
| [AltGrays](#AltGrays) | Корректируются только серые оттенки. |
### Default {#Default}
```
public static final int Default
```


Все значения цветов, включая серые оттенки, корректируются одной и той же матрицей коррекции цвета.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Все цвета корректируются, но серые оттенки не корректируются. Серый оттенок — любой цвет, у которого одинаковые значения компонентов красного, зелёного и синего.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Корректируются только серые оттенки.


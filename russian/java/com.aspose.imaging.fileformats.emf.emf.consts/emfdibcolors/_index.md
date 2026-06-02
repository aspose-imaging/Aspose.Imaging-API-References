---
title: "EmfDibColors"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление DIBColors определяет, как интерпретировать значения в таблице цветов DIB."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

Перечисление DIBColors определяет, как интерпретировать значения в таблице цветов DIB.
## Поля

| Поле | Описание |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | Таблица цветов содержит буквальные значения RGB. |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | Таблица цветов состоит из массива 16-битных индексов в объект LogPalette (раздел 2.2.17), который в данный момент определён в контексте устройства воспроизведения. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Таблица цветов не существует. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


Таблица цветов содержит буквальные значения RGB.

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


Таблица цветов состоит из массива 16-битных индексов в объект LogPalette (раздел 2.2.17), который в данный момент определён в контексте устройства воспроизведения.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Таблица цветов не существует. Пиксели в DIB являются индексами в текущую логическую палитру в контексте устройства воспроизведения.


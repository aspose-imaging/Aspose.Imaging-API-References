---
title: "WmfColorUsageEnum"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление ColorUsage указывает, существует ли таблица цветов в независимом от устройства bitmap (DIB) и как интерпретировать её значения."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

Перечисление ColorUsage указывает, существует ли таблица цветов в независимом от устройства битмапе (DIB) и как интерпретировать её значения.
## Поля

| Поле | Описание |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | Таблица цветов содержит значения RGB, указанные объектами RGBQuad (раздел 2.2.2.20). |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | Таблица цветов содержит 16-битные индексы в текущую логическую палитру в контексте устройства воспроизведения. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Таблица цветов не существует. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


Таблица цветов содержит значения RGB, указанные объектами RGBQuad (раздел 2.2.2.20).

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


Таблица цветов содержит 16-битные индексы в текущую логическую палитру в контексте устройства воспроизведения.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Таблица цветов не существует. Пиксели в DIB являются индексами в текущую логическую палитру в контексте устройства воспроизведения.


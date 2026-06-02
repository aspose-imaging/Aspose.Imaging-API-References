---
title: "WmfPitchFont"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление PitchFont определяет значения, используемые для указания характеристик шрифта."
type: docs
weight: 29
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfpitchfont/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPitchFont extends System.Enum
```

Перечисление PitchFont определяет значения, используемые для указания характеристик шрифта. Эти значения указывают, имеют ли символы шрифта фиксированную или переменную ширину, либо шаг.
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_PITCH](#DEFAULT-PITCH) | Шаг по умолчанию, зависящий от реализации. |
| [FIXED_PITCH](#FIXED-PITCH) | Фиксированный шаг, что означает, что все символы шрифта занимают одинаковую ширину при выводе в строке. |
| [VARIABLE_PITCH](#VARIABLE-PITCH) | Переменный шаг, что означает, что символы шрифта занимают ширины, пропорциональные фактическим ширинам глифов при выводе в строке. |
### DEFAULT_PITCH {#DEFAULT-PITCH}
```
public static final byte DEFAULT_PITCH
```


Шаг по умолчанию, зависящий от реализации.

### FIXED_PITCH {#FIXED-PITCH}
```
public static final byte FIXED_PITCH
```


Фиксированный шаг, что означает, что все символы шрифта занимают одинаковую ширину при выводе в строке.

### VARIABLE_PITCH {#VARIABLE-PITCH}
```
public static final byte VARIABLE_PITCH
```


Переменный шаг, что означает, что символы шрифта занимают ширины, пропорциональные фактическим ширинам глифов при выводе в строке. Например, символы "i" и пробел обычно имеют значительно меньшую ширину, чем символы "W" или "O".


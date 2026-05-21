---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Флаги DriverStringOptions указывают свойства позиционирования и рендеринга графического текста."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

Флаги DriverStringOptions определяют свойства позиционирования и рендеринга графического текста. Эти флаги можно комбинировать для указания нескольких параметров.

--------------------

Вывод графического текста указывается в записях [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring)
## Поля

| Поле | Описание |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | Если установлен, позиции глифов символов ДОЛЖНЫ быть указаны в таблице поиска карты символов. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | Если установлен, строка ДОЛЖНА отображаться вертикально. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | Если установлен, позиции глифов символов ДОЛЖНЫ рассчитываться относительно позиции первого глифа. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | Если установлен, должно использоваться меньше памяти для кэширования сглаженных глифов, что приводит к менее качественному рендерингу текста. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


Если установлен, позиции глифов символов ДОЛЖНЫ быть указаны в таблице поиска карты символов. Если сброшено, позиции глифов ДОЛЖНЫ получаться из массива координат.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


Если установлен, строка ДОЛЖНА отображаться вертикально. Если сброшено, строка ДОЛЖНА отображаться горизонтально.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


Если установлен, позиции глифов символов ДОЛЖНЫ рассчитываться относительно позиции первого глифа. Если сброшено, позиции глифов ДОЛЖНЫ получаться из массива координат.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


Если установлен, должно использоваться меньше памяти для кэширования сглаженных глифов, что приводит к менее качественному рендерингу текста. Если сброшено, должно использоваться больше памяти, что приводит к более качественному рендерингу текста.


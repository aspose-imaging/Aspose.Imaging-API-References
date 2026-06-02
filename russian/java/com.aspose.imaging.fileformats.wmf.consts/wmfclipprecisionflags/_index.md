---
title: "WmfClipPrecisionFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Флаги ClipPrecision указывают точность отсечения, определяющую, как отсекать символы, частично находящиеся за пределами области отсечения."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

Флаги ClipPrecision указывают точность отсечения, определяющую, как отсекать символы, частично находящиеся за пределами области отсечения. Эти флаги можно комбинировать для указания нескольких вариантов.
## Поля

| Поле | Описание |
| --- | --- |
| [Default](#Default) | Указывает, что необходимо использовать отсечение по умолчанию. |
| [Character](#Character) | Это значение НЕ ДОЛЖНО использоваться. |
| [Stroke](#Stroke) | Это значение МОЖЕТ быть возвращено при перечислении растровых, TrueType и векторных шрифтов. |
| [LhAngles](#LhAngles) | Это значение используется для управления вращением шрифтов, как указано ниже: - Если установлено, вращение всех шрифтов ДОЛЖНО определяться ориентацией системы координат; то есть, является ли ориентация левосторонней или правосторонней. |
| [TtAlways](#TtAlways) | Это значение НЕ ДОЛЖНО [34] использоваться. |
| [DfaDisable](#DfaDisable) | Это значение указывает, что ассоциация шрифтов ДОЛЖНА [35] быть отключена. |
| [Embedded](#Embedded) | Это значение указывает, что встраивание шрифтов ДОЛЖНО использоваться для отображения содержимого документа; встроенные шрифты доступны только для чтения. |
### Default {#Default}
```
public static final byte Default
```


Указывает, что необходимо использовать отсечение по умолчанию.

### Character {#Character}
```
public static final byte Character
```


Это значение НЕ ДОЛЖНО использоваться.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Это значение МОЖЕТ быть возвращено при перечислении растровых, TrueType и векторных шрифтов. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 и Windows XP: это значение всегда возвращается при перечислении шрифтов.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Это значение используется для управления вращением шрифтов, как указано ниже: - Если установлено, вращение всех шрифтов ДОЛЖНО определяться ориентацией системы координат; то есть, является ли ориентация левосторонней или правосторонней. - Если сброшено, шрифты устройства ДОЛЖНЫ вращаться против часовой стрелки, но вращение остальных шрифтов ДОЛЖНО определяться ориентацией системы координат.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Это значение НЕ ДОЛЖНО [34] использоваться. [34] Это значение игнорируется в следующих версиях Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Это значение указывает, что ассоциация шрифтов ДОЛЖНА [35] быть отключена. [35] Это значение не поддерживается в Windows 95, Windows 98 и Windows Millennium Edition. Ассоциация шрифтов отключена в Windows 2000, Windows XP и Windows Server 2003. Это значение игнорируется в следующих версиях Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Это значение указывает, что встраивание шрифтов ДОЛЖНО использоваться для отображения содержимого документа; встроенные шрифты доступны только для чтения.


---
title: WmfClipPrecisionFlags
second_title: Справочник по Aspose.Imaging for .NET API
description: ClipPrecision Флаги задают точность отсечения которая определяет как обрезать символы которые частично находятся за пределами области отсечения. Эти флаги можно комбинировать для указания нескольких параметров.
type: docs
weight: 8130
url: /ru/net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
## WmfClipPrecisionFlags enumeration

ClipPrecision Флаги задают точность отсечения, которая определяет, как обрезать символы, которые частично находятся за пределами области отсечения. Эти флаги можно комбинировать для указания нескольких параметров.

```csharp
[Flags]
public enum WmfClipPrecisionFlags : byte
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Default | `0` | Указывает, что ДОЛЖНО использоваться отсечение по умолчанию. |
| Character | `1` | Это значение НЕ ДОЛЖНО использоваться. |
| Stroke | `2` | Это значение МОЖЕТ быть возвращено при перечислении растровых, TrueType и векторных шрифтов. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 и Windows XP:Это значение всегда возвращается при перечислении шрифтов. ) |
| LhAngles | `10` | Это значение используется для управления поворотом шрифта следующим образом: - Если установлено, поворот для всех шрифтов ДОЛЖЕН определяться ориентацией системы координат; то есть, является ли ориентация левосторонней или правосторонней. - Если флажок не установлен, шрифты устройства ДОЛЖНЫ вращаться против часовой стрелки, но поворот других шрифтов ДОЛЖЕН определяться ориентацией системы координат . |
| TtAlways | `20` | Это значение НЕ ДОЛЖНО [34] использоваться. [34] Это значение игнорируется в следующих версиях Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| DfaDisable | `40` | Это значение указывает, что ассоциацию шрифтов СЛЕДУЕТ [35] отключить. [35] Это значение не поддерживается в Windows 95, Windows 98 и Windows Millennium Edition. Ассоциация шрифтов отключена в Windows 2000, Windows XP и Windows Server 2003. Это значение игнорируется в следующих версиях Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| Embedded | `80` | Это значение указывает, что встраивание шрифта ДОЛЖНО использоваться для визуализации документа содержимого; встроенные шрифты доступны только для чтения. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
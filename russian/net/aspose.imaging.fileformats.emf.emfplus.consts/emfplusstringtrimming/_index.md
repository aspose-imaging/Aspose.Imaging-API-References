---
title: EmfPlusStringTrimming
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление StringTrimming определяет как обрезать символы из строки которая слишком велика для прямоугольника текстового макета.
type: docs
weight: 5090
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/
---
## EmfPlusStringTrimming enumeration

Перечисление StringTrimming определяет, как обрезать символы из строки, которая слишком велика для прямоугольника текстового макета.

```csharp
public enum EmfPlusStringTrimming
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| StringTrimmingNone | `0` | Указывает, что обрезка не выполняется. |
| StringTrimmingCharacter | `1` | Указывает, что строка разрывается на границе последнего символа внутри прямоугольника макета. Это значение по умолчанию. |
| StringTrimmingWord | `2` | Указывает, что строка разрывается на границе последнего слова, находящегося внутри прямоугольника макета. |
| StringTrimmingEllipsisCharacter | `3` | Указывает, что строка разрывается на границе последнего символа, находящегося внутри прямоугольника макета, и после символа вставляется многоточие (...). |
| StringTrimmingEllipsisWord | `4` | Указывает, что строка прерывается на границе последнего слова, находящегося внутри прямоугольника макета, и после слова вставляется многоточие (...). |
| StringTrimmingEllipsisPath | `5` | Указывает, что центр удаляется из строки и заменяется многоточием. Алгоритм сохраняет как можно большую часть последней части строки. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

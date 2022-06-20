---
title: EmfPlusStringFormatFlags
second_title: Справочник по Aspose.Imaging for .NET API
description: Флаги StringFormat определяют параметры макета графического текста включая направление отсечение и обработку шрифтов. Эти флаги можно комбинировать для указания нескольких параметров.
type: docs
weight: 5080
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
## EmfPlusStringFormatFlags enumeration

Флаги StringFormat определяют параметры макета графического текста, включая направление, отсечение и обработку шрифтов. Эти флаги можно комбинировать для указания нескольких параметров.

```csharp
[Flags]
public enum EmfPlusStringFormatFlags : uint
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| StringFormatDirectionRightToLeft | `1` | Если установлено, порядок чтения строки ДОЛЖЕН быть справа налево. Для горизонтального текста это означает, что символы читаются справа налево. Для вертикального текста это означает, что столбцы читаются справа налево. Если текст четкий, то горизонтальный или вертикальный текст ДОЛЖЕН читаться слева направо. |
| StringFormatDirectionVertical | `2` | Если установлено, отдельные строки текста ДОЛЖНЫ отображаться на устройстве отображения вертикально. Если флажок не установлен, отдельные строки текста СЛЕДУЕТ рисовать горизонтально, при этом каждая новая строка должна располагаться ниже предыдущей строки. |
| StringFormatNoFitBlackBox | `4` | Если установлено, части символов ДОЛЖНЫ быть разрешены для нависания над прямоугольником макета текста. Если флажок установлен, символы, которые выходят за границы прямоугольника текстового макета, ДОЛЖНЫ быть перемещены, чтобы избежать выступания. Курсив, "f" является примером символа, который может иметь выступающие части. |
| StringFormatDisplayFormatControl | `20` | Если установлено, управляющие символы ДОЛЖНЫ появляться в выводе как репрезентативные глифы Unicode. |
| StringFormatNoFontFallback | `400` | Если установлено, СЛЕДУЕТ использовать альтернативный шрифт для символов, которые не поддерживаются в запрошенном шрифте. Если флажок не установлен, символ, отсутствующий в запрошенном шрифте, ДОЛЖЕН отображаться как символ "отсутствует шрифт", который МОЖЕТ быть открытым квадратом. |
| StringFormatMeasureTrailingSpaces | `800` | Если установлено, пробел в конце каждой строки ДОЛЖЕН быть включен в измерения длины строки. Если флажок не установлен, пробел в конце каждой строки ДОЛЖЕН быть исключен из измерений длины строки. |
| StringFormatNoWrap | `1000` | Если установлено, строка, выходящая за конец прямоугольника текстового макета, НЕ ДОЛЖНА переноситься на следующую строку. Если этот параметр не установлен, строка, выходящая за пределы прямоугольника текстового макета, ДОЛЖНА быть разорвана на границе последнего слова внутри ограничивающего прямоугольника, а оставшаяся часть строки ДОЛЖНА быть перенесена на следующую строку. |
| StringFormatLineLimit | `2000` | Если установлено, целые строки текста ДОЛЖНЫ выводиться и НЕ ДОЛЖНЫ обрезаться прямоугольником макета строки. Если флажок установлен, макет текста ДОЛЖЕН продолжаться до тех пор, пока не будут выведены все строки или пока дополнительные строки не будут видны в результате обрезки. Этот флаг может использоваться либо для запрета, либо для разрешения частичного закрытия строки текста прямоугольником макета, высота которого не кратна высоте строки. Чтобы весь текст был виден, прямоугольник макета должен быть не меньше высоты одной строки. |
| StringFormatNoClip | `4000` | Если установлено, СЛЕДУЕТ отображать текст, выходящий за пределы прямоугольника макета строки. Если флажок установлен, весь текст, выходящий за пределы прямоугольника макета, ДОЛЖЕН быть обрезан. |
| StringFormatBypassGdi | `80000000` | Этот флаг МОЖЕТ использоваться для указания специфичного для реализации процесса рендеринга текста. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
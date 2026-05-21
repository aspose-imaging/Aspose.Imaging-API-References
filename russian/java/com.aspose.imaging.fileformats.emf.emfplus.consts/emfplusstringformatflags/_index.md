---
title: "EmfPlusStringFormatFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Флаги StringFormat определяют параметры размещения графического текста, включая направление, обрезку и обработку шрифтов."
type: docs
weight: 50
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

Флаги StringFormat определяют параметры размещения графического текста, включая направление, обрезку и обработку шрифтов. Эти флаги можно комбинировать для указания нескольких параметров.
## Поля

| Поле | Описание |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Если установлен, порядок чтения строки ДОЛЖЕН быть справа налево. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Если установлен, отдельные строки текста ДОЛЖНЫ выводиться вертикально на устройстве отображения. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Если установлен, части символов ДОЛЖНЫ быть разрешены выступать за пределы прямоугольника размещения текста. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Если установлен, управляющие символы ДОЛЖНЫ отображаться в выводе в виде представительных глифов Unicode. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Если установлен, альтернативный шрифт ДОЛЖЕН использоваться для символов, не поддерживаемых запрошенным шрифтом. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Если установлен, пробел в конце каждой строки ДОЛЖЕН учитываться при измерении длины строки. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Если установлен, строка, выходящая за пределы прямоугольника размещения текста, НЕ ДОЛЖНА переноситься на следующую строку. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Если установлен, целые строки текста ДОЛЖНЫ выводиться и НЕ ДОЛЖНЫ обрезаться прямоугольником размещения строки. |
| [StringFormatNoClip](#StringFormatNoClip) | Если установлен, текст, выходящий за пределы прямоугольника размещения строки, ДОЛЖЕН отображаться. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Этот флаг МОЖЕТ использоваться для указания специфического для реализации процесса рендеринга текста. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Если установлен, порядок чтения строки ДОЛЖЕН быть справа налево. Для горизонтального текста это означает, что символы читаются справа налево. Для вертикального текста это означает, что столбцы читаются справа налево. Если флаг сброшен, горизонтальный или вертикальный текст ДОЛЖЕН читаться слева направо.

--------------------

Размещение графического текста задаётся объектами [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat)

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Если установлен, отдельные строки текста ДОЛЖНЫ выводиться вертикально на устройстве отображения. Если флаг сброшен, отдельные строки текста ДОЛЖНЫ выводиться горизонтально, при этом каждая новая строка располагается ниже предыдущей.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Если установлен, части символов ДОЛЖНЫ быть разрешены выступать за пределы прямоугольника размещения текста. Если флаг сброшен, символы, выступающие за границы прямоугольника размещения текста, ДОЛЖНЫ быть перемещены, чтобы избежать выступания. Курсивная буква "f" является примером символа, у которого могут быть выступающие части.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Если установлен, управляющие символы ДОЛЖНЫ отображаться в выводе в виде представительных глифов Unicode.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Если установлен, альтернативный шрифт ДОЛЖЕН использоваться для символов, не поддерживаемых запрошенным шрифтом. Если флаг сброшен, отсутствующий в запрошенном шрифте символ ДОЛЖЕН отображаться как символ "шрифт отсутствует", который МОЖЕТ быть открытым квадратом.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Если установлен, пробел в конце каждой строки ДОЛЖЕН учитываться при измерении длины строки. Если флаг сброшен, пробел в конце каждой строки ДОЛЖЕН исключаться из измерения длины строки.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Если установлен, строка, выходящая за пределы прямоугольника размещения текста, НЕ ДОЛЖНА переноситься на следующую строку. Если флаг сброшен, строка, выходящая за пределы прямоугольника размещения текста, ДОЛЖНА быть разорвана на последнем границе слова внутри ограничивающего прямоугольника, а оставшаяся часть строки ДОЛЖНА переноситься на следующую строку.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Если установлен, целые строки текста ДОЛЖНЫ выводиться и НЕ ДОЛЖНЫ обрезаться прямоугольником размещения строки. Если флаг сброшен, размещение текста ДОЛЖНО продолжаться, пока не будут выведены все строки, или пока дополнительные строки не станут невидимыми из‑за обрезки. Этот флаг можно использовать как для запрета, так и для разрешения частичного скрытия строки текста прямоугольником размещения, не кратным высоте строки. Чтобы весь текст был виден, прямоугольник размещения должен быть как минимум высотой одной строки.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Если установлен, текст, выходящий за пределы прямоугольника размещения строки, ДОЛЖЕН отображаться. Если флаг сброшен, весь текст, выходящий за пределы прямоугольника размещения, ДОЛЖЕН обрезаться.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Этот флаг МОЖЕТ использоваться для указания специфического для реализации процесса рендеринга текста.


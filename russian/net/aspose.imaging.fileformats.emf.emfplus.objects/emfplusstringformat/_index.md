---
title: EmfPlusStringFormat
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект EmfPlusStringFormat определяет макет текста манипуляции с отображением и идентификацию языка
type: docs
weight: 5780
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

Объект EmfPlusStringFormat определяет макет текста, манипуляции с отображением и идентификацию языка

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Получает или задает объект EmfPlusLanguageIdentifier, указывающий язык , используемый для числовых цифр в строке. Например, если эта строка содержит арабские цифры, это поле ДОЛЖНО содержать идентификатор языка, который указывает арабский язык |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как заменять числовые цифры в строке в соответствии с локалью или языком. Это значение ДОЛЖНО быть определено в перечислении StringDigitSubstitution (раздел 2.1.1.30). |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Получает или задает 32-битное значение с плавающей запятой, указывающее число пробелов между началом текстовой строки и первой остановкой табуляции |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее тип обработки, выполняемой над строкой, когда встречается префикс сочетания клавиш keyboard (то есть амперсанд). относятся к тексту. Значение ДОЛЖНО быть определено в перечислении HotkeyPrefix (раздел 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | Получает или задает объект EmfPlusLanguageIdentifier (раздел 2.2.2.23) , указывающий язык, используемый для string |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее длину пробела, добавляемого к начальной позиции строки. Значение по умолчанию — 1/6 дюйма; для типографских шрифтов значение по умолчанию равно 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее, как выровнять строку по вертикали в прямоугольнике макета. Это значение ДОЛЖНО быть определено в перечислении StringAlignment. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее количество объектов EmfPlusCharacterRange (раздел 2.2.2.8), определенных в поле StringFormatData. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Получает или задает 32-битное целое число без знака, указывающее, как выровнять строку по горизонтали в прямоугольнике макета. Это значение ДОЛЖНО быть определено в перечислении StringAlignment (раздел 2.1.1.29). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | Получает или задает объект EmfPlusStringFormatData (раздел 2.2.2.44) , который указывает дополнительные данные макета текста. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое определяет параметры layout текста для форматирования, обрезки и обработки шрифтов. Это значение ДОЛЖНО состоять из флагов StringFormat (раздел 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее количество позиций табуляции , определенное в поле StringFormatData. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее отношение горизонтального пространства, выделенного для каждого символа в указанной строке, к определяемой шрифтом ширине символа . Большие значения этого свойства указывают на расстояние между символами ample ; значения меньше 1 могут привести к перекрытию символов. По умолчанию 1,03; для шрифтов typographic значение по умолчанию — 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее длину пробела, оставляемого после строки. Значение default равно 1/6 дюйма; для типографских шрифтов значение по умолчанию 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Получает или задает способ обрезки символов из строки, которая слишком велика для размещения в прямоугольнике макета. Это значение ДОЛЖНО быть определено в перечислении StringTrimming (раздел 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Получает или задает версию. |

### Смотрите также

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

---
title: "EmfPlusStringFormat Class"
type: docs
weight: 650
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Инициализирует новый экземпляр класса EmfPlusStringFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Получает или задает объект EmfPlusLanguageIdentifier, который определяет<br/>            язык, используемый для числовых цифр в строке.<br/>            Например, если эта строка содержит арабские цифры,<br/>            это поле ДОЛЖНО содержать идентификатор языка, который<br/>            указывает на арабский язык |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет способ замены<br/>            числовых цифр в строке в соответствии с локалью или языком.<br/>            Это значение ДОЛЖНО быть определено в перечислении StringDigitSubstitution<br/>            (раздел 2.1.1.30). |
| first_tab_offset | float | r/w | Получает или задает 32-битное значение с плавающей точкой, которое указывает количество<br/>            пробелов между началом текстовой строки и<br/>            первой табуляцией |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Получает или задает 32-битное целое число, которое указывает тип<br/>            обработки, выполняемой со строкой, когда встречается префикс<br/>            клавиатурного сочетания (то есть амперсанд).<br/>            По сути, это поле указывает, следует ли отображать<br/>            префиксы клавиатурных сочетаний, относящиеся к тексту.<br/>            Значение ДОЛЖНО быть определено в перечислении HotkeyPrefix<br/>            (section 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Получает или задает объект EmfPlusLanguageIdentifier (section 2.2.2.23)<br/>            который указывает язык, используемый для строки. |
| leading_margin | float | r/w | Получает или задает 32-битное значение с плавающей точкой, которое указывает длину<br/>            пространства, добавляемого к начальной позиции строки.<br/>            Значение по умолчанию — 1/6 дюйма; для типографических шрифтов<br/>            значение по умолчанию равно 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает, как<br/>            выровнять строку по вертикали в прямоугольнике размещения.<br/>            Это значение ДОЛЖНО быть определено в перечислении StringAlignment. |
| range_count | int | r/w | Получает или задает 32-битное целое число, которое указывает количество объектов EmfPlusCharacterRange<br/>            (section 2.2.2.8), определённых в поле StringFormatData. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает, как<br/>            выровнять строку по горизонтали в прямоугольнике размещения.<br/>            Это значение ДОЛЖНО быть определено в перечислении StringAlignment<br/>            (section 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Получает или задает объект EmfPlusStringFormatData (section 2.2.2.44)<br/>            который определяет дополнительные данные размещения текста. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает параметры размещения текста<br/>            для форматирования, обрезки и обработки шрифтов.<br/>            Это значение ДОЛЖНО состоять из флагов StringFormat<br/>            (section 2.1.2.8). |
| tabstop_count | int | r/w | Получает или задает 32-битное целое число, которое указывает количество табуляций<br/>            определённых в поле StringFormatData. |
| tracking | float | r/w | Получает или задает 32-битное значение с плавающей точкой, которое указывает отношение<br/>            горизонтального пространства, выделенного каждому символу в<br/>            заданной строке, к ширине символа, определённой шрифтом.<br/>            Большие значения этого свойства указывают на обильное<br/>            пространство между символами; значения меньше 1 могут приводить<br/>            к наложению символов. Значение по умолчанию — 1.03; для типографических<br/>            шрифтов значение по умолчанию равно 1.00. |
| trailing_margin | float | r/w | Получает или задает 32-битное значение с плавающей точкой, которое указывает длину<br/>            пространства, оставляемого после строки. Значение по умолчанию<br/>            — 1/6 дюйма; для типографических шрифтов значение по умолчанию равно 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Получает или задает, указывая, как обрезать символы в строке, которая<br/>            слишком велика, чтобы поместиться в прямоугольник размещения. Это значение<br/>            ДОЛЖНО быть определено в перечислении StringTrimming (section 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Получает или задает версию. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Инициализирует новый экземпляр класса EmfPlusStringFormat


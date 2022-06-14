---
title: EmfLogFontPanose
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект LogFontPanose указывает характеристики PANOSE логического шрифта.
type: docs
weight: 3060
url: /ru/net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
## EmfLogFontPanose class

Объект LogFontPanose указывает характеристики PANOSE логического шрифта.

```csharp
public sealed class EmfLogFontPanose : EmfLogFont
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfLogFontPanose](emflogfontpanose)(EmfLogFont) | Инициализирует новый экземпляр класса[`EmfLogFontPanose`](../emflogfontpanose). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее набор глифов символов. Он ДОЛЖЕН быть значением в перечислении WMF CharacterSet ([MS-WMF], раздел 2.1.1.5). Если набор символов неизвестен, обработка метафайла НЕ ДОЛЖНА пытаться переводить или интерпретировать строки , отображаемые с помощью этого шрифта. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее точность отсечения. Точность отсечения определяет, как обрезать символы, которые частично находятся за пределами области отсечения. Это может быть один или несколько флагов WMF ClipPrecision |
| [Culture](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/culture) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое ДОЛЖНО быть установлено равным нулю и ДОЛЖНО игнорироваться. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее угол в десятых долях градуса между вектором спуска и осью X устройства. Вектор спуска параллелен базовой линии строки текста. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Получает или задает Facename (64 байта):строка, состоящая не более чем из 32 символов Юникода, которая определяет имя шрифта шрифта. Если длина этой строки меньше 32 символов, ДОЛЖЕН присутствовать завершающий NULL, после которого оставшаяся часть этого поля ДОЛЖНА игнорироваться. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/fullname) { get; set; } | Получает или задает строку из 64 символов Юникода, определяющую полное имя шрифта. Если длина этой строки меньше 64 символов, ДОЛЖЕН присутствовать завершающий NULL, после оставшаяся часть этого поля ДОЛЖНА игнорироваться. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее высоту (в логических единицах) символьной ячейки шрифта или символа. Значение высоты символа, также известное как размер em, равно значению высоты символьной ячейки минус внутреннее значение интерлиньяжа. Преобразователь шрифтов ДОЛЖЕН интерпретировать значение, указанное в поле Высота, следующим образом. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее курсивный шрифт, если установлено значение 0x01; в противном случае он ДОЛЖЕН быть установлен на 0x00. |
| [Match](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/match) { get; set; } | Получает или устанавливает Это поле ДОЛЖНО игнорироваться. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее угол в десятых долях градуса между базовой линией каждого символа и осью X устройства. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее выходную точность. Точность вывода определяет, насколько точно шрифт должен соответствовать требуемой высоте, ширине, ориентации символов, спуску, шагу и типу шрифта. Это ДОЛЖНО быть значение из перечисления WMF OutPrecision |
| [Padding](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/padding) { get; set; } | Получает или задает поле, которое существует только для обеспечения 32-битного выравнивания этой структуры. Его ДОЛЖНО игнорировать |
| [Panose](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/panose) { get; set; } | Получает или задает объект Panose (раздел 2.2.21), который определяет характеристики PANOSE логического шрифта. Если все поля этого объекта равны нулю, его ДОЛЖНО игнорировать. |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | Получает или задает объект WMF PitchAndFamily ([MS-WMF], раздел 2.2.2.14), который указывает шаг и семейство шрифта. Семейства шрифтов описывают внешний вид шрифта общим способом. Они предназначены для указания шрифта, когда указанная гарнитура недоступна. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее качество вывода. Качество вывода определяет, насколько точно пытаться сопоставить атрибуты логического шрифта с атрибутами реального физического шрифта. Это ДОЛЖНО быть одним из значений перечисления WMF FontQuality ([MS-WMF] раздел 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее зачеркнутый шрифт, если установлено значение 0x01; в противном случае он ДОЛЖЕН быть установлен на 0x00. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/style) { get; set; } | Получает или задает строку из 32 символов Юникода, определяющую стиль шрифта. Если длина этой строки меньше 32 символов, ДОЛЖЕН присутствовать завершающий NULL, после которого остаток этого поля ДОЛЖЕН игнорироваться. |
| [StyleSize](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/stylesize) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее размер в точках, при котором выполняется хинтинг шрифта . Если установлено значение ноль, хинтинг шрифта выполняется с размером пункта, соответствующим полю Height в объекте LogFont в поле LogFont |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | Получает или задает 8-разрядное целое число без знака, указывающее подчеркнутый шрифт, если установлено значение 0x01; в противном случае он ДОЛЖЕН быть установлен на 0x00. |
| [VendorId](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/vendorid) { get; set; } | Получает или устанавливает Это поле ДОЛЖНО игнорироваться. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/version) { get; set; } | Получает или устанавливает Это поле ДОЛЖНО игнорироваться. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее толщину шрифта в диапазоне от нуля до 1000. Например, 400 нормальный и 700 жирный. Если это значение равно нулю, можно использовать вес по умолчанию . |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее среднюю ширину (в логических единицах) символов в шрифте. Если значение поля «Ширина» равно нулю, соответствующее значение ДОЛЖНО быть рассчитанным из других значений LogFont, чтобы найти шрифт с предполагаемым типографом соотношением сторон |

### Смотрите также

* class [EmfLogFont](../emflogfont)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

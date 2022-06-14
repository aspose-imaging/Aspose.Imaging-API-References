---
title: WmfLogColorSpace
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект LogColorSpace указывает логическое цветовое пространство для контекста устройства воспроизведения которое может быть именем цветового профиля в символы ASCII.
type: docs
weight: 8750
url: /ru/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

Объект LogColorSpace указывает логическое цветовое пространство для контекста устройства воспроизведения, которое может быть именем цветового профиля в символы ASCII.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее тип цветового пространства . Он ДОЛЖЕН быть определен в перечислении LogicalColorSpace (раздел 2.1.1.14). Если это значение равно LCS_sRGB или LCS_WINDOWS_COLOR_SPACE, ДОЛЖНО использоваться цветовое пространство sRGB. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Получает или задает объект CIEXYZTriple (раздел 2.2.2.7), определяющий координаты CIE цветности x, y и z трех цветов. которые соответствуют RGBendpointsдля логического цветового пространства, связанного с битовая карта. Если в поле [`ColorSpaceType`](./colorspacetype)не указано LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано . |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Получает или задает необязательную строку символов ASCII, указывающую имя файла, содержащего цветовой профиль. Если указано имя файла , а в поле[`ColorSpaceType`](./colorspacetype)установлено значение LCS_CALIBRATED_RGB, остальные поля этой структуры ДОЛЖНЫ игнорироваться . |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Получает или задает 32-разрядное значение с фиксированной точкой, определяющее тонированную кривую отклика для синего цвета. Если в поле[`ColorSpaceType`](./colorspacetype) не указан LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Получает или задает 32-разрядное значение с фиксированной точкой, определяющее тонированную кривую отклика для зеленого цвета. Если в поле[`ColorSpaceType`](./colorspacetype) не указан LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Получает или задает 32-разрядное значение с фиксированной точкой, которое определяет тонированную кривую отклика для красного цвета. Если в поле[`ColorSpaceType`](./colorspacetype) не указан LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее сопоставление гаммы намерение. Он ДОЛЖЕН быть определен в перечислении GamutMappingIntent (раздел 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее signatureобъектов цветового пространства; он ДОЛЖЕН быть установлен на значение 0x50534F43, которое является кодировкой ASCII строки "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое определяет sizeэтого объекта в байтах. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Получает или задает 32-битное целое число без знака, определяющее версияномер; это ДОЛЖНО быть 0x00000400. |

### Примечания

Поля Endpoints, GammaRed, GammaGreen и GammaBlue используются для задать логическое цветовое пространство. Поле Endpoints представляет собой объект CIEXYZTriple , содержащий значения x, y и z конечной точки RGB цветового пространства . Соотношение между трехцветными значениями X,Y,Z и значениями цветности x,y,z выражается следующим образом. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Поля GammaRed, GammaGreen и GammaBlue содержат значения в формате "8.8 с фиксированной точкой", который является методом для представления нецелых чисел. Каждое значение состоит из расширенного нуля 8-битной величины, за которой следует 8-битная дробь, при этом объединенные 16 битов сдвинуты влево на 8 бит. Таким образом, в 32-битном режиме реальное значение NF равно 00000000nnnnnnffffffff00000000, где "nnnnnnnn" и "ffffffff" являются двоичными представлениями N и F соответственно. Например, для действительного числа 10,5 nnnnnnnn будет равно 00001010 (двоичное число 10), а ffffffff будет равно 00000101 (двоичное число 5), а полное 32-битное двоичное значение будет быть 00000000000010100000010100000000, что является шестнадцатеричным значением 0x0A50.

### Смотрите также

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* пространство имен [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

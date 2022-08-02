---
title: WmfLogColorSpace
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект LogColorSpace определяет логическое цветовое пространство для контекста устройства воспроизведения которое может быть именем цветового профиля в символах ASCII.
type: docs
weight: 8750
url: /ru/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

Объект LogColorSpace определяет логическое цветовое пространство для контекста устройства воспроизведения, которое может быть именем цветового профиля в символах ASCII.

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
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Получает или задает 32-разрядное целое число со знаком, указывающее тип цветового пространства . Он ДОЛЖЕН быть определен в LogicalColorSpace enumeration (раздел 2.1.1.14). Если это значение равно LCS_sRGB или LCS_WINDOWS_COLOR_SPACE, ДОЛЖНО использоваться цветовое пространство sRGB. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Получает или задает объект CIEXYZTriple (раздел 2.2.2.7), который определяет координаты CIE цветности x, y и z трех цветов , которые соответствуют RGBendpoints для цветового пространства logical , связанного с растровым изображением. Если [`ColorSpaceType`](./colorspacetype) поле не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Получает или задает необязательную строку символов ASCII, указывающую имя файла, содержащего цветовой профиль. Если имя файла указано , а[`ColorSpaceType`](./colorspacetype) поле установлено в LCS_CALIBRATED_RGB, другие поля этой структуры ДОЛЖНЫ быть игнорируемыми. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Получает или задает 32-разрядное значение с фиксированной точкой, определяющее кривую отклика toned для синего цвета. Если[`ColorSpaceType`](./colorspacetype) field не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Получает или задает 32-битное значение с фиксированной точкой, которое определяет кривую отклика toned для зеленого цвета. Если[`ColorSpaceType`](./colorspacetype) field не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Получает или задает 32-разрядное значение с фиксированной точкой, которое определяет кривую отклика toned для красного цвета. Если[`ColorSpaceType`](./colorspacetype) field не указывает LCS_CALIBRATED_RGB, это поле ДОЛЖНО быть проигнорировано. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Получает или задает 32-разрядное целое число со знаком, определяющее намерение gamut mapping . Он ДОЛЖЕН быть определен в перечислении GamutMappingIntent enumeration (раздел 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее signature объектов цветового пространства; он ДОЛЖЕН быть установлен в значение 0x50534F43, которое является кодировкой ASCII строки "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое определяет size этого объекта в байтах. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Получает или задает 32-разрядное целое число без знака, которое определяет a version количество; это ДОЛЖНО быть 0x00000400. |

### Примечания

Поля Endpoints, GammaRed, GammaGreen и GammaBlue используются для указания логического цветового пространства. Поле Endpoints — это объект CIEXYZTriple , который содержит значения x, y и z конечной точки RGB цветового пространства. Соотношение между значениями тристимула X, Y, Z и значениями цветности x, y, z выражается следующим образом. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Поля GammaRed, GammaGreen и GammaBlue содержат значения в "8.8 фиксированной точке" формат, который представляет собой метод представления нецелых чисел. Каждое значение состоит из 8-битной величины zeroextended , за которой следует 8-битная дробь, при этом объединенные 16 битов сдвинуты влево на 8 бит. Таким образом, в 32-битном формате реальное значение NF равно 00000000nnnnnnnnffffffff00000000, где "nnnnnnnn" и "ffffffff" являются двоичными представлениями N и F соответственно. Например, для The Real Number 10.5, nnnnnnn была бы 00001010 (двоичный 10), а Ffffffff будет 00000101 (двоичный 5), а полное 32-битное двоичное значение

### Смотрите также

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* пространство имен [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

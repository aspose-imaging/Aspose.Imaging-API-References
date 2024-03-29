---
title: EmfExtTextOutA
second_title: Справочник по Aspose.Imaging for .NET API
description: Запись EMR_EXTTEXTOUTA рисует текстовую строку ASCII используя текущий шрифт и цвета текста.
type: docs
weight: 3670
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
## EmfExtTextOutA class

Запись EMR_EXTTEXTOUTA рисует текстовую строку ASCII, используя текущий шрифт и цвета текста.

```csharp
public sealed class EmfExtTextOutA : EmfDrawingRecordType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfExtTextOutA](emfexttextouta#constructor)() | Инициализирует новый экземпляр[`EmfExtTextOutA`](../emfexttextouta) класс. |
| [EmfExtTextOutA](emfexttextouta#constructor_1)(EmfRecord) | Инициализирует новый экземпляр[`EmfExtTextOutA`](../emfexttextouta) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/aemrtext) { get; set; } | Получает или задает объект EmrText (раздел 2.2.5), который указывает выходную строку в виде 8-битных символов ASCII, текстовых атрибутов и значений интервалов. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/bounds) { get; set; } | Получает или задает объект WMF RectL ([MS-WMF], раздел 2.2.2.19). Он не используется, и ДОЛЖЕН игнорироваться при получении. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/exscale) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее коэффициент масштабирования, применяемый вдоль оси X для преобразования единиц пространства страницы в единицы 0,01 мм. Это СЛЕДУЕТ использовать, только если графический режим , указанный в iGraphicsMode, равен GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/eyscale) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее коэффициент масштабирования, применяемый вдоль оси Y для преобразования единиц пространства страницы в единицы 0,01 мм. Это СЛЕДУЕТ использовать, только если графический режим , указанный в iGraphicsMode, равен GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/igraphicsmode) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее графический режим из перечисления GraphicsMode (раздел 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Получает или задает размер записи |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Получает или задает тип. |

### Смотрите также

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

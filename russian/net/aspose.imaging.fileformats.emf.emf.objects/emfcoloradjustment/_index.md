---
title: EmfColorAdjustment
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект ColorAdjustment определяет значения для настройки цветов в исходных растровых изображениях при передаче битовых блоков.
type: docs
weight: 2930
url: /ru/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

Объект ColorAdjustment определяет значения для настройки цветов в исходных растровых изображениях при передаче битовых блоков.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее n-е значение гамма-коррекции мощности для основного синего цвета исходных цветов. Это значение ДОЛЖНО находиться в диапазоне от 2 500 до 65 000. Значение 10 000 означает, что гамма-коррекция НЕ ДОЛЖНА выполняться. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | Получает или задает 16-разрядное целое число со знаком, указывающее уровень яркости, применяемый к исходному объекту. Это значение ДОЛЖНО быть в диапазоне от –100 до 100. Нулевое значение означает, что регулировка яркости НЕ ДОЛЖНА выполняться. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | Получает или задает 16-разрядное целое число со знаком, указывающее степень красочности, которая должна быть применена к исходному объекту. Это значение ДОЛЖНО быть в диапазоне от –100 до 100. Нулевое значение означает, что регулировка цветности НЕ ДОЛЖНА выполняться |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | Получает или задает 16-разрядное целое число со знаком, указывающее степень контрастности, применяемую к исходному объекту. Это значение ДОЛЖНО находиться в диапазоне от –100 до 100. Нулевое значение означает, что регулировка контрастности НЕ ДОЛЖНА выполняться. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее n-е значение гамма-коррекции мощности для зеленого основного цвета исходных цветов. Это значение ДОЛЖНО находиться в диапазоне от 2 500 до 65 000. Значение 10 000 означает, что гамма-коррекция НЕ ДОЛЖНА выполняться. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее тип стандартного источника света, под которым просматривается изображение , из перечисления Illuminant (раздел 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее n-е значение гамма-коррекции мощности для красного основного цвета исходных цветов. Это значение ДОЛЖНО находиться в диапазоне от 2 500 до 65 000. Значение 10 000 означает, что гамма-коррекция НЕ ДОЛЖНА выполняться. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | Получает или задает 16-разрядное целое число со знаком, указывающее величину корректировки красного или зеленого оттенка, которая должна быть применена к исходному объекту. Это значение ДОЛЖНО находиться в диапазоне от –100 до 100. Положительные числа корректируются в сторону красного цвета, а отрицательные числа — в сторону зеленого. Нулевое значение означает, что регулировка оттенка НЕ ДОЛЖНА выполняться |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее ссылку на черный для исходных цветов. Любые цвета темнее этого считаются черными. Это значение ДОЛЖНО быть в диапазоне от нуля до 4000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее ссылку на белый для исходных цветов. Любые цвета светлее этого считаются белыми. Это значение ДОЛЖНО быть в диапазоне от 6 000 до 10 000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее размер этого объекта в байтах. Это ДОЛЖНО быть 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее способ подготовки выходного изображения. Это поле может быть установлено равным NULL или любой комбинации значений в перечислении ColorAdjustment (раздел 2.1.5). |

### Смотрите также

* class [EmfObject](../emfobject)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

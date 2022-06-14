---
title: EmfPlusPenOptionalData
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект EmfPlusPenOptionalData указывает дополнительные данные для графического пера
type: docs
weight: 5680
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

Объект EmfPlusPenOptionalData указывает дополнительные данные для графического пера

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | Получает или задает необязательный объект EmfPlusCompoundLineData (раздел 2.2.2.9) который указывает массив значений с плавающей запятой, которые определяют составная линия пера, состоящая из параллельных линий и пробелов. Это поле ДОЛЖНО присутствовать, если флаг PenDataCompoundLine установлен в поле PenDataFlags объекта EmfPlusPenData |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | Получает или задает необязательный объект EmfPlusCustomEndCapData (раздел 2.2.2.11) , который определяет пользовательскую форму торца, которая является формой для используйте в конце линии, нарисованной этим пером. Это может быть любая из различных форм, таких как квадрат, круг или ромб. Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomEndCap установлен в поле PenDataFlags объекта EmfPlusPenData |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Получает или задает необязательный объект EmfPlusCustomStartCapData (раздел 2.2.2.15) , который определяет пользовательскую форму начальной заглавной буквы, которая является формой для используйте в начале линии, нарисованной этим пером. Это может быть любой различной формы, например, квадрат, круг или ромб. Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomStartCap установлен в поле PenDataFlags объекта EmfPlusPenData |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Получает или задает необязательное 32-разрядное целое число со знаком, которое указывает форму для обоих концов каждого дефиса в пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLineCap установлен в поле PenDataFlags объекта EmfPlusPenData, а значение ДОЛЖНО быть определено в DashedLineCapType. перечисление (раздел 2.1.1.10). |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Получает или задает необязательный объект EmfPlusDashedLineData (раздел 2.2.2.16) который определяет длину дефисов и пробелов в пользовательском пунктир. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLine установлен в поле PenDataFlags объекта EmfPlusPenData . |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Получает или задает необязательное 32-битное значение с плавающей запятой, указывающее расстояние от начала строки до начала::.:47:::первый пробел в шаблоне пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLineOffset установлен в поле PenDataFlags объекта EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | Получает или задает необязательное 32-разрядное целое число со знаком, указывающее форму для конца строки в поле CustomEndCapData. Это поле ДОЛЖНО присутствовать, если флаг PenDataEndCap установлен в поле PenDataFlags объекта EmfPlusPenData, а значение ДОЛЖНО быть определено в LineCapType перечисление |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Получает или задает необязательное 32-битное целое число со знаком, указывающее, как соединить две линии, нарисованные одним пером и концы которых сходятся . Это поле ДОЛЖНО присутствовать, если флаг PenDataJoin установлен в поле PenDataFlags объекта EmfPlusPenData, а значение ДОЛЖНО быть определено в LineJoinType перечисление (раздел 2.1.1.19). |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Получает или задает необязательное 32-разрядное целое число со знаком, определяющее стиль используемый для линий, нарисованных с помощью этого объекта пера. Это поле ДОЛЖНО присутствовать, если флаг PenDataLineStyle установлен в поле PenDataFlags объекта EmfPlusPenData, а значение ДОЛЖНО быть определено в LineStyle. перечисление (раздел 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Получает или задает необязательное 32-битное значение с плавающей запятой, указывающее ограничение , которое является максимально допустимым отношением длины среза к ширина строки. Длина под углом — это расстояние от пересечения линейных стен внутри стыка до пересечения линейных стен снаружи стыка. Длина скоса может быть большой, когда угол между двумя линиями мал. Это поле ДОЛЖНО присутствовать, если флаг PenDataMiterLimit установлен в поле PenDataFlags объекта EmfPlusPenData. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Получает или задает необязательное 32-разрядное целое число со знаком, определяющее распределение ширины пера относительно координаты рисуемой линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataNonCenter установлен в поле PenDataFlags объекта EmfPlusPenData, а значение ДОЛЖНО быть определено в PenAlignment перечисление (раздел 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | Получает или задает необязательное 32-разрядное целое число со знаком, определяющее форму для начала строки в поле CustomStartCapData. Это поле ДОЛЖНО присутствовать, если установлен флаг PenDataStartCap в поле PenDataFlags объекта EmfPlusPenData, а значение ДОЛЖНО быть определено в LineCapType перечисление (раздел 2.1.1.18). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47) который определяет преобразование мирового пространства в пространство устройства для ручка. Это поле ДОЛЖНО присутствовать, если флаг PenDataTransform установлен в поле PenDataFlags объекта EmfPlusPenData . |

### Смотрите также

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

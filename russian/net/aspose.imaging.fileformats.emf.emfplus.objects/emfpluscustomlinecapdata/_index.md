---
title: EmfPlusCustomLineCapData
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект EmfPlusCustomLineCapData указывает данные по умолчанию для пользовательского ограничения строки.
type: docs
weight: 5390
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
## EmfPlusCustomLineCapData class

Объект EmfPlusCustomLineCapData указывает данные по умолчанию для пользовательского ограничения строки.

```csharp
public sealed class EmfPlusCustomLineCapData : EmfPlusCustomBaseLineCap
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusCustomLineCapData](emfpluscustomlinecapdata)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BaseCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/basecap) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее значение из перечисления LineCap (раздел 2.1.1.18) для которого пользовательское окончание строки основано. |
| [BaseInset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/baseinset) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, указывающее расстояние между началом конца строки и концом строки. |
| [CustomLineCapDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/customlinecapdataflags) { get; set; } | Получает или задает 32-разрядное целое число без знака, определяющее данные в поле OptionalData |
| [FillHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/fillhotspot) { get; set; } | Получает или задает объект EmfPlusPointF, который в данный момент не используется. ДОЛЖНО быть установлено значение {0.0, 0.0}. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/optionaldata) { get; set; } | Получает или задает необязательный объект EmfPlusCustomLineCapOptionalData (раздел 2.2.2.14) , который указывает дополнительные данные для пользовательского окончания строки графики. T Конкретное содержимое этого поля определяется значением поля CustomLineCapDataFlags. |
| [StrokeEndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokeendcap) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее значение в перечислении LineCap, указывающее, какой заглавная строка должна использоваться в конце линии, которую необходимо нарисовать. |
| [StrokeHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokehotspot) { get; set; } | Получает или задает объект EmfPlusPointF, который в данный момент не используется. ДОЛЖНО быть установлено значение {0.0, 0.0}. |
| [StrokeJoin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokejoin) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее значение в перечислении LineJoin (раздел 2.1.1.19), указывающее способ присоединения две линии, проведенные одним и тем же пером и концы которых сходятся. На пересечении двух концов линии соединение линий делает соединение более непрерывным. |
| [StrokeMiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokemiterlimit) { get; set; } | Получает или задает 32-разрядное значение с плавающей запятой, содержащее предел толщины соединения на скошенном углу путем установки максимального допустимое отношение длины под углом к ширине линии. |
| [StrokeStartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokestartcap) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее значение в перечислении LineCap, указывающее конец строки , используемый в начале строки нарисовано |
| [WidthScale](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/widthscale) { get; set; } | Получает или задает 32-битное значение с плавающей запятой, указывающее величину, на которую масштабируется пользовательский конец строки по отношению к ширине строки. объект EmfPlusPen (раздел 2.2.1.7), который используется для рисования линий. |

### Смотрите также

* class [EmfPlusCustomBaseLineCap](../emfpluscustombaselinecap)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

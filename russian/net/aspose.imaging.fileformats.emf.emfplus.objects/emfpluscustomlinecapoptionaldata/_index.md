---
title: EmfPlusCustomLineCapOptionalData
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект EmfPlusCustomLineCapOptionalData указывает необязательные данные заполнения и контура для пользовательского окончания строки.
type: docs
weight: 5400
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
## EmfPlusCustomLineCapOptionalData class

Объект EmfPlusCustomLineCapOptionalData указывает необязательные данные заполнения и контура для пользовательского окончания строки.

```csharp
public sealed class EmfPlusCustomLineCapOptionalData : EmfPlusStructureObjectType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData](emfpluscustomlinecapoptionaldata)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [FillData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/filldata) { get; set; } | Получает или задает необязательный объект EmfPlusFillPath (раздел 2.2.2.17), указывающий путь для заливки пользовательского графического штриха. Это поле ДОЛЖНО присутствовать, если флаг CustomLineCapDataFillPath установлен в поле CustomLineCapDataFlags объекта EmfPlusCustomLineCapData. |
| [OutlineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/outlinedata) { get; set; } | Получает или задает необязательный объект EmfPlusLinePath (раздел 2.2.2.26) , указывающий путь для обводки настраиваемой графической линии. Это поле ДОЛЖНО присутствовать, если флаг CustomLineCapDataLinePath установлен в поле CustomLineCapDataFlags объекта EmfPlusCustomLineCapData. |

### Смотрите также

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
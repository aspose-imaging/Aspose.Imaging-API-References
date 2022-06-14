---
title: EmfHeaderExtension2
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект HeaderExtension2 определяет второе расширение заголовка метафайла EMF. Он добавляет возможность измерения поверхности устройства в микрометрах что повышает разрешение и масштабируемость метафайлов EMF.
type: docs
weight: 3000
url: /ru/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

Объект HeaderExtension2 определяет второе расширение заголовка метафайла EMF. Он добавляет возможность измерения поверхности устройства в микрометрах, что повышает разрешение и масштабируемость метафайлов EMF.

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Получает или задает объект RectL WMF ([MS-WMF], раздел 2.2.2.19), который указывает прямоугольные включительно-включительно границы в устройстве единицы наименьшего прямоугольника, который можно нарисовать вокруг изображения, хранящегося в метафайле |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее размер метафайла в байтах. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Получает или задает объект WMF SizeL ([MS-WMF], раздел 2.2.2.22), который указывает размер эталонного устройства в пикселях |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Получает или задает объект WMF RectL, указывающий прямоугольные включающие-включающие размеры в 0,01 миллиметра единицы прямоугольника, окружающего изображение хранится в метафайле |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Получает или задает 16-разрядное целое число без знака, указывающее количество графических объектов, которые будут использоваться при обработке метафайла |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx) { get; set; } | Получает или задает 32-битный горизонтальный размер устройства отображения, для которого было сгенерировано изображение метафайла, в микрометрах |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy) { get; set; } | Получает или задает 32-битный вертикальный размер устройства отображения, для которого было сгенерировано изображение метафайла, в микрометрах. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Получает или задает объект WMF SizeL, указывающий размер эталонного устройства в миллиметрах |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее количество символов в массиве , содержащем описание содержимого метафайла. Это ноль, если нет строки описания. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее количество записей в палитре метафайла . Палитра находится в записи EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Получает или задает 32-битное целое число без знака, указывающее смещение от начала этой записи до массива, содержащего описание содержимое метафайла |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Получает или задает 32-битное целое число без знака, указывающее количество записей в метафайле |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Получает или задает 32-разрядное целое число без знака, указывающее подпись записи. Это ДОЛЖНО быть ENHMETA_SIGNATURE, из перечисления FormatSignature (раздел 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | Получает или устанавливает 16-битное целое число без знака, которое ДОЛЖНО быть равно 0x0000 и ДОЛЖНО игнорироваться |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Получает значение, указывающее, является ли этот[`EmfHeaderObject`](../emfheaderobject)допустимым. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Получает или задает Version (4 байта):32-разрядное целое число без знака, определяющее совместимость метафайлов EMF. Это ДОЛЖНО быть 0x00010000 |

### Смотрите также

* class [EmfHeaderObject](../emfheaderobject)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

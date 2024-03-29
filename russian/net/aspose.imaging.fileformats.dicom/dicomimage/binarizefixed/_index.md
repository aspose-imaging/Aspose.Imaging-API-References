---
title: BinarizeFixed
second_title: Справочник по Aspose.Imaging for .NET API
description: Бинаризация изображения с заданным порогом
type: docs
weight: 170
url: /ru/net/aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/
---
## DicomImage.BinarizeFixed method

Бинаризация изображения с заданным порогом

```csharp
public override void BinarizeFixed(byte threshold)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | Byte | Пороговое значение. Если соответствующее значение серого пикселя больше порогового значения, ему будет присвоено значение 255, в противном случае — 0. |

### Примеры

В следующем примере выполняется бинаризация изображения DICOM с предопределенным пороговым значением. Бинаризованные изображения содержат только 2 цвета — черный и белый.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // Бинаризовать изображение с пороговым значением 127.
    // Если соответствующее значение серого пикселя больше 127, ему будет присвоено значение 255, иначе 0.
    dicomImage.BinarizeFixed(127);
    dicomImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [DicomImage](../../dicomimage)
* пространство имен [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

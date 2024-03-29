---
title: RotateFlipType
second_title: Справочник по Aspose.Imaging for .NET API
description: Определяет степень поворота изображения и ось используемую для отражения изображения.
type: docs
weight: 10890
url: /ru/net/aspose.imaging/rotatefliptype/
---
## RotateFlipType enumeration

Определяет степень поворота изображения и ось, используемую для отражения изображения.

```csharp
public enum RotateFlipType
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| RotateNoneFlipNone | `0` | Задает отсутствие вращения по часовой стрелке и переворота. |
| Rotate90FlipNone | `1` | Определяет поворот на 90 градусов по часовой стрелке без отражения. |
| Rotate180FlipNone | `2` | Задает поворот на 180 градусов по часовой стрелке без отражения. |
| Rotate270FlipNone | `3` | Задает вращение на 270 градусов по часовой стрелке без отражения. |
| RotateNoneFlipX | `4` | Задает отсутствие вращения по часовой стрелке с последующим горизонтальным отражением. |
| Rotate90FlipX | `5` | Задает поворот на 90 градусов по часовой стрелке с последующим горизонтальным отражением. |
| Rotate180FlipX | `6` | Задает поворот на 180 градусов по часовой стрелке с последующим горизонтальным отражением. |
| Rotate270FlipX | `7` | Задает поворот на 270 градусов по часовой стрелке с последующим горизонтальным отражением. |
| RotateNoneFlipY | `8` | Указывает отсутствие вращения по часовой стрелке с последующим вертикальным отражением. |
| Rotate90FlipY | `9` | Задает поворот на 90 градусов по часовой стрелке с последующим вертикальным отражением. |
| Rotate180FlipY | `10` | Задает поворот на 180 градусов по часовой стрелке с последующим вертикальным отражением. |
| Rotate270FlipY | `11` | Задает поворот на 270 градусов по часовой стрелке с последующим вертикальным отражением. |
| RotateNoneFlipXY | `12` | Задает отсутствие вращения по часовой стрелке с последующим отражением по горизонтали и вертикали. |
| Rotate90FlipXY | `13` | Определяет поворот на 90 градусов по часовой стрелке с последующим отражением по горизонтали и вертикали. |
| Rotate180FlipXY | `14` | Определяет поворот на 180 градусов по часовой стрелке с последующим отражением по горизонтали и вертикали. |
| Rotate270FlipXY | `15` | Определяет поворот на 270 градусов по часовой стрелке с последующим горизонтальным и вертикальным отражением. |

### Примеры

Этот пример загружает изображение, поворачивает его на 90 градусов по часовой стрелке и, при необходимости, переворачивает изображение по горизонтали и (или) по вертикали.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // Повернуть, отразить и сохранить в выходной файл.
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

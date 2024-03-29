---
title: GammaValueDenominator
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает часть знаменателя значения гаммы. Неисправленное изображение изображение без гаммы должно иметь в результате значение 10.
type: docs
weight: 90
url: /ru/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/
---
## TgaImage.GammaValueDenominator property

Получает часть знаменателя значения гаммы. Неисправленное изображение (изображение без гаммы) должно иметь в результате значение 1,0.

```csharp
public ushort GammaValueDenominator { get; }
```

### Примеры

Получение значений публичных свойств загруженного изображения TGA.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### Смотрите также

* class [TgaImage](../../tgaimage)
* пространство имен [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

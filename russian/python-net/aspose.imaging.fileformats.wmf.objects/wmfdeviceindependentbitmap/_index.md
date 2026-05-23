---
title: "WmfDeviceIndependentBitmap Класс"
type: docs
weight: 180
url: /ru/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Инициализирует новый экземпляр класса WmfDeviceIndependentBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Получает или задает массив байтов, определяющих изображение. Размер и<br/>                формат этих данных определяется информацией в поле<br/>                DIBHeaderInfo. |
| cached_image | System.Byte | r/w | Получает или задает кэшированное растровое изображение. |
| colors_data | System.Byte | r/w | Получает или задает необязательный массив либо объектов RGBQuad (section<br/>                2.2.2.20), либо 16‑битных беззнаковых целых, определяющих таблицу цветов. Размер и содержимое этого поля ДОЛЖНО определяться из записи метафайла или объекта, содержащего этот DeviceIndependentBitmap<br/>                и из информации в поле DIBHeaderInfo. См. перечисление ColorUsage (section 2.1.1.6) и перечисление BitCount (section<br/>                2.1.1.3) для дополнительных сведений |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Получает или задает либо объект BitmapCoreHeader (section 2.2.2.2), либо объект BitmapInfoHeader (section 2.2.2.3), который определяет информацию<br/>                об изображении |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Инициализирует новый экземпляр класса WmfDeviceIndependentBitmap


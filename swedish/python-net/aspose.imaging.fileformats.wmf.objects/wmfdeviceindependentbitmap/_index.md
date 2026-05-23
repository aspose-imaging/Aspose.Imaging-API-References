---
title: "WmfDeviceIndependentBitmap klass"
type: docs
weight: 180
url: /sv/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Initierar en ny instans av WmfDeviceIndependentBitmap-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Hämtar eller anger en bytearray som definierar bilden. Storleken och<br/>                formatet för dessa data bestäms av information i<br/>                DIBHeaderInfo-fältet. |
| cached_image | System.Byte | r/w | Hämtar eller anger den cachade rasterbilden. |
| colors_data | System.Byte | r/w | Hämtar eller anger en valfri array av antingen RGBQuad-objekt (avsnitt<br/>                2.2.2.20) eller 16-bitars osignerade heltal som definierar en färgtabell. Storleken och innehållet i detta fält SKA bestämmas från<br/>                metafilsposten eller objektet som innehåller detta DeviceIndependentBitmap<br/>                och från information i DIBHeaderInfo-fältet. Se ColorUsage‑enumeration (avsnitt 2.1.1.6) och BitCount‑enumeration (avsnitt<br/>                2.1.1.3) för ytterligare detaljer. |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Hämtar eller anger antingen ett BitmapCoreHeader-objekt (avsnitt 2.2.2.2) eller ett<br/>                BitmapInfoHeader-objekt (avsnitt 2.2.2.3) som specificerar information<br/>                om bilden. |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Initierar en ny instans av WmfDeviceIndependentBitmap-klassen


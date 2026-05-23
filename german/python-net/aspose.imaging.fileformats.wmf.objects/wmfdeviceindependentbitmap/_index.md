---
title: "WmfDeviceIndependentBitmap Klasse"
type: docs
weight: 180
url: /de/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Initialisiert eine neue Instanz der WmfDeviceIndependentBitmap Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Liest oder setzt ein Array von Bytes, das das Bild definiert. Die Größe und<br/>                das Format dieser Daten werden durch Informationen im<br/>                Feld DIBHeaderInfo bestimmt. |
| cached_image | System.Byte | r/w | Liest oder setzt das zwischengespeicherte Rasterbild. |
| colors_data | System.Byte | r/w | Liest oder setzt ein optionales Array entweder von RGBQuad-Objekten (Abschnitt<br/>                2.2.2.20) oder 16‑Bit‑Ganzzahlen ohne Vorzeichen, die eine Farbpalette definieren. Die<br/>                Größe und der Inhalt dieses Feldes SOLLTEN aus dem<br/>                Metadatei‑Eintrag oder Objekt, das dieses DeviceIndependentBitmap enthält,<br/>                und aus Informationen im DIBHeaderInfo‑Feld bestimmt werden. Siehe ColorUsage<br/>                Enumeration (Abschnitt 2.1.1.6) und BitCount Enumeration (Abschnitt<br/>                2.1.1.3) für weitere Details |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Liest oder setzt entweder ein BitmapCoreHeader-Objekt (Abschnitt 2.2.2.2) oder ein<br/>                BitmapInfoHeader-Objekt (Abschnitt 2.2.2.3), das Informationen<br/>                über das Bild angibt |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Initialisiert eine neue Instanz der WmfDeviceIndependentBitmap Klasse


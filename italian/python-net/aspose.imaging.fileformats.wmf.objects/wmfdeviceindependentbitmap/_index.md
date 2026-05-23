---
title: "WmfDeviceIndependentBitmap Classe"
type: docs
weight: 180
url: /it/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | Inizializza una nuova istanza della classe WmfDeviceIndependentBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Ottiene o imposta un array di byte che definisce l'immagine. La dimensione e<br/>                il formato di questi dati sono determinati dalle informazioni nel<br/>                campo DIBHeaderInfo. |
| cached_image | System.Byte | r/w | Ottiene o imposta l'immagine raster memorizzata nella cache. |
| colors_data | System.Byte | r/w | Ottiene o imposta un array opzionale di RGBQuad Objects (sezione<br/>                2.2.2.20) o interi senza segno a 16 bit che definiscono una tavola dei colori. La<br/>                dimensione e il contenuto di questo campo DEVE essere determinati dal<br/>                record metafile o dall'oggetto che contiene questo DeviceIndependentBitmap<br/>                e dalle informazioni nel campo DIBHeaderInfo. Vedere l'enumerazione ColorUsage<br/>                (sezione 2.1.1.6) e l'enumerazione BitCount (sezione<br/>                2.1.1.3) per ulteriori dettagli |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Ottiene o imposta un BitmapCoreHeader Object (sezione 2.2.2.2) o un<br/>                BitmapInfoHeader Object (sezione 2.2.2.3) che specifica le informazioni<br/>                sull'immagine |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

Inizializza una nuova istanza della classe WmfDeviceIndependentBitmap


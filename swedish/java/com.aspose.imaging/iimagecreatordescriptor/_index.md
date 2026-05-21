---
title: "IImageCreatorDescriptor"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bildskaparens beskrivning som specificerar skaparegenskaperna."
type: docs
weight: 129
url: /sv/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Bildskapardeskriptorn som specificerar skaparegenskaperna. Skapardeskriptorn används för att undvika behovet av att hålla varje bildskaparinstans i minnet och problem med flertrådad körning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Bestämmer om bildskaparen kan skapa en ny bild med hjälp av `imageOptions`. |
| [createInstance()](#createInstance--) | Skapar en ny skaparinstans. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Bestämmer om bildskaparen kan skapa en ny bild med hjälp av `imageOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Bildalternativen. |

**Returns:**
boolean - `true` om bildskaparen som skapats av detta deskriptör kan skapa bilddata med den angivna `imageOptions`; annars `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Skapar en ny skaparinstans.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

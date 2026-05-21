---
title: "IImageLoaderDescriptor"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bildläsarens beskrivning som specificerar laddarens egenskaper."
type: docs
weight: 134
url: /sv/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Den image loader descriptor som specificerar loader properties. Den loader descriptor används för att övervinna behovet av att innehålla varje image loader-instans i minnet och problem med flertrådad körning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Bestämmer om image loader kan läsa en ny bild från den angivna strömmen och eventuellt använda `loadOptions`. |
| [createInstance()](#createInstance--) | Skapar en ny laddarinstans. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Bestämmer om image loader kan läsa en ny bild från den angivna strömmen och eventuellt använda `loadOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Strömbehållaren. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Filformatdetaljerna specificerade av `loadOptions`. `loadOptions` kan vara null. |

**Returns:**
boolean - `true` om bildläsaren som skapats av den här beskrivaren kan läsa bild från ström; annars `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Skapar en ny laddarinstans.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.

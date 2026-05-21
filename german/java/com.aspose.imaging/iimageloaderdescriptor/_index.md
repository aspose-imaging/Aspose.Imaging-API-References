---
title: "IImageLoaderDescriptor"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Bild-Lader-Deskriptor, der die Lader-Eigenschaften spezifiziert."
type: docs
weight: 134
url: /de/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Der image loader descriptor, der die loader properties angibt. Der loader descriptor wird verwendet, um die Notwendigkeit zu umgehen, jede image loader Instanz im Speicher zu halten und Multithreading‑Probleme zu vermeiden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Bestimmt, ob der image loader ein neues Bild aus dem angegebenen Stream lesen kann und optional die `loadOptions` verwendet. |
| [createInstance()](#createInstance--) | Erstellt eine neue Loader‑Instanz. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Bestimmt, ob der image loader ein neues Bild aus dem angegebenen Stream lesen kann und optional die `loadOptions` verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Dateiformatdetails, die durch `loadOptions` angegeben werden. Die `loadOptions` können null sein. |

**Returns:**
boolesch - `true`, wenn der von diesem Deskriptor erstellte Bildlader das Bild aus dem Stream lesen kann; andernfalls `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Erstellt eine neue Loader‑Instanz.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.

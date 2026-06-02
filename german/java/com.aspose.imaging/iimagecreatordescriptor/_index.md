---
title: "IImageCreatorDescriptor"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Bild-Ersteller-Deskriptor, der die Eigenschaften des Erstellers angibt."
type: docs
weight: 129
url: /de/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Der image creator descriptor gibt die creator properties an. Der creator descriptor wird verwendet, um die Notwendigkeit zu umgehen, jede image creator instance im Speicher zu halten und multithreading-Probleme zu vermeiden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Bestimmt, ob der image creator ein neues Bild mit den `imageOptions` erstellen kann. |
| [createInstance()](#createInstance--) | Erstellt eine neue creator-Instanz. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Bestimmt, ob der image creator ein neues Bild mit den `imageOptions` erstellen kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Bildoptionen. |

**Returns:**
boolean - `true`, wenn der von diesem descriptor erstellte image creator Bilddaten mit den angegebenen `imageOptions` erstellen kann; andernfalls `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Erstellt eine neue creator-Instanz.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

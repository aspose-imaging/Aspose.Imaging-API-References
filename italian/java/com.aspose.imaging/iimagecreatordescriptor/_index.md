---
title: "IImageCreatorDescriptor"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il descrittore del creatore dell'immagine che specifica le proprietà del creatore."
type: docs
weight: 129
url: /it/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Il descrittore del creatore di immagini che specifica le proprietà del creatore. Il descrittore del creatore è usato per superare la necessità di contenere ogni istanza del creatore di immagini in memoria e i problemi di multithreading.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Determina se il creatore di immagini può creare una nuova immagine usando `imageOptions`. |
| [createInstance()](#createInstance--) | Crea una nuova istanza del creatore. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Determina se il creatore di immagini può creare una nuova immagine usando `imageOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni dell'immagine. |

**Returns:**
boolean - `true` se il creatore di immagini creato da questo descrittore può creare dati immagine usando le `imageOptions` specificate; altrimenti, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Crea una nuova istanza del creatore.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

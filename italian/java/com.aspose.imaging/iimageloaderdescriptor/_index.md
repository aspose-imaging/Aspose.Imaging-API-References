---
title: "IImageLoaderDescriptor"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il descrittore del caricatore dell'immagine che specifica le proprietà del caricatore."
type: docs
weight: 134
url: /it/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Il descrittore del caricatore di immagini che specifica le proprietà del caricatore. Il descrittore del caricatore è usato per superare la necessità di contenere ogni istanza del caricatore di immagini in memoria e i problemi di multithreading.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente usando `loadOptions`. |
| [createInstance()](#createInstance--) | Crea una nuova istanza del caricatore. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente usando `loadOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Il contenitore dello stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | I dettagli del formato file specificati da `loadOptions`. `loadOptions` può essere null. |

**Returns:**
boolean - `true` se il caricatore di immagini creato da questo descrittore può leggere l'immagine dallo stream; altrimenti, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Crea una nuova istanza del caricatore.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.

---
title: "IImageLoaderDescriptor"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El descriptor del cargador de imágenes que especifica las propiedades del cargador."
type: docs
weight: 134
url: /es/java/com.aspose.imaging/iimageloaderdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

El descriptor del cargador de imágenes que especifica las propiedades del cargador. El descriptor del cargador se utiliza para superar la necesidad de contener cada instancia del cargador de imágenes en memoria y los problemas de multihilo.
## Métodos

| Método | Descripción |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando `loadOptions`. |
| [createInstance()](#createInstance--) | Crea una nueva instancia del cargador. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando `loadOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Los detalles del formato de archivo especificados por `loadOptions`. `loadOptions` puede ser nulo. |

**Returns:**
boolean - `true` si el cargador de imágenes creado por este descriptor puede leer la imagen desde el flujo; de lo contrario, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Crea una nueva instancia del cargador.

**Returns:**
[IImageLoader](../../com.aspose.imaging/iimageloader) - A new loader instance.

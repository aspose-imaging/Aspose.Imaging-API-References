---
title: "IImageCreatorDescriptor"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El descriptor del creador de imágenes que especifica las propiedades del creador."
type: docs
weight: 129
url: /es/java/com.aspose.imaging/iimagecreatordescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

El descriptor del creador de imágenes que especifica las propiedades del creador. El descriptor del creador se utiliza para superar la necesidad de mantener cada instancia del creador de imágenes en memoria y los problemas de multihilo.
## Métodos

| Método | Descripción |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.imaging.ImageOptionsBase-) | Determina si el creador de imágenes puede crear una nueva imagen usando el `imageOptions`. |
| [createInstance()](#createInstance--) | Crea una nueva instancia del creador. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Determina si el creador de imágenes puede crear una nueva imagen usando el `imageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones de imagen. |

**Returns:**
boolean - `true` si el creador de imágenes creado por este descriptor puede generar datos de imagen usando los `imageOptions` especificados; de lo contrario, `false`.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Crea una nueva instancia del creador.

**Returns:**
[IImageCreator](../../com.aspose.imaging/iimagecreator) - A new creator instance.

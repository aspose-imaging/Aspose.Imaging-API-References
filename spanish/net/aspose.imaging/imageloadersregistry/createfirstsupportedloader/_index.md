---
title: CreateFirstSupportedLoader
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Crea el primer cargador encontrado adecuado para el especificadostream y opcionalmente elloadOptions .
type: docs
weight: 30
url: /es/net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Crea el primer cargador encontrado adecuado para el especificado*stream* y opcionalmente el*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Valor_devuelto

El cargador que soporta el especificado*stream* y*loadOptions* o nulo si no se encuentra dicho cargador.

### Observaciones

El primer cargador será en realidad el último registrado.

### Ver también

* interface [IImageLoader](../../iimageloader)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* espacio de nombres [Aspose.Imaging](../../imageloadersregistry)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

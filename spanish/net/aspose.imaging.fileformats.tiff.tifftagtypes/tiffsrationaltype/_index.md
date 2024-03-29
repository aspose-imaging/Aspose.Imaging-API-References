---
title: TiffSRationalType
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El tiff firmado tipo racional.
type: docs
weight: 8010
url: /es/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---
## TiffSRationalType class

El tiff firmado tipo racional.

```csharp
public sealed class TiffSRationalType : TiffCommonArrayType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffSRationalType](tiffsrationaltype#constructor)(TiffTags) | Inicializa una nueva instancia del[`TiffSRationalType`](../tiffsrationaltype) clase. |
| [TiffSRationalType](tiffsrationaltype#constructor_1)(ushort) | Inicializa una nueva instancia del[`TiffSRationalType`](../tiffsrationaltype) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Obtiene el tamaño de datos adicional en bytes (en caso de que los 12 bytes no sean suficientes para los datos de la etiqueta). |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count) { get; } | Obtiene el conteo de elementos. |
| [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/datasize) { get; } | Obtiene el tamaño de datos adicional en bytes (en caso de que los 12 bytes no sean suficientes para los datos de la etiqueta). |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/elementsize) { get; } | Obtiene el tamaño del elemento en bytes. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Obtiene la representación de números enteros de ID de etiqueta. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden conservarse. No se puede almacenar la etiqueta no válida. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Obtiene la etiqueta id. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/tagtype) { get; } | Obtiene el tipo de etiqueta. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/value) { get; set; } | Obtiene o establece el valor que contiene este tipo de datos. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/values) { get; set; } | Obtiene o establece los valores. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/valuescontainer) { get; } | Obtiene el contenedor de valores. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un número entero que indica si la instancia actual precede, sigue u ocurre en la misma posición en el orden de clasificación que el otro objeto. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Realiza una clonación profunda de esta instancia. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | Devuelve unString que representa esta instancia. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/writeadditionaldata)(TiffStreamWriter) | Escribe los datos adicionales de la etiqueta. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Escribe los datos de la etiqueta. |

### Ver también

* class [TiffCommonArrayType](../tiffcommonarraytype)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

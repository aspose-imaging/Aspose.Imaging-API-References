---
title: XmpPacketWrapper
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Contiene un paquete xmp serializado que incluye encabezado y tráiler.
type: docs
weight: 11800
url: /es/net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Contiene un paquete xmp serializado que incluye encabezado y tráiler.

```csharp
public class XmpPacketWrapper
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | Inicializa una nueva instancia del[`XmpPacketWrapper`](../xmppacketwrapper) clase. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Inicializa una nueva instancia del[`XmpPacketWrapper`](../xmppacketwrapper) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi) { get; } | Obtiene la instrucción de procesamiento del encabezado. |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta) { get; set; } | Obtiene el metadato XMP. Opcional. |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages) { get; } | Obtiene una matriz de[`XmpPackage`](../xmppackage) dentro de XMP. |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount) { get; } | Obtiene la cantidad de paquetes dentro de la estructura XMP. |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi) { get; } | Obtiene la instrucción de procesamiento del tráiler. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage)(XmpPackage) | Agrega el paquete. |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages)() | Elimina todo[`XmpPackage`](../xmppackage) dentro de XMP. |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage)(string) | Determina si el paquete existe en el contenedor xmp. |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage)(string) | Obtiene el paquete por URI de espacio de nombres. |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage)(XmpPackage) | Elimina el paquete XMP. |

### Observaciones

Se puede colocar un contenedor que consta de un par de instrucciones de procesamiento XML (PI) alrededor del elemento rdf:RDF.

### Ver también

* espacio de nombres [Aspose.Imaging.Xmp](../../aspose.imaging.xmp)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

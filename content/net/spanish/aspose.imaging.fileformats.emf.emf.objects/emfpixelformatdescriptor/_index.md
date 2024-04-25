---
title: EmfPixelFormatDescriptor
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto PixelFormatDescriptor se puede utilizar en los registros EMR_HEADER sección 2.3.4.2 para especificar el formato de píxel de la superficie de salida para el contexto del dispositivo de reproducción.
type: docs
weight: 3120
url: /es/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

El objeto PixelFormatDescriptor se puede utilizar en los registros EMR_HEADER (sección 2.3.4.2) para especificar el formato de píxel de la superficie de salida para el contexto del dispositivo de reproducción.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Obtiene o establece el número de planos superpuestos y subyacentes. Los bits 0 a 3 especifican hasta 15 planos superpuestos y los bits 4 a 7 especifican hasta 15 planos subyacentes |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Obtiene o establece el número de planos de bits alfa en el búfer de acumulación |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Obtiene o establece especifica el número total de planos de bits en el búfer de acumulación. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Obtiene o establece la cantidad de planos de bits azules en el búfer de acumulación. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Obtiene o establece especifica el número de planos de bits verdes en la acumulación |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Obtiene o establece la cantidad de planos de bits rojos en el búfer de acumulación |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Obtiene o establece Especifica el número de planos de bits alfa en cada búfer de color RGBA |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Obtiene o establece Especifica el recuento de desplazamiento para planos de bits alfa en cada búfer de color RGBA |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Obtiene o establece especifica el número de búferes auxiliares. Los búferes auxiliares no son compatibles |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | Obtiene o establece Especifica el número de planos de bits azules en cada búfer de color RGBA. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | Obtiene o establece Especifica el recuento de desplazamiento para planos de bits azules en cada búfer de color RGBA. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | Obtiene o establece el número de bits por píxel para los tipos de píxeles RGBA, sin incluir los planos de bits alfa. Para los píxeles de la tabla de colores, es el tamaño de cada tabla de colores index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | Obtiene o establece la profundidad del búfer de profundidad (eje z). |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | Obtiene o establece Especifica el número de planos de bits verdes en cada búfer de color RGBA |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | Obtiene o establece Especifica el recuento de desplazamiento para planos de bits verdes en cada búfer de color RGBA. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | Obtiene o establece Especifica el número de planos de bits rojos en cada búfer de color RGBA |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | Obtiene o establece Especifica el recuento de desplazamiento en bits para planos de bits rojos en cada búfer de color RGBA. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | Obtiene o establece la profundidad del búfer de la plantilla. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | Obtiene o establece Este campo PUEDE ser ignorado |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | Obtiene o establece indicadores de bits que especifican las propiedades del búfer de píxeles que se usa para la salida a la superficie de dibujo. Estas propiedades no son todas mutuamente exclusivas; se permiten combinaciones de banderas, excepto donde se indique lo contrario. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | Obtiene o establece Este campo PUEDE ser ignorado. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Obtiene o establece especifica el color transparente o el índice de un plano subyacente. Cuando el tipo de píxel es RGBA, dwVisibleMask es un valor de color RGB transparente. Cuando el tipo de píxel es índice de color, es un valor de índice transparente. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | Obtiene o establece Este campo PUEDE ser ignorado |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | Obtiene o establece el tipo de píxel data PFD_TYPE_RGBA 0x00 El formato de píxel es RGBA. PFD_TYPE_COLORINDEX 0x01 Cada píxel es un índice en una tabla de colores. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | Obtiene o establece un entero de 16 bits que especifica el tamaño, en bytes, de esta estructura de datos. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | Obtiene o establece un entero de 16 bits que DEBE establecerse en 0x0001. |

### Ver también

* class [EmfObject](../emfobject)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

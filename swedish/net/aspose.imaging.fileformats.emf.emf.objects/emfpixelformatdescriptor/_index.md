---
title: EmfPixelFormatDescriptor
second_title: Aspose.Imaging för .NET API-referens
description: PixelFormatDescriptor-objektet kan användas i EMR_HEADER-poster avsnitt 2.3.4.2 för att specificera pixelformatet för utdataytan för uppspelningsenhetskontexten.
type: docs
weight: 3120
url: /sv/net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

PixelFormatDescriptor-objektet kan användas i EMR_HEADER-poster (avsnitt 2.3.4.2) för att specificera pixelformatet för utdataytan för uppspelningsenhetskontexten.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Gets eller sets anger antalet överläggs- och underläggsplan. Bitarna 0 till 3 anger upp till 15 överlagringsplan och bitar 4 till 7 anger upp till 15 underliggande planes |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Gets eller sets specificerar antalet alfabitplan i ackumuleringsbufferten |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Gets eller sets specificerar det totala antalet bitplan i ackumuleringsbufferten. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Gets eller sets specificerar antalet blå bitplan i ackumuleringsbufferten. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Gets eller sets specificerar antalet gröna bitplan i ackumulation |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Gets eller sets specificerar antalet röda bitplan i ackumuleringsbufferten |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Gets eller sets Anger antalet alfabitplan i varje RGBA-färgbuffert |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Hämtar eller sätter Anger skifträkningen för alfabitplan i varje RGBA-färgbuffert |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Gets eller sets anger antalet extra buffertar. Hjälpbuffertar stöds inte |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | Hämtar eller sätter Anger antalet blå bitplan i varje RGBA-färgbuffert. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | Hämtar eller sätter Anger skifträkningen för blå bitplan i varje RGBA-färgbuffert. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | Hämtar eller ställer in antalet bitar per pixel för RGBA-pixeltyper, exklusive alfabitplanen. För färgtabellpixlar är det storleken på varje färgtabell index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | Gets eller sets specificerar djupet på djupbufferten (z-axeln). |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | Gets eller sets Anger antalet gröna bitplan i varje RGBA-färgbuffert |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | Hämtar eller sätter Anger skifträkningen för gröna bitplan i varje RGBA-färgbuffert. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | Gets eller sets Anger antalet röda bitplan i varje RGBA-färgbuffert |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | Hämtar eller sätter Anger skiftantalet i bitar för röda bitplan i varje RGBA-färgbuffert. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | Gets eller sets anger djupet på stencilbufferten. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | Hämtar eller sätter Det här fältet KAN ignoreras |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | Hämtar eller ställer in bitflaggor som anger egenskaperna för pixelbufferten som används för utmatning till ritytan. Dessa egenskaper är inte alla ömsesidigt exklusiva; kombinationer av flaggor är tillåtna, om inte annat anges. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | Hämtar eller sätter Det här fältet KAN ignoreras. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Gets eller sets specificerar den transparenta färgen eller indexet för ett underlagsplan. När pixeltypen är RGBA är dwVisibleMask ett transparent RGB-färgvärde. När pixeltypen är färgindex är det ett transparent indexvärde. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | Hämtar eller sätter Det här fältet KAN ignoreras |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | Hämtar eller ställer in typen av pixeldata PFD_TYPE_RGBA 0x00 Pixelformatet är RGBA. PFD_TYPE_COLORINDEX 0x01 Varje pixel är ett index i en färgtabell. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | Hämtar eller ställer in ett 16-bitars heltal som anger storleken, i byte, av denna datastruktur. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | Hämtar eller ställer in ett 16-bitars heltal som MÅSTE sättas till 0x0001. |

### Se även

* class [EmfObject](../emfobject)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

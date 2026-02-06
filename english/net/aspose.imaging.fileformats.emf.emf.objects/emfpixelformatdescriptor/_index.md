---
title: Class EmfPixelFormatDescriptor
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfPixelFormatDescriptor class. The PixelFormatDescriptor object can be used in EMR_HEADER records section 2.3.4.2 to specify the pixel format of the output surface for the playback device context
type: docs
weight: 3210
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved/) { get; set; } | Gets or sets specifies the number of overlay and underlay planes. Bits 0 through 3 specify up to 15 overlay planes and bits 4 through 7 specify up to 15 underlay planes |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits/) { get; set; } | Gets or sets specifies the number of alpha bitplanes in the accumulation buffer |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits/) { get; set; } | Gets or sets specifies the total number of bitplanes in the accumulation buffer. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits/) { get; set; } | Gets or sets specifies the number of blue bitplanes in the accumulation buffer. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits/) { get; set; } | Gets or sets specifies the number of green bitplanes in the accumulation |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits/) { get; set; } | Gets or sets specifies the number of red bitplanes in the accumulation buffer |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits/) { get; set; } | Gets or sets Specifies the number of alpha bitplanes in each RGBA color buffer |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift/) { get; set; } | Gets or sets Specifies the shift count for alpha bitplanes in each RGBA color buffer |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers/) { get; set; } | Gets or sets specifies the number of auxiliary buffers. Auxiliary buffers are not supported |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits/) { get; set; } | Gets or sets Specifies the number of blue bitplanes in each RGBA color buffer. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift/) { get; set; } | Gets or sets Specifies the shift count for blue bitplanes in each RGBA color buffer. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits/) { get; set; } | Gets or sets the number of bits per pixel for RGBA pixel types, excluding the alpha bitplanes. For color table pixels, it is the size of each color table index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits/) { get; set; } | Gets or sets specifies the depth of the depth (z-axis) buffer. |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits/) { get; set; } | Gets or sets Specifies the number of green bitplanes in each RGBA color buffer |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift/) { get; set; } | Gets or sets Specifies the shift count for green bitplanes in each RGBA color buffer. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits/) { get; set; } | Gets or sets Specifies the number of red bitplanes in each RGBA color buffer |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift/) { get; set; } | Gets or sets Specifies the shift count in bits for red bitplanes in each RGBA color buffer. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits/) { get; set; } | Gets or sets specifies the depth of the stencil buffer. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask/) { get; set; } | Gets or sets This field MAY be ignored |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags/) { get; set; } | Gets or sets bit flags that specify properties of the pixel buffer that is used for output to the drawing surface. These properties are not all mutually exclusive; combinations of flags are allowed, except where noted otherwise. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask/) { get; set; } | Gets or sets This field MAY be ignored. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask/) { get; set; } | Gets or sets specifies the transparent color or index of an underlay plane. When the pixel type is RGBA, dwVisibleMask is a transparent RGB color value. When the pixel type is color index, it is a transparent index value. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype/) { get; set; } | Gets or sets This field MAY be ignored |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype/) { get; set; } | Gets or sets the type of pixel data PFD_TYPE_RGBA 0x00 The pixel format is RGBA. PFD_TYPE_COLORINDEX 0x01 Each pixel is an index in a color table. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize/) { get; set; } | Gets or sets a 16-bit integer that specifies the size, in bytes, of this data structure. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion/) { get; set; } | Gets or sets a 16-bit integer that MUST be set to 0x0001. |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)



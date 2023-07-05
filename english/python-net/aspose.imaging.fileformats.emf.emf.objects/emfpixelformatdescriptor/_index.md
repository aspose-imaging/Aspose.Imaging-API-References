---
title: EmfPixelFormatDescriptor Class
type: docs
weight: 220
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPixelFormatDescriptor type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPixelFormatDescriptor()|Initializes a new instance of the EmfPixelFormatDescriptor class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|n_size|Gets or sets a 16-bit integer that specifies the size, in bytes, of this data structure.|
|n_version|Gets or sets a 16-bit integer that MUST be set to 0x0001.|
|dw_flags|Gets or sets bit flags that specify properties of the pixel buffer that is used <br/>            for output to the drawing surface. These properties are not all mutually <br/>            exclusive; combinations of flags are allowed, except where noted otherwise.|
|pixel_type|Gets or sets the type of pixel data<br/>            PFD_TYPE_RGBA       0x00 The pixel format is RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Each pixel is an index in a color table.|
|c_color_bits|Gets or sets the number of bits per pixel for RGBA pixel types, excluding the alpha bitplanes. For color table pixels, it is the size of each color table index|
|c_red_bits|Gets or sets  Specifies the number of red bitplanes in each RGBA color buffer|
|c_red_shift|Gets or sets  Specifies the shift count in bits for red bitplanes in each RGBA color buffer.|
|c_green_bits|Gets or sets  Specifies the number of green bitplanes in each RGBA color buffer|
|c_green_shift|Gets or sets  Specifies the shift count for green bitplanes in each RGBA color buffer.|
|c_blue_bits|Gets or sets  Specifies the number of blue bitplanes in each RGBA color buffer.|
|c_blue_shift|Gets or sets  Specifies the shift count for blue bitplanes in each RGBA color buffer.|
|c_alpha_bits|Gets or sets  Specifies the number of alpha bitplanes in each RGBA color buffer|
|c_alpha_shift|Gets or sets Specifies the shift count for alpha bitplanes in each RGBA color buffer|
|c_accum_bits|Gets or sets specifies the total number of bitplanes in the accumulation buffer.|
|c_accum_red_bits|Gets or sets specifies the number of red bitplanes in the accumulation buffer|
|c_accum_green_bits|Gets or sets specifies the number of green bitplanes in the accumulation|
|c_accum_blue_bits|Gets or sets specifies the number of blue bitplanes in the accumulation buffer.|
|c_accum_alpha_bits|Gets or sets specifies the number of alpha bitplanes in the accumulation buffer|
|c_depth_bits|Gets or sets specifies the depth of the depth (z-axis) buffer.|
|c_stencil_bits|Gets or sets specifies the depth of the stencil buffer.|
|c_aux_buffers|Gets or sets specifies the number of auxiliary buffers. Auxiliary buffers are not supported|
|layer_type|Gets or sets This field MAY be ignored|
|b_reserved|Gets or sets specifies the number of overlay and underlay planes. Bits 0 through 3 specify <br/>            up to 15 overlay planes and bits 4 through 7 specify up to 15 underlay planes|
|dw_layer_mask|Gets or sets This field MAY be ignored.|
|dw_visible_mask|Gets or sets specifies the transparent color or index of an underlay plane. When the pixel <br/>            type is RGBA, dwVisibleMask is a transparent RGB color value. When the pixel <br/>            type is color index, it is a transparent index value.|
|dw_damage_mask|Gets or sets This field MAY be ignored|

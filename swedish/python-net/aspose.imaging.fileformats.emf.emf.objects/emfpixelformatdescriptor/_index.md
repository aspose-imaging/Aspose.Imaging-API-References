---
title: "EmfPixelFormatDescriptor‑klass"
type: docs
weight: 220
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | Initierar en ny instans av EmfPixelFormatDescriptor‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Hämtar eller anger specificerar antalet overlay‑ och underlay‑plan. Bit 0 till 3 specificerar <br/>            upp till 15 overlay‑plan och bit 4 till 7 specificerar upp till 15 underlay‑plan. |
| c_accum_alpha_bits | System.Byte | r/w | Hämtar eller anger specificerar antalet alfa‑bitplan i ackumuleringsbufferten. |
| c_accum_bits | System.Byte | r/w | Hämtar eller anger det totala antalet bitplan i ackumuleringsbufferten. |
| c_accum_blue_bits | System.Byte | r/w | Hämtar eller anger antalet blåa bitplan i ackumuleringsbufferten. |
| c_accum_green_bits | System.Byte | r/w | Hämtar eller anger antalet gröna bitplan i ackumuleringen. |
| c_accum_red_bits | System.Byte | r/w | Hämtar eller anger antalet röda bitplan i ackumuleringsbufferten. |
| c_alpha_bits | System.Byte | r/w | Hämtar eller anger antalet alfa‑bitplan i varje RGBA‑färgbuffert. |
| c_alpha_shift | System.Byte | r/w | Hämtar eller anger skiftantalet för alfa‑bitplan i varje RGBA‑färgbuffert. |
| c_aux_buffers | System.Byte | r/w | Hämtar eller anger antalet hjälpbuffertar. Hjälpbuffertar stöds inte. |
| c_blue_bits | System.Byte | r/w | Hämtar eller anger antalet blåa bitplan i varje RGBA‑färgbuffert. |
| c_blue_shift | System.Byte | r/w | Hämtar eller anger skiftantalet för blåa bitplan i varje RGBA‑färgbuffert. |
| c_color_bits | System.Byte | r/w | Hämtar eller anger antalet bitar per pixel för RGBA‑pixelformer, exklusive alfa‑bitplan. För färgtabell‑pixlar är det storleken på varje färgtabell‑index. |
| c_depth_bits | System.Byte | r/w | Hämtar eller anger djupet på djupbufferten (z‑axeln). |
| c_green_bits | System.Byte | r/w | Hämtar eller anger antalet gröna bitplan i varje RGBA‑färgbuffert. |
| c_green_shift | System.Byte | r/w | Hämtar eller anger  Anger förskjutningsantalet för gröna bitplan i varje RGBA-färgbuffer. |
| c_red_bits | System.Byte | r/w | Hämtar eller anger  Anger antalet röda bitplan i varje RGBA-färgbuffer |
| c_red_shift | System.Byte | r/w | Hämtar eller anger  Anger förskjutningsantalet i bitar för röda bitplan i varje RGBA-färgbuffer. |
| c_stencil_bits | System.Byte | r/w | Hämtar eller anger anger djupet på stencilbufferten. |
| dw_damage_mask | int | r/w | Hämtar eller anger Detta fält KAN ignoreras |
| dw_flags | int | r/w | Hämtar eller anger bitflaggor som specificerar egenskaperna för pixelbufferten som används <br/>            för utskrift till ritytan. Dessa egenskaper är inte alla ömsesidigt <br/>            uteslutande; kombinationer av flaggor är tillåtna, förutom där annat anges. |
| dw_layer_mask | int | r/w | Hämtar eller anger Detta fält KAN ignoreras. |
| dw_visible_mask | int | r/w | Hämtar eller anger anger den transparenta färgen eller indexet för ett underliggande plan. När pixel <br/>            typen är RGBA, är dwVisibleMask ett transparent RGB-färgvärde. När pixel <br/>            typen är färgindex, är det ett transparent indexvärde. |
| layer_type | System.Byte | r/w | Hämtar eller anger Detta fält KAN ignoreras |
| n_size | int | r/w | Hämtar eller anger ett 16-bitars heltal som specificerar storleken, i byte, för denna datastruktur. |
| n_version | int | r/w | Hämtar eller anger ett 16-bitars heltal som MÅSTE sättas till 0x0001. |
| pixel_type | System.Byte | r/w | Hämtar eller anger typen av pixeldata<br/>            PFD_TYPE_RGBA       0x00 Pixelformatet är RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Varje pixel är ett index i en färgtabell. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

Initierar en ny instans av EmfPixelFormatDescriptor‑klassen


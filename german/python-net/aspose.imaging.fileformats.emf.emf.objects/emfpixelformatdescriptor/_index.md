---
title: "Klasse EmfPixelFormatDescriptor"
type: docs
weight: 220
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | Initialisiert eine neue Instanz der Klasse EmfPixelFormatDescriptor |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Liest oder setzt gibt die Anzahl der Overlay‑ und Underlay‑Ebenen an. Bits 0 bis 3 geben <br/>            bis zu 15 Overlay‑Ebenen an und Bits 4 bis 7 geben bis zu 15 Underlay‑Ebenen an. |
| c_accum_alpha_bits | System.Byte | r/w | Liest oder setzt gibt die Anzahl der Alpha‑Bitebenen im Akkumulationspuffer an. |
| c_accum_bits | System.Byte | r/w | Liest oder setzt die Gesamtzahl der Bitplanes im Akkumulationspuffer. |
| c_accum_blue_bits | System.Byte | r/w | Liest oder setzt die Anzahl der blauen Bitplanes im Akkumulationspuffer. |
| c_accum_green_bits | System.Byte | r/w | Liest oder setzt die Anzahl der grünen Bitplanes in der Akkumulation. |
| c_accum_red_bits | System.Byte | r/w | Liest oder setzt die Anzahl der roten Bitplanes im Akkumulationspuffer. |
| c_alpha_bits | System.Byte | r/w | Liest oder setzt die Anzahl der Alpha-Bitplanes in jedem RGBA-Farbpuffer. |
| c_alpha_shift | System.Byte | r/w | Liest oder setzt die Verschiebungsanzahl für Alpha-Bitplanes in jedem RGBA-Farbpuffer. |
| c_aux_buffers | System.Byte | r/w | Liest oder setzt die Anzahl der Hilfspuffer. Hilfspuffer werden nicht unterstützt. |
| c_blue_bits | System.Byte | r/w | Liest oder setzt die Anzahl der blauen Bitplanes in jedem RGBA-Farbpuffer. |
| c_blue_shift | System.Byte | r/w | Liest oder setzt die Verschiebungsanzahl für blaue Bitplanes in jedem RGBA-Farbpuffer. |
| c_color_bits | System.Byte | r/w | Liest oder setzt die Anzahl der Bits pro Pixel für RGBA-Pixeltypen, ohne die Alpha-Bitplanes. Für Farbtabelle-Pixel ist dies die Größe jedes Farbtabelle-Index. |
| c_depth_bits | System.Byte | r/w | Liest oder setzt die Tiefe des Tiefenpuffers (z-Achse). |
| c_green_bits | System.Byte | r/w | Liest oder setzt die Anzahl der grünen Bitplanes in jedem RGBA-Farbpuffer. |
| c_green_shift | System.Byte | r/w | Liest oder setzt  Gibt die Verschiebungsanzahl für grüne Bitebenen in jedem RGBA-Farbpuffer an. |
| c_red_bits | System.Byte | r/w | Liest oder setzt  Gibt die Anzahl der roten Bitebenen in jedem RGBA-Farbpuffer an |
| c_red_shift | System.Byte | r/w | Liest oder setzt  Gibt die Verschiebungsanzahl in Bits für rote Bitebenen in jedem RGBA-Farbpuffer an. |
| c_stencil_bits | System.Byte | r/w | Liest oder setzt gibt die Tiefe des Stencil-Puffers an. |
| dw_damage_mask | int | r/w | Liest oder setzt Dieses Feld KANN ignoriert werden |
| dw_flags | int | r/w | Liest oder setzt Bit‑Flags, die Eigenschaften des Pixelpuffers angeben, der <br/>            für die Ausgabe auf die Zeichenfläche verwendet wird. Diese Eigenschaften sind nicht alle gegenseitig <br/>            exklusiv; Kombinationen von Flags sind zulässig, außer wo anders angegeben. |
| dw_layer_mask | int | r/w | Liest oder setzt Dieses Feld KANN ignoriert werden. |
| dw_visible_mask | int | r/w | Liest oder setzt gibt die transparente Farbe oder den Index einer Unterlage‑Ebene an. Wenn der Pixel <br/>            Typ RGBA ist, ist dwVisibleMask ein transparenter RGB‑Farbwert. Wenn der Pixel <br/>            Typ ein Farbindex ist, ist es ein transparenter Indexwert. |
| layer_type | System.Byte | r/w | Liest oder setzt Dieses Feld KANN ignoriert werden |
| n_size | int | r/w | Liest oder setzt eine 16‑Bit‑Ganzzahl, die die Größe, in Bytes, dieser Datenstruktur angibt. |
| n_version | int | r/w | Liest oder setzt eine 16‑Bit‑Ganzzahl, die AUF 0x0001 gesetzt werden MUSS. |
| pixel_type | System.Byte | r/w | Liest oder setzt den Typ der Pixeldaten<br/>            PFD_TYPE_RGBA       0x00 Das Pixelformat ist RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Jeder Pixel ist ein Index in einer Farbpalette. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

Initialisiert eine neue Instanz der Klasse EmfPixelFormatDescriptor


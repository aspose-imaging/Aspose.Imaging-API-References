---
title: EmfPixelFormatDescriptor
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das PixelFormatDescriptor-Objekt kann in EMR_HEADER-Datensätzen Abschnitt 2.3.4.2 verwendet werden um das Pixelformat der Ausgabeoberfläche für den Kontext des Wiedergabegeräts anzugeben.
type: docs
weight: 3120
url: /de/net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

Das PixelFormatDescriptor-Objekt kann in EMR_HEADER-Datensätzen (Abschnitt 2.3.4.2) verwendet werden, um das Pixelformat der Ausgabeoberfläche für den Kontext des Wiedergabegeräts anzugeben.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Ruft ab oder setzt die Anzahl der Overlay- und Underlay-Ebenen. Die Bits 0 bis 3 spezifizieren bis zu 15 Overlay-Ebenen und die Bits 4 bis 7 spezifizieren bis zu 15 Underlay-Ebenen |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Erhält oder setzt die Anzahl der Alpha-Bitebenen im Akkumulationspuffer |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Ruft ab oder setzt die Gesamtzahl der Bitplanes im Akkumulationspuffer. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Ruft ab oder legt fest, wie viele blaue Bitebenen im Akkumulationspuffer vorhanden sind. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Erhält oder setzt die Anzahl der grünen Bitplanes in der Akkumulation |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Erhält oder setzt die Anzahl der roten Bitplanes im Akkumulationspuffer |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Ruft ab oder legt fest Gibt die Anzahl der Alpha-Bitebenen in jedem RGBA-Farbpuffer an |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Ruft ab oder legt fest Gibt die Verschiebungsanzahl für Alpha-Bitebenen in jedem RGBA-Farbpuffer an |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Ruft ab oder setzt die Anzahl der Hilfspuffer. Hilfspuffer werden nicht unterstützt |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | Ruft ab oder legt fest Gibt die Anzahl der blauen Bitplanes in jedem RGBA-Farbpuffer an. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | Ruft ab oder legt fest Gibt die Verschiebungsanzahl für blaue Bitebenen in jedem RGBA-Farbpuffer an. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | Ruft die Anzahl der Bits pro Pixel für RGBA-Pixeltypen ab oder legt sie fest, ausgenommen die Alpha-Bitebenen. Bei Farbtabellenpixeln ist dies die Größe jeder Farbtabelle index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | Ruft ab oder legt die Tiefe des Tiefenpuffers (Z-Achse) fest. |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | Ruft ab oder legt fest Gibt die Anzahl grüner Bitplanes in jedem RGBA-Farbpuffer an |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | Ruft ab oder legt fest Gibt die Verschiebungsanzahl für grüne Bitplanes in jedem RGBA-Farbpuffer an. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | Ruft ab oder legt fest Gibt die Anzahl der roten Bitplanes in jedem RGBA-Farbpuffer an |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | Ruft ab oder legt fest Gibt die Verschiebungsanzahl in Bits für rote Bitebenen in jedem RGBA-Farbpuffer an. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | Ruft ab oder legt die Tiefe des Schablonenpuffers fest. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | Ruft ab oder setzt Dieses Feld KANN ignoriert werden |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | Ruft Bit-Flags ab oder setzt diese, die Eigenschaften des Pixelpuffers spezifizieren, der für die Ausgabe an die Zeichenoberfläche verwendet wird. Diese Eigenschaften schließen sich nicht alle gegenseitig aus; Kombinationen von Flags sind zulässig, sofern nicht anders angegeben. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | Ruft ab oder setzt Dieses Feld KANN ignoriert werden. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Ruft ab oder setzt die transparente Farbe oder den Index einer Unterlageebene. Wenn der Typ des Pixels RGBA ist, ist dwVisibleMask ein transparenter RGB-Farbwert. Wenn der Pixeltyp ein Farbindex ist, handelt es sich um einen transparenten Indexwert. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | Ruft ab oder setzt Dieses Feld KANN ignoriert werden |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | Holt oder setzt den Typ der Pixeldaten PFD_TYPE_RGBA 0x00 Das Pixelformat ist RGBA. PFD_TYPE_COLORINDEX 0x01 Jedes Pixel ist ein Index in einer Farbtabelle. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | Ruft eine 16-Bit-Ganzzahl ab oder legt diese fest, die die Größe dieser Datenstruktur in Byte angibt. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | Erhält oder setzt eine 16-Bit-Ganzzahl, die auf 0x0001 gesetzt werden MUSS. |

### Siehe auch

* class [EmfObject](../emfobject)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

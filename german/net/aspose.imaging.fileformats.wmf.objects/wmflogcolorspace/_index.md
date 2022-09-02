---
title: WmfLogColorSpace
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das LogColorSpace-Objekt gibt einen logischen Farbraum für den Kontext des Wiedergabegeräts an der der Name eines Farbprofils in ASCII-Zeichen sein kann.
type: docs
weight: 8750
url: /de/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

Das LogColorSpace-Objekt gibt einen logischen Farbraum für den Kontext des Wiedergabegeräts an, der der Name eines Farbprofils in ASCII-Zeichen sein kann.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die den Typ des Farbraums angibt. Es MUSS im LogicalColorSpace enumeration (Abschnitt 2.1.1.14) definiert werden. Wenn dieser Wert LCS_sRGB oder LCS_WINDOWS_COLOR_SPACE ist, MUSS der sRGB-Farbraum verwendet werden. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Erhält oder setzt ein CIEXYZTriple-Objekt (Abschnitt 2.2.2.7), das die CIE-Chromatizität x-, y- und z-Koordinaten der drei Farben definiert, die dem RGB entsprechenendpoints für den Farbraum logical , der der Bitmap zugeordnet ist. Wenn die [`ColorSpaceType`](./colorspacetype) Feld nicht spezifiziert LCS_CALIBRATED_RGB, dieses Feld MUSS ignoriert werden. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Ruft eine optionale ASCII-Zeichenfolge ab oder legt diese fest, die den -Namen einer Datei angibt, die ein Farbprofil enthält. Wenn ein Dateiname is angegeben ist und die[`ColorSpaceType`](./colorspacetype) Feld auf LCS_CALIBRATED_RGB gesetzt ist, SOLLTEN die anderen Felder dieser Struktur ignoriert werden. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Ruft einen 32-Bit-Festkommawert ab oder legt ihn fest, der die getönte -Antwortkurve für Blau definiert. Wenn die[`ColorSpaceType`](./colorspacetype) field gibt LCS_CALIBRATED_RGB nicht an, dieses Feld MUSS ignoriert werden. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Ruft einen 32-Bit-Festkommawert ab oder legt ihn fest, der die getönte -Antwortkurve für Grün definiert. Wenn die[`ColorSpaceType`](./colorspacetype) field gibt LCS_CALIBRATED_RGB nicht an, dieses Feld MUSS ignoriert werden. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Ruft einen 32-Bit-Festkommawert ab oder legt ihn fest, der die getönte -Antwortkurve für Rot definiert. Wenn die[`ColorSpaceType`](./colorspacetype) field gibt LCS_CALIBRATED_RGB nicht an, dieses Feld MUSS ignoriert werden. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Ruft eine vorzeichenbehaftete 32-Bit-Ganzzahl ab oder legt diese fest, die die Farbraumzuordnungsabsicht definiert. Es MUSS in der GamutMappingIntent-Enumeration (Abschnitt 2.1.1.11). definiert werden. |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die the angibt.signature von Farbraumobjekten; es MUSS auf den Wert 0x50534F43 gesetzt werden, was die ASCII-Codierung der Zeichenfolge "PSOC". ist. |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die the definiertsize dieses Objekts in Bytes. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die a definiertversion Nummer; es MUSS 0x00000400. sein |

### Bemerkungen

Die Felder Endpoints, GammaRed, GammaGreen und GammaBlue werden verwendet, um einen logischen Farbraum anzugeben. Das Endpoints-Feld ist ein CIEXYZTriple -Objekt, das die x-, y- und z-Werte des RGB-Endpunkts des -Farbraums enthält. Die Beziehung zwischen Tri-Stimulus-Werten X, Y, Z und Chromatizitätswerten x, y, z wird wie folgt ausgedrückt. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) Die Felder GammaRed, GammaGreen und GammaBlue enthalten Werte in „8,8 Festkomma“ -Format, das eine Technik für ist, die nicht ganzzahlige Zahlen darstellt. Jeder Wert besteht aus einer nullerweiterten 8-Bit-Größe, gefolgt von einem 8-Bit-Bruchteil, wobei die kombinierten 16 Bits um 8 Bit nach links verschoben sind. Somit ist in 32-Bit der reale Wert NF 00000000nnnnnnnnffffffff00000000, wobei „nnnnnnnn“ und „ffffffff“ jeweils binäre Darstellungen von N und F sind. For example, for the real number 10.5, nnnnnnnn would be 00001010 (binary 10) and ffffffff would be 00000101 (binary 5), and the complete 32-bit binary value would be 00000000000010100000010100000000, which is the hexadecimal value 0x0A50.

### Siehe auch

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* namensraum [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

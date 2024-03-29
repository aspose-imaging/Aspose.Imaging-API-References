---
title: EmfPlusPathPointFlags
second_title: Aspose.Imaging für .NET-API-Referenz
description: Eine 32-Bit-Ganzzahl ohne Vorzeichen die angibt wie die Punkte und zugehörigen Punkttypen interpretiert werden die von diesem Objekt definiert werden. C 1 Bit Wenn gesetzt gibt das PathPoints-Array absolute Positionen im Koordinatenraum mit einer 16-Bit-Ganzzahl an Koordinaten. Wenn es leer ist gibt das PathPoints-Array absolute Positionen im Koordinatenraum mit 32-Bit-Gleitkommakoordinaten an. Hinweis Wenn das P-Flag unten gesetzt ist KANN dieses Flag leer sein und MUSS ignoriert werden. R  1 Bit Wenn gesetzt werden die Punkttypen im PathPointTypes-Array durch EmfPlusPathPointTypeRle-Objekte Abschnitt 2.2.2.32  die Run-Length-Encoding-Komprimierung RLE verwenden und/oder EmfPlusPathPointType-Objekte Abschnitt 2.2.2.31 angegeben. Siehe MS-WMF Abschnitt 3.1.6 für weitere Informationen zur RLE-Komprimierung. Wenn klar werden die Punkttypen im PathPointTypes-Array durch EmfPlusPathPointType-Objekte spezifiziert. P 1 Bit Wenn gesetzt jedes Element im PathPoints-Array gibt eine Position im Koordinatenraum an die relativ zu der -Position ist die durch das vorherige Element im Array angegeben ist. Im Fall des ersten Elements in PathPoints wird eine vorherige Position bei den Koordinaten 00 angenommen. Wenn es leer ist gibt jedes Element im PathPoints-Array eine absolute Position an.
type: docs
weight: 4960
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

Eine 32-Bit-Ganzzahl ohne Vorzeichen, die angibt, wie die Punkte und zugehörigen Punkttypen interpretiert werden, die von diesem Objekt definiert werden. C (1 Bit): Wenn gesetzt, gibt das PathPoints-Array absolute Positionen im Koordinatenraum mit einer 16-Bit-Ganzzahl an Koordinaten. Wenn es leer ist, gibt das PathPoints-Array absolute Positionen im Koordinatenraum mit 32-Bit-Gleitkommakoordinaten an. Hinweis Wenn das P-Flag (unten) gesetzt ist, KANN dieses Flag leer sein und MUSS ignoriert werden. R ( 1 Bit): Wenn gesetzt, werden die Punkttypen im PathPointTypes-Array durch EmfPlusPathPointTypeRle-Objekte (Abschnitt 2.2.2.32), , die Run-Length-Encoding-Komprimierung (RLE) verwenden, und/oder EmfPlusPathPointType-Objekte (Abschnitt 2.2.2.31) angegeben. Siehe [MS-WMF] Abschnitt 3.1.6 für weitere Informationen zur RLE-Komprimierung. Wenn klar, werden die Punkttypen im PathPointTypes-Array durch EmfPlusPathPointType-Objekte spezifiziert. P (1 Bit): Wenn gesetzt, jedes Element im PathPoints-Array gibt eine Position im Koordinatenraum an, die relativ zu der -Position ist, die durch das vorherige Element im Array angegeben ist. Im Fall des ersten Elements in PathPoints wird eine vorherige Position bei den Koordinaten (0,0) angenommen. Wenn es leer ist, gibt jedes Element im PathPoints-Array eine absolute Position an.

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| C | `4000` | Die c-Flagge |
| R | `1000` | Die r-Flagge |
| P | `800` | Die p-Flagge |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

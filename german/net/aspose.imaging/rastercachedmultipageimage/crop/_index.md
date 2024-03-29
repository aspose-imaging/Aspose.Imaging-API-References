---
title: Crop
second_title: Aspose.Imaging für .NET-API-Referenz
description: Bild zuschneiden.
type: docs
weight: 200
url: /de/net/aspose.imaging/rastercachedmultipageimage/crop/
---
## Crop(Rectangle) {#crop}

Bild zuschneiden.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck. |

### Siehe auch

* struct [Rectangle](../../rectangle)
* class [RasterCachedMultipageImage](../../rastercachedmultipageimage)
* namensraum [Aspose.Imaging](../../rastercachedmultipageimage)
* Montage [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Bild mit Verschiebungen zuschneiden.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | Int32 | Die Linksverschiebung. |
| rightShift | Int32 | Die richtige Verschiebung. |
| topShift | Int32 | Die Top-Schicht. |
| bottomShift | Int32 | Die untere Schicht. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Rechteck falsch. - Rectangle or Rectangle muss in den Bildgrenzen enthalten sein. - Rechteck |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception) | Bild kann nicht zugeschnitten werden. Bildindex: " + frameIndex or Bild kann nicht zugeschnitten werden. |

### Siehe auch

* class [RasterCachedMultipageImage](../../rastercachedmultipageimage)
* namensraum [Aspose.Imaging](../../rastercachedmultipageimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

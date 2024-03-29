---
title: EmfPlusBlurEffect
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das BlurEffect-Objekt gibt eine Verringerung des Intensitätsunterschieds zwischen Pixeln in einem Bild an.
type: docs
weight: 5220
url: /de/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
## EmfPlusBlurEffect class

Das BlurEffect-Objekt gibt eine Verringerung des Intensitätsunterschieds zwischen Pixeln in einem Bild an.

```csharp
public sealed class EmfPlusBlurEffect : EmfPlusImageEffectsObjectType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusBlurEffect](emfplusblureffect)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlurRadius](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/blurradius) { get; set; } | Erhält oder setzt eine 32-Bit-Gleitkommazahl, die den Unschärferadius in Pixel angibt, die die Anzahl der Pixel bestimmt, die bei der Berechnung des neuen Werts eines bestimmten Pixels berücksichtigt werden. Dieser Wert MUSS im Bereich von 0,0 bis 255,0 liegen. |
| [ExpandEdge](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/expandedge) { get; set; } | Ruft einen booleschen 32-Bit-Wert ab oder legt ihn fest, der angibt, ob die Bitmap um um einen Betrag erweitert wird, der dem Wert von BlurRadius entspricht, um weiche Kanten zu erzeugen. Dieser Wert MUSS einer der folgenden sein: FALSE 0x00000000 Die Größe der Bitmap DARF NICHT geändert werden, und ihre weichen Ränder SOLLTEN auf die Größe des BlurRadius beschnitten werden. TRUE 0x00000001 Die Größe der Bitmap soll um einen Betrag erweitert werden der BlurRadius to erzeugt weiche Kanten. |

### Siehe auch

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

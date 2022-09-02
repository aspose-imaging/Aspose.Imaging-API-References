---
title: ImageAttributes
second_title: Aspose.Imaging für .NET-API-Referenz
description: EinImageAttributes./imageattributes -Objekt enthält Informationen darüber wie Bitmap- und Metadateifarben während des Renderns manipuliert werden. EinImageAttributes./imageattributes-Objekt verwaltet mehrere Farbanpassungseinstellungen darunter Farbanpassungsmatrizen Graustufenanpassungsmatrizen Gammakorrekturwerte Farbabbildungstabellen und Farbschwellenwerte. Während des Renderns können Farben korrigiert abgedunkelt aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden initialisieren Sie eineImageAttributes./imageattributes Objekt und passiere den Pfad davonImageAttributes./imageattributes Objekt zusammen mit dem Pfad einerImage./image  an die DrawImage-Methode.
type: docs
weight: 9680
url: /de/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

Ein[`ImageAttributes`](../imageattributes) -Objekt enthält Informationen darüber, wie Bitmap- und Metadateifarben während des Renderns manipuliert werden. Ein[`ImageAttributes`](../imageattributes)-Objekt verwaltet mehrere Farbanpassungseinstellungen, darunter Farbanpassungsmatrizen, Graustufenanpassungsmatrizen, Gammakorrekturwerte, Farbabbildungstabellen und Farbschwellenwerte. Während des Renderns können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie eine[`ImageAttributes`](../imageattributes) Objekt und passiere den Pfad davon[`ImageAttributes`](../imageattributes) Objekt (zusammen mit dem Pfad einer[`Image`](../image) ) an die DrawImage-Methode.

```csharp
public sealed class ImageAttributes
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Constructor |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Löscht die Pinselfarben-Neuzuordnungstabelle davon[`ImageAttributes`](../imageattributes) Objekt. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Löscht den Farbschlüssel (Transparenzbereich) für eine bestimmte Kategorie. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Löscht die Farbanpassungsmatrix für die Standardkategorie. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Löscht die Farbanpassungsmatrix für eine bestimmte Kategorie. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Deaktiviert die Gammakorrektur für die Standardkategorie. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Deaktiviert die Gammakorrektur für eine bestimmte Kategorie. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Löscht die NoOp-Einstellung für die Standardkategorie. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Löscht die NoOp-Einstellung für eine bestimmte Kategorie. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Löscht die CMYK-Ausgabekanaleinstellung (Cyan-Magenta-Gelb-Schwarz) für die Standardkategorie. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Löscht die Ausgabekanaleinstellung (Cyan-Magenta-Gelb-Schwarz) für eine bestimmte Kategorie. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Löscht die Farbprofileinstellung des Ausgangskanals für die Standardkategorie. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Löscht die Farbprofileinstellung des Ausgangskanals für eine bestimmte Kategorie. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Löscht die Farbzuordnungstabelle für die Standardkategorie. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Löscht die Farbzuordnungstabelle für eine bestimmte Kategorie. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Löscht den Schwellenwert für die Standardkategorie. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Löscht den Schwellenwert für eine bestimmte Kategorie. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Legt die Farbneuzuordnungstabelle für die Pinselkategorie fest. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Legt den Farbschlüssel für die Standardkategorie fest. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Legt den Farbschlüssel (Transparenzbereich) für eine bestimmte Kategorie fest. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Legt die Farbanpassungsmatrix und die Graustufenanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Legt die Farbanpassungsmatrix und die Graustufenanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Legt die Farbanpassungsmatrix und die Graustufenanpassungsmatrix für eine bestimmte Kategorie fest. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Legt die Farbanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Legt die Farbanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Legt die Farbanpassungsmatrix für eine bestimmte Kategorie fest. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Legt den Gammawert für die Standardkategorie fest. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Legt den Gammawert für eine bestimmte Kategorie fest. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Deaktiviert die Farbanpassung für die Standardkategorie. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Deaktiviert die Farbanpassung für eine bestimmte Kategorie. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Legt den CMYK-Ausgabekanal (Cyan-Magenta-Gelb-Schwarz) für die Standardkategorie fest. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Legt den CMYK-Ausgabekanal (Cyan-Magenta-Gelb-Schwarz) für eine bestimmte Kategorie fest. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Legt die Farbprofildatei des Ausgabekanals für eine bestimmte Kategorie fest. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Legt die Farbzuordnungstabelle für die Standardkategorie fest. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Legt die Farbumwandlungstabelle für eine bestimmte Kategorie fest. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Legt den Schwellenwert (Transparenzbereich) für eine bestimmte Kategorie fest. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Legt den Umbruchmodus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie ausfüllt. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Legt den Umbruchmodus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie ausfüllt. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Legt den Umbruchmodus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie ausfüllt. |

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

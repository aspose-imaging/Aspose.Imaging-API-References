---
title: ImageAttributes
second_title: Aspose.Imaging för .NET API-referens
description: AnImageAttributes./imageattributes objektet innehåller information om hur bitmapps- och metafilfärger manipuleras under rendering. EnImageAttributes./imageattributesobjektet har flera färgjusteringsinställningar inklusive färgjusteringsmatriser gråskalejusteringsmatriser gammakorrigeringsvärden färgkartatabeller och färgtröskelvärden. Under renderingen kan färger korrigeras mörkas ljusnas och tas bort. För att tillämpa sådana manipulationer initiera enImageAttributes./imageattributes objekt och passera vägen för detImageAttributes./imageattributes objekt tillsammans med sökvägen för enImage./image  till DrawImage-metoden.
type: docs
weight: 9680
url: /sv/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

An[`ImageAttributes`](../imageattributes) objektet innehåller information om hur bitmapps- och metafilfärger manipuleras under rendering. En[`ImageAttributes`](../imageattributes)objektet har flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalejusteringsmatriser, gammakorrigeringsvärden, färgkartatabeller och färgtröskelvärden. Under renderingen kan färger korrigeras, mörkas, ljusnas och tas bort. För att tillämpa sådana manipulationer, initiera en[`ImageAttributes`](../imageattributes) objekt och passera vägen för det[`ImageAttributes`](../imageattributes) objekt (tillsammans med sökvägen för en[`Image`](../image) ) till DrawImage-metoden.

```csharp
public sealed class ImageAttributes
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Constructor |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Rensar penselfärgombildningstabellen för detta[`ImageAttributes`](../imageattributes) objekt. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Rensar färgnyckeln (transparensintervall) för standardkategorin. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Rensar färgnyckeln (transparensintervall) för en angiven kategori. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Rensar färgjusteringsmatrisen för standardkategorin. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Rensar färgjusteringsmatrisen för en angiven kategori. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Inaktiverar gammakorrigering för standardkategorin. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Inaktiverar gammakorrigering för en angiven kategori. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Rensar NoOp-inställningen för standardkategorin. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Rensar NoOp-inställningen för en angiven kategori. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Rensar utgångskanalinställningen för CMYK (cyan-magenta-gul-svart) för standardkategorin. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Rensar utgångskanalinställningen (cyan-magenta-gul-svart) för en angiven kategori. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Rensar utgångskanalens färgprofilinställning för standardkategorin. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Rensar utgångskanalens färgprofilinställning för en angiven kategori. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Rensar färgombildningstabellen för standardkategorin. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Rensar färgombildningstabellen för en angiven kategori. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Tar bort tröskelvärdet för standardkategorin. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Tar bort tröskelvärdet för en angiven kategori. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Ställer in färgombildningstabellen för penselkategorin. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Ställer in färgnyckeln för standardkategorin. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Ställer in färgnyckeln (transparensintervall) för en angiven kategori. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för en angiven kategori. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen för en angiven kategori. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Anger gammavärdet för standardkategorin. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Anger gammavärdet för en angiven kategori. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Stänger av färgjustering för standardkategorin. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Stänger av färgjustering för en angiven kategori. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Ställer in CMYK-utgångskanalen (cyan-magenta-gul-svart) för standardkategorin. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Ställer in CMYK-utgångskanalen (cyan-magenta-gul-svart) för en angiven kategori. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Ställer in utgångskanalens färgprofilfil för standardkategorin. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Ställer in utgångskanalens färgprofilfil för en angiven kategori. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Ställer in färgombildningstabellen för standardkategorin. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Ställer in färgombildningstabellen för en angiven kategori. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Ställer in tröskeln (transparensintervall) för standardkategorin. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Ställer in tröskeln (transparensintervall) för en angiven kategori. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Ställer in lindningsläget som används för att bestämma hur en textur ska kaklas över en form eller vid formgränser. En textur är sida vid sida över en form för att fylla i den när strukturen är mindre än formen den fyller. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Ställer in lindningsläget och färgen som används för att bestämma hur en textur ska kaklas över en form eller vid formgränser. En textur är sida vid sida över en form för att fylla i den när strukturen är mindre än formen den fyller. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Ställer in lindningsläget och färgen som används för att bestämma hur en textur ska kaklas över en form eller vid formgränser. En textur är sida vid sida över en form för att fylla i den när strukturen är mindre än formen den fyller. |

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

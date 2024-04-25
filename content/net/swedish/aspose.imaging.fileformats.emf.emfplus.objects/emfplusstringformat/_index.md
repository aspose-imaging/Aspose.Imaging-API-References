---
title: EmfPlusStringFormat
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusStringFormat-objektet specificerar textlayout visningsmanipulationer och språkidentifiering
type: docs
weight: 5780
url: /sv/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

EmfPlusStringFormat-objektet specificerar textlayout, visningsmanipulationer och språkidentifiering

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Hämtar eller ställer in ett EmfPlusLanguageIdentifier-objekt som anger språket som ska användas för numeriska siffror i strängen. Till exempel, om den här strängen innehåller arabiska siffror, MÅSTE detta fält innehålla en språkidentifierare som_x0d _x00d_ Arabic language specific_x0d |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur man ersätter numeriska siffror i strängen enligt en lokal eller ett språk. Detta värde MÅSTE definieras i StringDigitSubstitution enumeration.1.000)._sektion. |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Hämtar eller ställer in ett 32-bitars flyttalsvärde som anger antalet mellanslag mellan början av en textrad och den första tabben stop |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger typen av bearbetning som utförs på en sträng när ett keyboard genvägsprefix (det vill säga ett et-tecken) påträffas. I grund och botten anger det här fältet huruvida det ska visas prefix_x000 tangentbord. relate to text. Värdet MÅSTE definieras i HotkeyPrefix uppräkningen (avsnitt 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | Hämtar eller ställer in ett EmfPlusLanguageIdentifier-objekt (avsnitt 2.2.2.23) som anger språket som ska användas för string |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Hämtar eller ställer in ett 32-bitars flyttalsvärde som anger längden för utrymmet som ska läggas till startpositionen för en sträng. Standard är 1/6 tum; för typografiska teckensnitt är standardvärdet 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur strängen justeras vertikalt i layoutrektangeln. Detta värde MÅSTE definieras i StringAlignment-uppräkningen. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger antalet EmfPlusCharacterRange -objekt (avsnitt 2.2.2.8) definierade i StringFormatData-fältet. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger hur strängen ska justeras horisontellt i layoutrektangeln. Detta värde MÅSTE definieras i StringAlignment uppräkningen (avsnitt 2.1.x0.00d_). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | Hämtar eller ställer in ett EmfPlusStringFormatData-objekt (avsnitt 2.2.2.44) som anger valfria textlayoutdata. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger textlayout alternativ för formatering, klippning och teckensnittshantering. Detta värde MÅSTE bestå av StringFormat flags (avsnitt 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger antalet tabbstopp definierat i StringFormatData-fältet. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Hämtar eller ställer in ett 32-bitars flyttalsvärde som specificerar ratio för det horisontella utrymmet som tilldelats varje tecken i en specificerad sträng till den teckensnittsdefinierade bredden av tecknet . Stora värden för den här egenskapen anger ample utrymme mellan tecken; värden mindre än 1 kan producera tecken överlappar varandra. Standard är 1.03; för typographic -teckensnitt är standardvärdet 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Hämtar eller ställer in ett 32-bitars flyttalsvärde som anger längden av utrymmet som ska lämnas efter en sträng. Standard är 1/6 tum; för typografiska teckensnitt är standardvärdet 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Gets eller sets anger hur tecken ska trimmas från en sträng som är för stor för att passa in i en layoutrektangel. Detta värde MÅSTE definieras i StringTrimming-uppräkningen (avsnitt 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Hämtar eller ställer in versionen. |

### Se även

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

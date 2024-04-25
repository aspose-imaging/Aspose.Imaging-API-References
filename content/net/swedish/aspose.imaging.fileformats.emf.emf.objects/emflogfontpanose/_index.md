---
title: EmfLogFontPanose
second_title: Aspose.Imaging för .NET API-referens
description: LogFontPanose-objektet anger PANOSE-egenskaperna för ett logiskt teckensnitt.
type: docs
weight: 3060
url: /sv/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
## EmfLogFontPanose class

LogFontPanose-objektet anger PANOSE-egenskaperna för ett logiskt teckensnitt.

```csharp
public sealed class EmfLogFontPanose : EmfLogFont
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfLogFontPanose](emflogfontpanose)(EmfLogFont) | Initierar en ny instans av[`EmfLogFontPanose`](../emflogfontpanose) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger uppsättningen teckenglyfer. Det MÅSTE vara ett värde i WMF CharacterSet-uppräkningen ([MS-WMF] avsnitt 2.1.1.5). Om teckenuppsättningen är okänd, SKA metafilbehandling INTE försöka översätta eller tolka -strängar som renderas med det teckensnittet. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger klippningsprecisionen. klippprecisionen definierar hur tecken som delvis är utanför klippområdet ska klippas. Det kan vara en eller flera av WMF ClipPrecision Flags |
| [Culture](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/culture) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE sättas till noll och MÅSTE ignoreras. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger vinkeln, i tiondelar av grader, mellan escapement-vektorn och enhetens x-axel. Escapement-vektorn är parallell med baslinjen för en textrad. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Hämtar eller ställer in ett ansiktsnamn (64 byte): En sträng på högst 32 Unicode-tecken som anger typsnittets typsnittsnamn. Om längden på denna sträng är mindre än 32 tecken, MÅSTE en avslutande NULL finnas, varefter resten av detta fält MÅSTE ignoreras. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/fullname) { get; set; } | Hämtar eller ställer in en sträng med 64 Unicode-tecken som definierar teckensnittets fullständiga namn. Om längden på denna sträng är mindre än 64 tecken, MÅSTE en avslutande NULL finnas, efter som resten av detta fält MÅSTE ignoreras. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger höjden, i logiska enheter, på teckensnittets teckencell eller tecken. Teckenhöjdsvärdet, även känt som em-storleken, är värdet för teckencellens höjd minus det interna inledande värdet. Teckensnittsmapparen SKA tolka värdet som anges i fältet Height på följande sätt. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger ett kursivt teckensnitt om satt till 0x01; annars MÅSTE den vara inställd på 0x00. |
| [Match](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/match) { get; set; } | Gets eller sets Det här fältet MÅSTE ignoreras. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger vinkeln, i tiondelar av grader, mellan varje teckens baslinje och enhetens x-axel. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Hämtar eller ställer in ett 8-bitars heltal utan tecken som anger utdataprecisionen. Utdataprecisionen definierar hur nära teckensnittet krävs för att matcha den begärda höjden, bredden, teckenorienteringen, escapement, tonhöjd och teckensnittstyp. Det MÅSTE vara ett värde från WMF OutPrecision enumeration |
| [Padding](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/padding) { get; set; } | Hämtar eller ställer in ett fält som endast existerar för att säkerställa 32-bitars justering av denna struktur. Det MÅSTE ignoreras |
| [Panose](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/panose) { get; set; } | Hämtar eller ställer in ett Panose-objekt (avsnitt 2.2.21) som specificerar PANOSE-egenskaperna för det logiska teckensnittet. Om alla fält i detta objekt är noll, MÅSTE det ignoreras. |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | Hämtar eller ställer in ett WMF PitchAndFamily-objekt ([MS-WMF] avsnitt 2.2.2.14) som anger teckensnittets tonhöjd och familj. Teckensnittsfamiljer beskriver utseendet på ett teckensnitt på ett allmänt sätt. De är avsedda för att ange ett teckensnitt när det angivna typsnittet inte är tillgängligt. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger utdatakvaliteten. Utdatakvaliteten definierar hur nära man försöker matcha attributen för logiskt teckensnitt med de för ett faktiskt fysiskt teckensnitt. Det MÅSTE vara ett av värdena i WMF FontQuality-uppräkningen ([MS-WMF] avsnitt 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger ett överstruket teckensnitt om det är satt till 0x01; annars MÅSTE den vara inställd på 0x00. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/style) { get; set; } | Hämtar eller ställer in en sträng med 32 Unicode-tecken som definierar typsnittets stil. Om längden på denna sträng är mindre än 32 tecken, MÅSTE en avslutande NULL finnas, varefter resten av detta fält MÅSTE ignoreras. |
| [StyleSize](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/stylesize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger punktstorleken vid vilken teckensnitt antydning utförs. Om inställt på noll utförs teckensnittstips vid punktstorleken som motsvarar fältet Height i LogFont-objektet i LogFont-fältet |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger ett understruket teckensnitt om satt till 0x01; annars MÅSTE den vara inställd på 0x00. |
| [VendorId](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/vendorid) { get; set; } | Gets eller sets Det här fältet MÅSTE ignoreras. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/version) { get; set; } | Gets eller sets Detta fält MÅSTE ignoreras. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger vikten på teckensnittet i intervallet noll till 1000. Till exempel är 400 normalt och 700 är fetstil. Om detta värde är noll kan en standardvikt användas. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger medelbredden, i logiska enheter, på tecken i teckensnittet. Om fältvärdet Width är noll, SKA ett lämpligt värde beräknas från andra LogFont-värden för att hitta ett teckensnitt som har typografens avsedda bildförhållande |

### Se även

* class [EmfLogFont](../emflogfont)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

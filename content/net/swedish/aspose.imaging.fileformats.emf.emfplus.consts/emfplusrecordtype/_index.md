---
title: EmfPlusRecordType
second_title: Aspose.Imaging för .NET API-referens
description: RecordType-uppräkningen definierar posttyper som används i EMF metafiler.
type: docs
weight: 5030
url: /sv/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

RecordType-uppräkningen definierar posttyper som används i EMF+ metafiler.

```csharp
public enum EmfPlusRecordType : short
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| EmfPlusHeader | `16385` | Den här posten anger början av EMF+-data i metafilen. Den MÅSTE vara inbäddad i den första EMF-posten efter[`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) post ([MS-EMF] avsnitt 2.3.4.2 post). |
| EmfPlusEndOfFile | `16386` | Den här posten anger slutet av EMF+-data i metafilen. |
| EmfPlusComment | `16387` | Denna post specificerar godtyckliga privata data. |
| EmfPlusGetDC | `16388` | Denna post anger att efterföljande EMF-poster som påträffas i metafilen SKA bearbetas. EMF-poster slutar bearbetas när nästa EMF+-post påträffas. |
| EmfPlusMultiFormatStart | `16389` | Denna post är reserverad och FÅR INTE användas. |
| EmfPlusMultiFormatSection | `16390` | Denna post är reserverad och FÅR INTE användas. |
| EmfPlusMultiFormatEnd | `16391` | Denna post är reserverad och FÅR INTE användas. |
| EmfPlusObject | `16392` | Denna post anger ett objekt för användning i grafikoperationer. |
| EmfPlusClear | `16393` | Denna post rensar utdata`koordinera utrymme` och initierar den med en specificerad bakgrundsfärg och transparens. |
| EmfPlusFillRects | `16394` | Den här posten definierar hur man fyller det inre av en serie rektanglar med en specificerad borste. |
| EmfPlusDrawRects | `16395` | Den här posten definierar penndragen för att rita en serie rektanglar. |
| EmfPlusFillPolygon | `16396` | Denna post definierar data för att fylla det inre av en polygon, med hjälp av en specificerad pensel. |
| EmfPlusDrawLines | `16397` | Den här posten definierar penndragen för att rita en serie sammankopplade linjer. |
| EmfPlusFillEllipse | `16398` | Den här posten definierar hur man fyller det inre av en ellips med en specificerad borste. |
| EmfPlusDrawEllipse | `16399` | Denna post definierar penndragen för att rita en ellips. |
| EmfPlusFillPie | `16400` | Den här posten definierar hur man fyller en del av en inre del av en ellips med hjälp av en specificerad borste. |
| EmfPlusDrawPie | `16401` | Den här posten definierar penndrag för att rita en sektion av en ellips. |
| EmfPlusDrawArc | `16402` | Posten definierar penndrag för att rita en båge av en ellips. |
| EmfPlusFillRegion | `16403` | Den här posten definierar hur man fyller det inre av en region med en specificerad pensel. |
| EmfPlusFillPath | `16404` | Posten definierar hur man fyller det inre av figurerna definierade i en grafisk bana med en specificerad pensel. En bana är ett objekt som definierar en godtycklig sekvens av linjer, kurvor och former. |
| EmfPlusDrawPath | `16405` | Posten definierar penndragen för att rita figurerna i en grafisk bana. En bana är ett objekt som definierar en godtycklig sekvens av linjer, kurvor och former. |
| EmfPlusFillClosedCurve | `16406` | Denna post definierar hur man fyller det inre av en sluten kardinalspline med en specificerad borste. |
| EmfPlusDrawClosedCurve | `16407` | Denna post definierar pennan och slagen för att rita en stängd kardinalspline. |
| EmfPlusDrawCurve | `16408` | Denna post definierar penndragen för att rita en kardinal spline. |
| EmfPlusDrawBeziers | `16409` | Denna post definierar penndragen för att rita en Bezier-spline. |
| EmfPlusDrawImage | `16410` | Denna post definierar en skalad[`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)objekt (avsnitt 2.2.1.4). En bild kan bestå av antingen bitmapps- eller metafildata. |
| EmfPlusDrawImagePoints | `16411` | Denna post definierar ett skalat EmfPlusImage-objekt inuti ett parallellogram. En bild kan bestå av antingen bitmapps- eller metafildata. |
| EmfPlusDrawString | `16412` | Den här posten definierar en textsträng baserat på ett teckensnitt, en layoutrektangel och ett format. |
| EmfPlusSetRenderingOrigin | `16413` | Denna post definierar ursprunget för återgivningen till de angivna horisontella och vertikala koordinaterna. Detta gäller för kläckningsborstar och 8 och 16 bitar per pixel vibrerande mönster. |
| EmfPlusSetAntiAliasMode | `16414` | Denna post definierar om textkantutjämning ska aktiveras eller inaktiveras. Textkantutjämning är en metod för att få linjer och kanter på teckenglyfer att se jämnare ut när de ritas på en utdatayta. |
| EmfPlusSetTextRenderingHint | `16415` | Denna post definierar processen som används för att rendera text. |
| EmfPlusSetTextContrast | `16416` | Denna post ställer in textkontrasten enligt det angivna textgammavärdet. |
| EmfPlusSetInterpolationMode | `16417` | Denna post definierar interpolationsläget för ett objekt enligt den specificerade typen av bildfiltrering. Interpolationsläget påverkar hur skalning (sträckning och krympning) utförs. |
| EmfPlusSetPixelOffsetMode | `16418` | Denna post definierar pixelförskjutningsläget enligt det angivna pixelcentreringsvärdet. |
| EmfPlusSetCompositingMode | `16419` | Den här posten definierar sammansättningsläget enligt tillståndet för alfablandning, vilket anger hur källfärger kombineras med bakgrundsfärger. |
| EmfPlusSetCompositingQuality | `16420` | Denna post definierar sammansättningskvaliteten, som beskriver den önskade kvalitetsnivån för att skapa sammansatta bilder från flera objekt. |
| EmfPlusSave | `16421` | Denna post sparar grafiktillståndet, identifierat av ett specificerat index, på en stapel med sparade grafiktillstånd. Varje stackindex är associerat med ett visst sparat tillstånd, och indexet används av en[`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) spela in (avsnitt 2.3.7.4) för att återställa tillståndet. |
| EmfPlusRestore | `16422` | Denna post återställer grafiktillståndet, identifierat av ett specificerat index, från en stapel med sparade grafiktillstånd. Varje stackindex är associerat med ett visst sparat tillstånd, och indexet definieras av en[`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave) spela in (avsnitt 2.3.7.5) för att spara tillståndet. |
| EmfPlusBeginContainer | `16423` | Denna post öppnar en ny grafiktillståndsbehållare och anger en transformation för den. Grafikbehållare används för att behålla delar av grafiktillståndet. |
| EmfPlusBeginContainerNoParams | `16424` | Denna post öppnar en ny behållare för grafiktillstånd. |
| EmfPlusEndContainer | `16425` | Denna post stänger en grafiktillståndsbehållare som tidigare öppnades av en start-containeroperation. |
| EmfPlusSetWorldTransform | `16426` | Denna post definierar den aktuella världsrymdtransformen i uppspelningsenhet_kontext, enligt en specificerad transformationsmatris. |
| EmfPlusResetWorldTransform | `16427` | Denna post återställer den aktuella världsrymdtransformen till identifieringsmatrisen. |
| EmfPlusMultiplyWorldTransform | `16428` | Denna post multiplicerar det aktuella världsutrymmet med en specificerad transformationsmatris. |
| EmfPlusTranslateWorldTransform | `16429` | Denna post tillämpar en översättningsomvandling till det aktuella världsrummet med angivna horisontella och vertikala avstånd. |
| EmfPlusScaleWorldTransform | `16430` | Denna post tillämpar en skalomvandling på det aktuella världsutrymmet med angivna horisontella och vertikala skalfaktorer. |
| EmfPlusRotateWorldTransform | `16431` | Denna post roterar det aktuella världsutrymmet med en specificerad vinkel. |
| EmfPlusSetPageTransform | `16432` | Denna post specificerar extra skalningsfaktorer för den aktuella världsrymdtransformen. |
| EmfPlusResetClip | `16433` | Denna post återställer den aktuella klippningsregionen för världsrymden till oändlighet. |
| EmfPlusSetClipRect | `16434` | Denna post kombinerar det aktuella klippområdet med en rektangel. |
| EmfPlusSetClipPath | `16435` | Denna post kombinerar det aktuella klippområdet med en grafisk sökväg. |
| EmfPlusSetClipRegion | `16436` | Denna post kombinerar det aktuella klippområdet med ett annat grafikområde. |
| EmfPlusOffsetClip | `16437` | Denna post tillämpar en översättningsomvandling på den aktuella urklippsregionen i världsrymden. |
| EmfPlusDrawDriverString | `16438` | Denna post specificerar textutmatning med teckenpositioner. |
| EmfPlusStrokeFillPath | `16439` | Den här posten stänger alla öppna figurer i en bana, strök konturerna av banan med hjälp av den aktuella pennan och fyller dess inre med hjälp av den aktuella penseln. |
| EmfPlusSerializableObject | `16440` | Denna post definierar ett parameterblock för bildeffekter som har serialiserats till en databuffert. |
| EmfPlusSetTSGraphics | `16441` | Den här posten anger tillståndet för en grafikenhetskontext för en terminalserver. |
| EmfPlusSetTSClip | `16442` | Den här posten anger klippområden i grafikenhetskontexten för en terminalserver. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

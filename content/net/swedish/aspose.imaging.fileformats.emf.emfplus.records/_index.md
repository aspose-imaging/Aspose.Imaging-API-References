---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging för .NET API-referens
description: Namnutrymmet innehåller typer MS-EMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF Records
type: docs
weight: 390
url: /sv/aspose.imaging.fileformats.emf.emfplus.records/
---
Namnutrymmet innehåller typer [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | EmfPlusBeginContainer-posten öppnar en ny grafiktillståndsbehållare och anger en transformation för den. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | EmfPlusBeginContainerNoParams-posten öppnar en ny grafiktillståndsbehållare. |
| [EmfPlusClear](./emfplusclear) | EmfPlusClear-posten rensar utdatakoordinatutrymmet och initierar det med en bakgrundsfärg och transparency |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | Urklippsposttyperna anger klippområden och operationer. |
| [EmfPlusComment](./emfpluscomment) | EmfPlusComment-posten anger godtyckliga privata data. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | Kontrollposttyperna anger globala parametrar för EMF+ metafilbehandling. |
| [EmfPlusDrawArc](./emfplusdrawarc) | EmfPlusDrawArc-posten specificerar att rita bågen av en ellips. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | EmfPlusDrawBeziers-posten specificerar att rita en sekvens av anslutna Bezier-kurvor. Ordningen för Bezier-datapunkter är startpunkten, kontrollpunkt 1, kontrollpunkt 2 och slutpunkt. För mer information se [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | EmfPlusDrawClosedCurve-posten anger att rita en stängd kardinalspline |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | EmfPlusDrawCurve-posten specificerar att rita en kardinal spline OBS: ObjectID (1 byte): Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+-objekttabellen för att rita kurvan. Värdet MÅSTE vara noll till 63, inklusive. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | EmfPlusDrawDriverString-posten anger textutmatning med teckenpositioner. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | EmfPlusDrawEllipse-posten anger att rita en ellips. |
| [EmfPlusDrawImage](./emfplusdrawimage) | EmfPlusDrawImage-posten anger att man ritar en skalad bild. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | EmfPlusDrawImagePoints-posten anger att man ritar en skalad bild inuti ett parallellogram. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | Ritningsposttyperna anger grafikutdata. |
| [EmfPlusDrawLines](./emfplusdrawlines) | EmfPlusDrawlLines-posten anger ritning av en serie anslutna linjer |
| [EmfPlusDrawPath](./emfplusdrawpath) | EmfPlusDrawPath-posten anger att rita en grafisk sökväg. |
| [EmfPlusDrawPie](./emfplusdrawpie) | EmfPlusDrawPie-posten specificerar att rita en sektion av det inre av en ellips. |
| [EmfPlusDrawRects](./emfplusdrawrects) | EmfPlusDrawRects-posten anger att rita en serie rektanglar |
| [EmfPlusDrawString](./emfplusdrawstring) | EmfPlusDrawString-posten anger textutmatning med strängformatering |
| [EmfPlusEndContainer](./emfplusendcontainer) | EmfPlusEndContainer-posten stänger en grafiktillståndsbehållare som tidigare öppnades av en start-containeroperation. |
| [EmfPlusEndOfFile](./emfplusendoffile) | EmfPlusEndOfFile-posten anger slutet av EMF+-data i metafilen. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | EmfPlusFillClosedCurve-posten anger fyllning av det inre av en stängd kardinalspline |
| [EmfPlusFillEllipse](./emfplusfillellipse) | EmfPlusFillEllipse-posten anger fyllning av det inre av en ellips |
| [EmfPlusFillPath](./emfplusfillpath) | Fyll sökväg record FLAGS: 16-bitars osignerat heltal som ger information om hur operationen ska utföras, och om postens struktur. 0 1 2 3 4 5 6 7 0 8 4 9 1 2 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 bit): Denna bit indikerar typen av data i BrushId-fältet. Om det är inställt, anger BrushId en färg som ett EmfPlusARGB-objekt (avsnitt 2.2.2.1). Om den är ren, innehåller BrushId indexet för ett EmfPlusBrush-objekt (avsnitt 2.2.1.1) i EMF+-objekttabellen. X (1 bit): Reserverat och MÅSTE ignoreras. ObjectId (1 byte): Indexet för EmfPlusPath-objektet ( avsnitt 2.2.1.6) för att fylla i EMF+-objekttabellen. Värdet MÅSTE vara noll till 63, inklusive. |
| [EmfPlusFillPie](./emfplusfillpie) | EmfPlusFillPie-posten anger att fylla en del av det inre av en ellips |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | EmfPlusFillPolygon-posten anger fyllning av det inre av en polygon. |
| [EmfPlusFillRects](./emfplusfillrects) | EmfPlusFillRects-posten anger fyllning av insidan av en serie rektanglar |
| [EmfPlusFillRegion](./emfplusfillregion) | EmfPlusFillRegion-posten anger fyllning av det inre av en grafikregion |
| [EmfPlusGetDc](./emfplusgetdc) | EmfPlusGetDC-posten anger att efterföljande EMF-poster som påträffas i metafilen SKA bearbetas. |
| [EmfPlusHeader](./emfplusheader) | EmfPlusHeader-posten anger starten av EMF+-data i metafilen. EmfPlusHeader-posten MÅSTE vara inbäddad i en EMF EMR_COMMENT_EMFPLUS-post, som MÅSTE vara posten omedelbart efter EMF-huvudet i metafilen. EMR_COMMENT_EMFPLUS-posten specificeras i [MS-EMF] avsnitt 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | EmfPlusMultiplyWorldTransform-posten multiplicerar den aktuella världsrymdtransformen med en specificerad transformationsmatris. |
| [EmfPlusObject](./emfplusobject) | EmfPlusObject-posten anger ett objekt för användning i grafikoperationer. Objektdefinitionen kan sträcka sig över flera poster, vilket indikeras av värdet i fältet Flaggor. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | Objektposttyperna definierar återanvändbara grafikobjekt. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | EmfPlusOffsetClip-posten tillämpar en översättningsomvandling på den aktuella klippningsregionen för världsrymden. Den nya aktuella klippningsregionen ställs in på resultatet av översättningstransformeringen. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | Egenskapsposttyperna anger egenskaper för uppspelningsenhetskontexten. |
| [EmfPlusRecord](./emfplusrecord) | Basposttypen Emf+. |
| [EmfPlusResetClip](./emfplusresetclip) | EmfPlusResetClip-posten återställer den aktuella klippningsregionen för världsrymden till oändlighet. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | EmfPlusResetWorldTransform-posten återställer den aktuella världsrymdtransformen till identifieringsmatrisen. |
| [EmfPlusRestore](./emfplusrestore) | EmfPlusRestore-posten återställer grafiktillståndet, identifierat av ett specificerat index, från en stapel med sparade grafiktillstånd. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | EmfPlusRotateWorldTransform-posten utför en rotation på den aktuella världsrymdtransformen. |
| [EmfPlusSave](./emfplussave) | EmfPlusSave-posten sparar grafiktillståndet, identifierat av ett specificerat index, på en stapel med sparade grafiktillstånd. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | EmfPlusScaleWorldTransform-posten utför en skalning på den aktuella världsrymdtransformen. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | EmfPlusSerializableObject-posten definierar ett parameterblock för bildeffekter som har serialiserats till en databuffert. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | EmfPlusSetAntiAliasMode-posten anger kantutjämningsläget för textutmatning. |
| [EmfPlusSetClipPath](./emfplussetclippath) | EmfPlusSetClipPath-posten kombinerar den aktuella klippningsregionen med en grafisk sökväg. Den nya aktuella klippningsregionen ställs in på resultatet av CombineMode-operationen. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | EmfPlusSetClipRect-posten kombinerar det aktuella klippområdet med en rektangel. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | EmfPlusSetClipRegion-posten kombinerar den aktuella klippningsregionen med en annan grafikregion. Den nya aktuella klippningsregionen ställs in på resultatet av att utföra CombineMode-operationen on den tidigare aktuella urklippsregionen och det angivna EmfPlusRegion-objektet._x000 |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | EmfPlusSetCompositingMode-posten anger hur källfärger kombineras med bakgrundsfärger. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | EmfPlusSetCompositingQuality-posten anger önskad kvalitetsnivå för att skapa sammansatta bilder från flera objekt. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | EmfPlusSetInterpolationMode-posten anger hur bildskalning, inklusive sträckning och krympning, utförs. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | EmfPlusSetPageTransform-posten anger skalningsfaktorer och enheter för att konvertera sidutrymme -koordinater till enhetsutrymmeskoordinater. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | EmfPlusSetPixelOffsetMode-posten anger hur pixlar centreras med avseende på -koordinaterna för ritytan. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | EmfPlusSetRenderingOrigin-posten anger renderingsursprunget för grafikutdata. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | EmfPlusSetTextContrast-posten anger textkontrast enligt gammakorrigeringsvärdet. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | EmfPlusSetTextRenderingHint-posten anger kvaliteten på textåtergivningen, inklusive typen av kantutjämning. |
| [EmfPlusSetTsClip](./emfplussettsclip) | EmfPlusSetTSClip-posten specificerar klippområden i grafikenhetskontexten för en terminalserver. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | EmfPlusSetTSGraphics-posten anger tillståndet för en grafikenhetskontext för en terminalserver. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | EmfPlusSetWorldTransform-posten ställer in världsomvandlingen enligt värdena i en specificerad transformationsmatris. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | State Record Types specificerar operationer på tillståndet för uppspelningsenhetskontexten. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | Terminal Server Record Types specificerar grafikbearbetning på en terminalserver. Följande är EMF+ terminalserverposttyper. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | Transformposttyperna anger egenskaper och transformeringar på koordinatutrymmen. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | EmfPlusTranslateWorldTransform-posten utför en översättning av den aktuella världsrymdtransformen. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

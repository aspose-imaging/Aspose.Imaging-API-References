---
title: "EmfPlusRecordType"
second_title: "Aspose.Imaging för Java API-referens"
description: "RecordType‑uppräkningen definierar posttyper som används i EMF‑metafiler."
type: docs
weight: 45
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

RecordType‑enumerationen definierar rekordtyper som används i EMF+-metafiler.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Denna post specificerar början av EMF+‑data i metafilen. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Denna post specificerar slutet på EMF+‑data i metafilen. |
| [EmfPlusComment](#EmfPlusComment) | Denna post specificerar godtyckliga privata data. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Denna post specificerar att efterföljande EMF‑poster som påträffas i metafilen SKA bearbetas. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Denna post är reserverad och FÅR INTE användas. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Denna post är reserverad och FÅR INTE användas. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Denna post är reserverad och FÅR INTE användas. |
| [EmfPlusObject](#EmfPlusObject) | Denna post specificerar ett objekt för användning i grafikoperationer. |
| [EmfPlusClear](#EmfPlusClear) | Denna post rensar utdata `coordinate space` och initierar den med en specificerad bakgrundsfärg och transparens. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Denna post definierar hur man fyller insidan av en serie rektanglar med en specificerad pensel. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Denna post definierar pennstrecken för att rita en serie rektanglar. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Denna post definierar data för att fylla insidan av en polygon med en specificerad pensel. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Denna post definierar pennstrecken för att rita en serie sammankopplade linjer. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Denna post definierar hur man fyller insidan av en ellips med en specificerad pensel. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Denna post definierar pennstrecken för att rita en ellips. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Denna post definierar hur man fyller ett avsnitt av en inre sektion av en ellips med en specificerad pensel. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Denna post definierar pennstreck för att rita ett avsnitt av en ellips. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | Posten definierar pennstreck för att rita en båge av en ellips. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Denna post definierar hur man fyller regionens inre med en specificerad pensel. |
| [EmfPlusFillPath](#EmfPlusFillPath) | Posten definierar hur man fyller figurers inre som definierats i en grafikväg med en specificerad pensel. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | Posten definierar pennstrecken för att rita figurerna i en grafikväg. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Denna post definierar hur man fyller inre av en sluten kardinal spline med en specificerad pensel. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Denna post definierar pennan och strecken för att rita en sluten kardinal spline. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Denna post definierar pennstrecken för att rita en kardinal spline. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Denna post definierar pennstrecken för att rita en Bezier-spline. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Denna post definierar ett skalat [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) objekt (avsnitt 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Denna post definierar ett skalat EmfPlusImage-objekt inuti ett parallellogram. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Denna post definierar en textsträng baserad på ett teckensnitt, en layoutrektangel och ett format. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Denna post definierar renderingsursprunget till de specificerade horisontella och vertikala koordinaterna. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Denna post definierar om textantialiasing ska aktiveras eller inaktiveras. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Denna post definierar processen som används för att rendera text. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Denna post ställer in textkontrast enligt det specificerade textgammavärdet. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Denna post definierar interpolationsläget för ett objekt enligt den specificerade typen av bildfiltrering. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Denna post definierar pixeloffsetläget enligt det specificerade pixelcentreringsvärdet. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Denna post definierar kompositionsläget enligt tillståndet för alfa‑blandning, vilket specificerar hur källfärger kombineras med bakgrundsfärger. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Denna post definierar kompositionskvaliteten, som beskriver önskad kvalitetsnivå för att skapa sammansatta bilder från flera objekt. |
| [EmfPlusSave](#EmfPlusSave) | Denna post sparar grafikstatusen, identifierad av ett specificerat index, på en stack av sparade grafikstatusar. |
| [EmfPlusRestore](#EmfPlusRestore) | Denna post återställer grafikstatusen, identifierad av ett specificerat index, från en stack av sparade grafikstatusar. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Denna post öppnar en ny grafikstatusbehållare och specificerar en transform för den. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Denna post öppnar en ny grafikstatusbehållare. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Denna post stänger en grafikstatusbehållare som tidigare öppnades av en startbehållaroperation. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Denna post definierar den aktuella världsrumstransformen i uppspelningsenhet\_context enligt en specificerad transformmatris. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Denna post återställer den aktuella världsrumstransformen till identitetsmatrisen. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Denna post multiplicerar det aktuella världsrummet med en specificerad transformmatris. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Denna post tillämpar en translationstransform på det aktuella världsrummet med specificerade horisontella och vertikala avstånd. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Denna post tillämpar en skalningstransform på det aktuella världsrummet med specificerade horisontella och vertikala skalningsfaktorer. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Denna post roterar det aktuella världsrummet med en specificerad vinkel. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Denna post specificerar extra skalningsfaktorer för den aktuella världsrumstransformen. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Denna post återställer den aktuella beskärningsregionen för världsrummet till oändlighet. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Denna post kombinerar den aktuella beskärningsregionen med en rektangel. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Denna post kombinerar den aktuella beskärningsregionen med en grafikbana. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Denna post kombinerar den aktuella beskärningsregionen med en annan grafikregion. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Denna post tillämpar en translationstransform på den aktuella beskärningsregionen för världsrummet. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Denna post specificerar textutmatning med teckenpositioner. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Denna post stänger eventuella öppna figurer i en sökväg, ritar konturen av sökvägen med den aktuella pennan och fyller dess inre med den aktuella penseln. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Denna post definierar ett bildeffektparameterblock som har serialiserats till en databuffert. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Denna post specificerar tillståndet för en grafikenhetssammanhang för en terminalserver. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Denna post specificerar beskärningsområden i grafikenhetssammanhanget för en terminalserver. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Denna post specificerar starten av EMF+‑data i metafilen. Den MÅSTE vara inbäddad i den första EMF‑posten efter [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)‑posten ([MS-EMF] avsnitt 2.3.4.2‑post).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Denna post specificerar slutet på EMF+‑data i metafilen.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Denna post specificerar godtyckliga privata data.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Denna post specificerar att efterföljande EMF‑poster som påträffas i metafilen SKA bearbetas. EMF‑poster upphör att bearbetas när nästa EMF+‑post påträffas.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Denna post är reserverad och FÅR INTE användas.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Denna post är reserverad och FÅR INTE användas.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Denna post är reserverad och FÅR INTE användas.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Denna post specificerar ett objekt för användning i grafikoperationer.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Denna post rensar utdata `coordinate space` och initierar den med en specificerad bakgrundsfärg och transparens.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Denna post definierar hur man fyller insidan av en serie rektanglar med en specificerad pensel.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Denna post definierar pennstrecken för att rita en serie rektanglar.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Denna post definierar data för att fylla insidan av en polygon med en specificerad pensel.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Denna post definierar pennstrecken för att rita en serie sammankopplade linjer.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Denna post definierar hur man fyller insidan av en ellips med en specificerad pensel.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Denna post definierar pennstrecken för att rita en ellips.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Denna post definierar hur man fyller ett avsnitt av en inre sektion av en ellips med en specificerad pensel.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Denna post definierar pennstreck för att rita ett avsnitt av en ellips.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


Posten definierar pennstreck för att rita en båge av en ellips.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Denna post definierar hur man fyller regionens inre med en specificerad pensel.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


Posten definierar hur man fyller innanmålen av figurerna som definieras i en grafikbana med en specificerad pensel. En bana är ett objekt som definierar en godtycklig sekvens av linjer, kurvor och former.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


Posten definierar penndragningarna för att rita figurerna i en grafikbana. En bana är ett objekt som definierar en godtycklig sekvens av linjer, kurvor och former.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Denna post definierar hur man fyller inre av en sluten kardinal spline med en specificerad pensel.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Denna post definierar pennan och strecken för att rita en sluten kardinal spline.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Denna post definierar pennstrecken för att rita en kardinal spline.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Denna post definierar pennstrecken för att rita en Bezier-spline.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Denna post definierar ett skalat [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)-objekt (avsnitt 2.2.1.4). En bild kan bestå av antingen bitmap‑ eller metafildata.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Denna post definierar ett skalat EmfPlusImage‑objekt inuti ett parallellogram. En bild kan bestå av antingen bitmap‑ eller metafildata.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Denna post definierar en textsträng baserad på ett teckensnitt, en layoutrektangel och ett format.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Denna post definierar renderingsursprunget till de specificerade horisontella och vertikala koordinaterna. Detta gäller för skraffermönster och för 8‑ och 16‑bits‑per‑pixel‑dithermönster.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Denna post definierar om textantialiasing ska aktiveras eller inaktiveras. Textantialiasing är en metod för att få linjer och kanter på teckenglyfer att framstå mjukare när de ritas på en utskriftsyta.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Denna post definierar processen som används för att rendera text.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Denna post ställer in textkontrast enligt det specificerade textgammavärdet.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Denna post definierar interpolationsläget för ett objekt enligt den angivna typen av bildfiltrering. Interpolationsläget påverkar hur skalning (utsträckning och krympning) utförs.

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Denna post definierar pixeloffsetläget enligt det specificerade pixelcentreringsvärdet.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Denna post definierar kompositionsläget enligt tillståndet för alfa‑blandning, vilket specificerar hur källfärger kombineras med bakgrundsfärger.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Denna post definierar kompositionskvaliteten, som beskriver önskad kvalitetsnivå för att skapa sammansatta bilder från flera objekt.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Denna post sparar grafikläget, identifierat av ett angivet index, på en stack av sparade grafiklägen. Varje stackindex är associerat med ett specifikt sparat läge, och indexet används av en [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) post (avsnitt 2.3.7.4) för att återställa läget.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Denna post återställer grafikläget, identifierat av ett angivet index, från en stack av sparade grafiklägen. Varje stackindex är associerat med ett specifikt sparat läge, och indexet definieras av en [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) post (avsnitt 2.3.7.5) för att spara läget.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Denna post öppnar en ny grafikstatusbehållare och specificerar en transformation för den. Grafikbehållare används för att behålla element av grafikläget.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Denna post öppnar en ny grafikstatusbehållare.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Denna post stänger en grafikstatusbehållare som tidigare öppnades av en startbehållaroperation.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Denna post definierar den aktuella världsrumstransformen i uppspelningsenhet\_context enligt en specificerad transformmatris.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Denna post återställer den aktuella världsrumstransformen till identitetsmatrisen.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Denna post multiplicerar det aktuella världsrummet med en specificerad transformmatris.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Denna post tillämpar en translationstransform på det aktuella världsrummet med specificerade horisontella och vertikala avstånd.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Denna post tillämpar en skalningstransform på det aktuella världsrummet med specificerade horisontella och vertikala skalningsfaktorer.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Denna post roterar det aktuella världsrummet med en specificerad vinkel.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Denna post specificerar extra skalningsfaktorer för den aktuella världsrumstransformen.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Denna post återställer den aktuella beskärningsregionen för världsrummet till oändlighet.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Denna post kombinerar den aktuella beskärningsregionen med en rektangel.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Denna post kombinerar den aktuella beskärningsregionen med en grafikbana.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Denna post kombinerar den aktuella beskärningsregionen med en annan grafikregion.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Denna post tillämpar en translationstransform på den aktuella beskärningsregionen för världsrummet.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Denna post specificerar textutmatning med teckenpositioner.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Denna post stänger eventuella öppna figurer i en sökväg, ritar konturen av sökvägen med den aktuella pennan och fyller dess inre med den aktuella penseln.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Denna post definierar ett bildeffektparameterblock som har serialiserats till en databuffert.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Denna post specificerar tillståndet för en grafikenhetssammanhang för en terminalserver.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Denna post specificerar beskärningsområden i grafikenhetssammanhanget för en terminalserver.


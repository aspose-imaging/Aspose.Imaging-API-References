---
title: "EmfPlusRecordType uppräkning"
type: docs
weight: 360
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

RecordType‑uppräkningen definierar rekordtyper som används i EMF+-metafiler.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | Denna post öppnar en ny grafikstatusbehållare och specificerar en transform för den. Grafikbehållare används för att behålla element av grafikstatusen. |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | Denna post öppnar en ny grafikstatusbehållare. |
| EMF_PLUS_CLEAR | Denna post rensar utdata <c>coordinate space</c> och initierar den med en angiven bakgrundsfärg och transparens. |
| EMF_PLUS_COMMENT | Denna post specificerar godtycklig privat data. |
| EMF_PLUS_DRAW_ARC | Posten definierar pennstreck för att rita en båge av en ellips. |
| EMF_PLUS_DRAW_BEZIERS | Denna post definierar pennstrecken för att rita en Bézier-spline. |
| EMF_PLUS_DRAW_CLOSED_CURVE | Denna post definierar pennan och strecken för att rita en sluten kardinalspline. |
| EMF_PLUS_DRAW_CURVE | Denna post definierar pennstrecken för att rita en kardinalspline. |
| EMF_PLUS_DRAW_DRIVER_STRING | Denna post specificerar textutmatning med teckenpositioner. |
| EMF_PLUS_DRAW_ELLIPSE | Denna post definierar pennstrecken för att rita en ellips. |
| EMF_PLUS_DRAW_IMAGE | Denna post definierar ett skalat [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) objekt (avsnitt 2.2.1.4). En bild kan bestå av antingen bitmap- eller metafildata. |
| EMF_PLUS_DRAW_IMAGE_POINTS | Denna post definierar ett skalat EmfPlusImage-objekt inuti ett parallellogram. En bild kan bestå av antingen bitmap- eller metafildata. |
| EMF_PLUS_DRAW_LINES | Denna post definierar pennstrecken för att rita en serie av sammanhängande linjer. |
| EMF_PLUS_DRAW_PATH | Posten definierar penndragningarna för att rita figurerna i en grafikbana. En bana är ett objekt som definierar en godtycklig sekvens av linjer, kurvor och former. |
| EMF_PLUS_DRAW_PIE | Denna post definierar penndragningarna för att rita en del av en ellips. |
| EMF_PLUS_DRAW_RECTS | Denna post definierar penndragningarna för att rita en serie rektanglar. |
| EMF_PLUS_DRAW_STRING | Denna post definierar en textsträng baserad på ett typsnitt, en layoutrektangel och ett format. |
| EMF_PLUS_END_CONTAINER | Denna post stänger en grafikstatusbehållare som tidigare öppnades av en startbehållaroperation. |
| EMF_PLUS_END_OF_FILE | Denna post specificerar slutet på EMF+-data i metafilen. |
| EMF_PLUS_FILL_CLOSED_CURVE | Denna post definierar hur man fyller insidan av en sluten kardinal spline med en angiven pensel. |
| EMF_PLUS_FILL_ELLIPSE | Denna post definierar hur man fyller insidan av en ellips med en angiven pensel. |
| EMF_PLUS_FILL_PATH | Posten definierar hur man fyller insidan av figurerna som definieras i en grafikbana med en angiven pensel. En bana är ett objekt som definierar en godtycklig sekvens av linjer, kurvor och former. |
| EMF_PLUS_FILL_PIE | Denna post definierar hur man fyller en del av en inre sektion av en ellips med en angiven pensel. |
| EMF_PLUS_FILL_POLYGON | Denna post definierar data för att fylla insidan av en polygon med en angiven pensel. |
| EMF_PLUS_FILL_RECTS | Denna post definierar hur man fyller insidan av en serie rektanglar med en angiven pensel. |
| EMF_PLUS_FILL_REGION | Denna post definierar hur man fyller regionens interiör med en specificerad pensel. |
| EMF_PLUS_GET_DC | Denna post specificerar att efterföljande EMF-poster som påträffas i metafilen SKA bearbetas. EMF-poster slutar bearbetas när nästa EMF+-post påträffas. |
| EMF_PLUS_HEADER | Denna post specificerar början av EMF+-data i metafilen. Den MÅSTE vara inbäddad i den första EMF-posten efter [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) posten ([MS-EMF] avsnitt 2.3.4.2 post). |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | Denna post multiplicerar det aktuella världsrummet med en specificerad transformationsmatris. |
| EMF_PLUS_MULTI_FORMAT_END | Denna post är reserverad och FÅR INTE användas. |
| EMF_PLUS_MULTI_FORMAT_SECTION | Denna post är reserverad och FÅR INTE användas. |
| EMF_PLUS_MULTI_FORMAT_START | Denna post är reserverad och FÅR INTE användas. |
| EMF_PLUS_OBJECT | Denna post specificerar ett objekt för användning i grafikoperationer. |
| EMF_PLUS_OFFSET_CLIP | Denna post tillämpar en translatetransformation på det aktuella beskärningsområdet i världsrummet. |
| EMF_PLUS_RESET_CLIP | Denna post återställer det aktuella beskärningsområdet för världsrummet till oändlighet. |
| EMF_PLUS_RESET_WORLD_TRANSFORM | Denna post återställer den aktuella världsrumstransformen till identitetsmatrisen. |
| EMF_PLUS_RESTORE | Denna post återställer grafikstatusen, identifierad av ett specificerat index, från en stack av sparade grafikstatusar. Varje stackindex är associerat med ett särskilt sparat tillstånd, och indexet definieras av en [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) post (avsnitt 2.3.7.5) för att spara tillståndet. |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | Denna post roterar det aktuella världsrummet med en specificerad vinkel. |
| EMF_PLUS_SAVE | Denna post sparar grafikstatusen, identifierad av ett specificerat index, på en stack av sparade grafikstatusar. Varje stackindex är associerat med ett särskilt sparat tillstånd, och indexet används av en [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) post (avsnitt 2.3.7.4) för att återställa tillståndet. |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | Denna post tillämpar en skalningstransform på det aktuella världsrummet med specificerade horisontella och vertikala skalningsfaktorer. |
| EMF_PLUS_SERIALIZABLE_OBJECT | Denna post definierar ett bildeffektsparameterblock som har serialiserats till en databuffert. |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | Denna post definierar om textantialiasing ska aktiveras eller inaktiveras. Textantialiasing är en metod för att få linjer och kanter på teckenglyfer att framstå som mjukare när de ritas på en utskriftsyta. |
| EMF_PLUS_SET_CLIP_PATH | Denna post kombinerar den aktuella beskärningsregionen med en grafikbana. |
| EMF_PLUS_SET_CLIP_RECT | Denna post kombinerar den aktuella beskärningsregionen med en rektangel. |
| EMF_PLUS_SET_CLIP_REGION | Denna post kombinerar den aktuella beskärningsregionen med en annan grafikregion. |
| EMF_PLUS_SET_COMPOSITING_MODE | Denna post definierar sammansättningsläget enligt alfa‑blandningens tillstånd, vilket specificerar hur källfärger kombineras med bakgrundsfärger. |
| EMF_PLUS_SET_COMPOSITING_QUALITY | Denna post definierar sammansättningskvaliteten, som beskriver den önskade kvalitetsnivån för att skapa sammansatta bilder från flera objekt. |
| EMF_PLUS_SET_INTERPOLATION_MODE | Denna post definierar interpolationsläget för ett objekt enligt den angivna typen av bildfiltrering. Interpolationsläget påverkar hur skalning (utsträckning och förminskning) utförs. |
| EMF_PLUS_SET_PAGE_TRANSFORM | Denna post specificerar extra skalningsfaktorer för den aktuella världsrumstransformen. |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | Denna post definierar pixeloffsetläget enligt det angivna pixelcentreringsvärdet. |
| EMF_PLUS_SET_RENDERING_ORIGIN | Denna post definierar renderingsursprunget till de angivna horisontella och vertikala koordinaterna. Detta gäller för skraffermunstycken och för 8‑ och 16‑bits per pixel‑dithermönster. |
| EMF_PLUS_SET_TEXT_CONTRAST | Denna post ställer in textkontrast enligt det angivna textgammavärdet. |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | Denna post definierar processen som används för att rendera text. |
| EMF_PLUS_SET_TS_CLIP | Denna post specificerar klippningsområden i grafikens enhetskontext för en terminalserver. |
| EMF_PLUS_SET_TS_GRAPHICS | Denna post specificerar tillståndet för en grafikens enhetskontext för en terminalserver. |
| EMF_PLUS_SET_WORLD_TRANSFORM | Denna post definierar den aktuella världsrumstransformen i uppspelningsenhetskontexten, enligt en specificerad transformmatris. |
| EMF_PLUS_STROKE_FILL_PATH | Denna post stänger alla öppna figurer i en bana, ritar konturen av banan med den aktuella pennan och fyller dess inre med den aktuella penseln. |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | Denna post tillämpar en translatetransform på det aktuella världsrummet med angivna horisontella och vertikala avstånd. |

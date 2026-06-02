---
title: "CmxImageFill"
second_title: "Aspose.Imaging för Java API-referens"
description: "Information om bildfyllning"
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---
**Inheritance:**
java.lang.Object
```
public class CmxImageFill
```

Information om bildfyllning
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CmxImageFill()](#CmxImageFill--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImages()](#getImages--) | Hämtar bilderna. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Ställer in bilderna. |
| [getProcedure()](#getProcedure--) | Hämtar proceduren. |
| [setProcedure(CmxProcedure value)](#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-) | Ställer in proceduren. |
| [getTileOffsetX()](#getTileOffsetX--) | Hämtar tile offset X. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Ställer in tile offset X. |
| [getTileOffsetY()](#getTileOffsetY--) | Hämtar tile offset Y. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Ställer in tile offset Y. |
| [getRcpOffset()](#getRcpOffset--) | Hämtar den relativa förskjutningen mellan tile-rader eller kolumner (beror på `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [setRcpOffset(float value)](#setRcpOffset-float-) | Ställer in den relativa förskjutningen mellan tile-rader eller kolumner (beror på `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [getOffsetType()](#getOffsetType--) | Hämtar typen av förskjutningen mellan intilliggande tiles. |
| [setOffsetType(int value)](#setOffsetType-int-) | Ställer in typen av förskjutningen mellan intilliggande tiles. |
| [getPatternWidth()](#getPatternWidth--) | Hämtar bredden på mönstret. |
| [setPatternWidth(float value)](#setPatternWidth-float-) | Ställer in bredden på mönstret. |
| [getPatternHeight()](#getPatternHeight--) | Hämtar höjden på mönstret. |
| [setPatternHeight(float value)](#setPatternHeight-float-) | Ställer in höjden på mönstret. |
| [isRelative()](#isRelative--) | Hämtar ett värde som indikerar om mönsterstorleksvärden är relativa. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ställer in ett värde som indikerar om mönsterstorleksvärden är relativa. |
| [getRotate180()](#getRotate180--) | Hämtar ett värde som indikerar om denna [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) är upp och ner. |
| [setRotate180(boolean value)](#setRotate180-boolean-) | Ställer in ett värde som indikerar om denna [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) är upp och ner. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### CmxImageFill() {#CmxImageFill--}
```
public CmxImageFill()
```


### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Hämtar bilderna.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - bilderna.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Ställer in bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | bilderna. |

### getProcedure() {#getProcedure--}
```
public final CmxProcedure getProcedure()
```


Hämtar proceduren.

**Returns:**
[CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) - the procedure.
### setProcedure(CmxProcedure value) {#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-}
```
public final void setProcedure(CmxProcedure value)
```


Ställer in proceduren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) | proceduren. |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Hämtar tile offset X.

**Returns:**
float - tileförskjutning X.
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Ställer in tile offset X.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | tileförskjutning X. |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Hämtar tile offset Y.

**Returns:**
float - tileförskjutning Y.
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Ställer in tile offset Y.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | tileförskjutning Y. |

### getRcpOffset() {#getRcpOffset--}
```
public final float getRcpOffset()
```


Hämtar den relativa förskjutningen mellan tile‑rader eller kolumner (beror på `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). Dimensionen är bråkdelar av höjd eller bredd.

**Returns:**
float - den relativa förskjutningen mellan tile‑rader eller kolumner (beror på `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))).
### setRcpOffset(float value) {#setRcpOffset-float-}
```
public final void setRcpOffset(float value)
```


Ställer in den relativa förskjutningen mellan tile‑rader eller kolumner (beror på `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). Dimensionen är bråkdelar av höjd eller bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | den relativa förskjutningen mellan tile‑rader eller kolumner (beror på `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |

### getOffsetType() {#getOffsetType--}
```
public final int getOffsetType()
```


Hämtar typen av förskjutningen mellan intilliggande tiles.

**Returns:**
int - typen av förskjutning mellan intilliggande tiles.
### setOffsetType(int value) {#setOffsetType-int-}
```
public final void setOffsetType(int value)
```


Ställer in typen av förskjutningen mellan intilliggande tiles.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | typen av förskjutning mellan intilliggande tiles. |

### getPatternWidth() {#getPatternWidth--}
```
public final float getPatternWidth()
```


Hämtar mönstrets bredd. Använder en gemensam måttenhet för dokumentavstånd om `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) är `false`, annars har den dimensionen av bildpixelns breddbråkdel.

**Returns:**
float - mönstrets bredd.
### setPatternWidth(float value) {#setPatternWidth-float-}
```
public final void setPatternWidth(float value)
```


Ställer in mönstrets bredd. Använder en gemensam måttenhet för dokumentavstånd om `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) är `false`, annars har den dimensionen av bildpixelns breddbråkdel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | mönstrets bredd. |

### getPatternHeight() {#getPatternHeight--}
```
public final float getPatternHeight()
```


Hämtar mönstrets höjd. Använder en gemensam måttenhet för dokumentavstånd om `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) är `false`, annars har den dimensionen av bildpixelns höjdbråkdel.

**Returns:**
float - mönstrets höjd.
### setPatternHeight(float value) {#setPatternHeight-float-}
```
public final void setPatternHeight(float value)
```


Ställer in mönstrets höjd. Använder en gemensam måttenhet för dokumentavstånd om `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) är `false`, annars har den dimensionen av bildpixelns höjdbråkdel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | mönstrets höjd. |

### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Hämtar ett värde som indikerar om mönsterstorleksvärden är relativa.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public final void setRelative(boolean value)
```


Ställer in ett värde som indikerar om mönsterstorleksvärden är relativa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRotate180() {#getRotate180--}
```
public final boolean getRotate180()
```


Hämtar ett värde som indikerar om denna [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) är upp och ner.

Värde: `true` om bilden är upp och ner; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om detta [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) är upp och ner.
### setRotate180(boolean value) {#setRotate180-boolean-}
```
public final void setRotate180(boolean value)
```


Ställer in ett värde som indikerar om denna [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) är upp och ner.

Värde: `true` om bilden är upp och ner; annars, `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | ett värde som indikerar om detta [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) är upp och ner. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En sträng som representerar detta objekt.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.

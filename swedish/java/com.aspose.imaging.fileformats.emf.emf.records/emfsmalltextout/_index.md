---
title: "EmfSmallTextOut"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SMALLTEXTOUT-posten skriver ut en sträng."
type: docs
weight: 147
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

EMR\\_SMALLTEXTOUT-posten skriver ut en sträng.

Om ETO\_SMALL\_CHARS är angivet i fuOptions-fältet innehåller TextString 8-bitars koder för tecken, härledda från de låga bytena i 16-bitars Unicode UTF16-LE teckenkoder, där den högsta byten antas vara 0. Om ETO\_NO\_RECT är angivet i fuOptions-fältet inkluderas inte Bounds-fältet i posten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSmallTextOut`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten för var strängen ska placeras. |
| [setX(int value)](#setX-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten för var strängen ska placeras. |
| [getY()](#getY--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten för var strängen ska placeras. |
| [setY(int value)](#setY-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten för var strängen ska placeras. |
| [getCChars()](#getCChars--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet 16-bitars tecken i strängen. |
| [setCChars(int value)](#setCChars-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet 16-bitars tecken i strängen. |
| [getFuOptions()](#getFuOptions--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar vilka textutskriftsalternativ som ska användas. |
| [setFuOptions(int value)](#setFuOptions-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar vilka textutskriftsalternativ som ska användas. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget, från uppräkningen GraphicsMode (avsnitt 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget, från uppräkningen GraphicsMode (avsnitt 2.1.16). |
| [getExScale()](#getExScale--) | Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i x-riktning. |
| [setExScale(float value)](#setExScale-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i x-riktning. |
| [getEyScale()](#getEyScale--) | Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i y-riktning. |
| [setEyScale(float value)](#setEyScale-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i y-riktning. |
| [getBounds()](#getBounds--) | Hämtar eller anger ett valfritt, 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln i enhetsenheter. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett valfritt, 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln i enhetsenheter. |
| [getTextString()](#getTextString--) | Hämtar eller anger en variabel‑längd sträng som innehåller textsträngen att rita, i antingen 8-bitars eller 16-bitars teckenkoder, enligt värdet i fuOptions-fältet. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Hämtar eller anger en variabel‑längd sträng som innehåller textsträngen att rita, i antingen 8-bitars eller 16-bitars teckenkoder, enligt värdet i fuOptions-fältet. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSmallTextOut`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getX() {#getX--}
```
public int getX()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten för var strängen ska placeras.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten för var strängen ska placeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getY() {#getY--}
```
public int getY()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten för var strängen ska placeras.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten för var strängen ska placeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet 16-bitars tecken i strängen. Strängen är INTE null‑terminerad.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet 16-bitars tecken i strängen. Strängen är INTE null‑terminerad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar vilka textutskriftsalternativ som ska användas. Dessa alternativ anges av ett eller en kombination av värden från uppräkningen ExtTextOutOptions (avsnitt 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar vilka textutskriftsalternativ som ska användas. Dessa alternativ anges av ett eller en kombination av värden från uppräkningen ExtTextOutOptions (avsnitt 2.1.11).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget, från uppräkningen GraphicsMode (avsnitt 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget, från uppräkningen GraphicsMode (avsnitt 2.1.16).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i x-riktning.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i x-riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i y-riktning.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i y-riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett valfritt, 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln i enhetsenheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett valfritt, 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln i enhetsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Hämtar eller anger en variabel‑längd sträng som innehåller textsträngen att rita, i antingen 8-bitars eller 16-bitars teckenkoder, enligt värdet i fuOptions-fältet.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Hämtar eller anger en variabel‑längd sträng som innehåller textsträngen att rita, i antingen 8-bitars eller 16-bitars teckenkoder, enligt värdet i fuOptions-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |


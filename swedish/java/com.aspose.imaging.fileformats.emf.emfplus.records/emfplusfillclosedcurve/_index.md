---
title: "EmfPlusFillClosedCurve"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusFillClosedCurve-posten specificerar fyllning av insidan av en sluten kardinal spline."
type: docs
weight: 32
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

EmfPlusFillClosedCurve-posten specificerar fyllning av insidan av en sluten kardinal spline.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusFillClosedCurve`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [getCompressed()](#getCompressed--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är komprimerad. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är komprimerad. |
| [getWinding()](#getWinding--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är winding. |
| [setWinding(boolean value)](#setWinding-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är winding. |
| [getRelative()](#getRelative--) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är relativ. |
| [setRelative(boolean value)](#setRelative-boolean-) | Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är relativ. |
| [getBrushId()](#getBrushId--) | Hämtar eller anger borstidentifieraren Ett 32‑bitars osignerat heltal som specificerar EmfPlusBrush, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [setBrushId(int value)](#setBrushId-int-) | Hämtar eller anger borstidentifieraren Ett 32‑bitars osignerat heltal som specificerar EmfPlusBrush, vars innehåll bestäms av S‑biten i Flags‑fältet. |
| [getTension()](#getTension--) | Hämtar eller anger spänningen Ett 32‑bitars flyttal som specificerar hur kraftigt splinen böjs när den passerar genom punkterna. |
| [setTension(float value)](#setTension-float-) | Hämtar eller anger spänningen Ett 32‑bitars flyttal som specificerar hur kraftigt splinen böjs när den passerar genom punkterna. |
| [getPointData()](#getPointData--) | Hämtar eller anger punktdata En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Hämtar eller anger punktdata En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusFillClosedCurve`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar eller anger ett värde som indikerar om denna instans är färg. Om satt specificerar BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans är färg. Om satt specificerar BrushId en färg som ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad innehåller BrushId indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1) i EMF+‑objektabellen.

Värde: `true` om denna instans är färg; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är komprimerad. Denna bit indikerar om PointData‑fältet specificerar komprimerad data. Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om rensad, specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. ---------------------- En "winding"‑fyllningsoperation fyller områden enligt regeln för "even-odd parity". Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en sluten kurva på följande sätt: Rita en linje från testpunkten till en punkt som ligger långt från kurvan. Om den linjen korsar kurvan ett udda antal gånger är testpunkten innanför kurvan; annars är testpunkten utanför kurvan. --------------------- En "alternate"‑fyllningsoperation fyller områden enligt regeln för "non-zero". Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en sluten kurva på följande sätt: Rita en linje från en testpunkt till en punkt som ligger långt från kurvan. Räkna antalet gånger kurvan korsar testlinjen från vänster till höger, och räkna antalet gånger kurvan korsar testlinjen från höger till vänster. Om de två siffrorna är lika är testpunkten utanför kurvan; annars är testpunkten innanför kurvan.

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är komprimerad. Denna bit indikerar om PointData‑fältet specificerar komprimerad data. Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. Om rensad, specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater. ---------------------- En "winding"‑fyllningsoperation fyller områden enligt regeln för "even-odd parity". Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en sluten kurva på följande sätt: Rita en linje från testpunkten till en punkt som ligger långt från kurvan. Om den linjen korsar kurvan ett udda antal gånger är testpunkten innanför kurvan; annars är testpunkten utanför kurvan. --------------------- En "alternate"‑fyllningsoperation fyller områden enligt regeln för "non-zero". Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en sluten kurva på följande sätt: Rita en linje från en testpunkt till en punkt som ligger långt från kurvan. Räkna antalet gånger kurvan korsar testlinjen från vänster till höger, och räkna antalet gånger kurvan korsar testlinjen från höger till vänster. Om de två siffrorna är lika är testpunkten utanför kurvan; annars är testpunkten innanför kurvan.

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är winding. Denna bit indikerar hur fyllningsoperationen ska utföras. Om satt är fyllningen en "winding"‑fyllning. Om rensad är fyllningen en "alternate"‑fyllning.

Värde: `true` om winding; annars `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är winding. Denna bit indikerar hur fyllningsoperationen ska utföras. Om satt är fyllningen en "winding"‑fyllning. Om rensad är fyllningen en "alternate"‑fyllning.

Värde: `true` om winding; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är relativ. Denna bit indikerar om PointData‑fältet specificerar relativa eller absoluta positioner. Om satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som angavs av föregående element i arrayen. För det första elementet i PointData antas en tidigare plats med koordinaterna (0,0). Om rensad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras.

Värde: `true` om relativ; annars `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna `EmfPlusFillClosedCurve` är relativ. Denna bit indikerar om PointData‑fältet specificerar relativa eller absoluta positioner. Om satt specificerar varje element i PointData en plats i koordinatrymden som är relativ till platsen som angavs av föregående element i arrayen. För det första elementet i PointData antas en tidigare plats med koordinaterna (0,0). Om rensad specificerar PointData absoluta positioner enligt C‑flaggan. Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras.

Värde: `true` om relativ; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar eller anger borstidentifieraren Ett 32‑bitars osignerat heltal som specificerar EmfPlusBrush, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna borste används för att fylla insidan av den slutna kardinalsplinen.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Hämtar eller anger borstidentifieraren Ett 32‑bitars osignerat heltal som specificerar EmfPlusBrush, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna borste används för att fylla insidan av den slutna kardinalsplinen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Hämtar eller anger spänningen Ett 32‑bitars flyttal som specificerar hur kraftigt splinen böjs när den passerar genom punkterna. Ett värde på 0,0 anger att splinen är en sekvens av raka linjer. När värdet ökar blir kurvan mer rundad. För mer information, se [SPLINE77] och [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Hämtar eller anger spänningen Ett 32‑bitars flyttal som specificerar hur kraftigt splinen böjs när den passerar genom punkterna. Ett värde på 0,0 anger att splinen är en sekvens av raka linjer. När värdet ökar blir kurvan mer rundad. För mer information, se [SPLINE77] och [PETZOLD].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Hämtar eller anger punktdata En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. I en sluten kardinalspline fortsätter kurvan genom den sista punkten i PointData‑arrayen och ansluter till den första punkten i arrayen

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Hämtar eller anger punktdata En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. I en sluten kardinalspline fortsätter kurvan genom den sista punkten i PointData‑arrayen och ansluter till den första punkten i arrayen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |


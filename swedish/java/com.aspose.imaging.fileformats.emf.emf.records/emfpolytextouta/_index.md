---
title: "EmfPolyTextOutA"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_POLYTEXTOUTA-posten ritar en eller flera ASCII-textsträngar med det aktuella teckensnittet och textfärgerna."
type: docs
weight: 97
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutA extends EmfDrawingRecordType
```

EMR\_POLYTEXTOUTA‑posten ritar en eller flera ASCII‑textsträngar med det aktuella teckensnittet och textfärgerna.

Teckensnittet och textfärgerna som används för utdata specificeras av egenskaper i det aktuella tillståndet för uppspelningsenhetens kontext. EMR\_POLYTEXTOUTA SKALL emuleras med en serie EMR\_EXTTEXTOUTW-poster (avsnitt 2.3.5.7), en per sträng. Detta kräver att ASCII‑textsträngen i varje EmrText‑objekt konverteras till Unicode UTF16-LE‑kodning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPolyTextOutA(EmfRecord source)](#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPolyTextOutA`. |
| [EmfPolyTextOutA()](#EmfPolyTextOutA--) | Initierar en ny instans av klassen [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar den omgivande rektangeln i enhetsenheter. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar den omgivande rektangeln i enhetsenheter. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar det aktuella grafikläget, från GraphicsMode‑enumerationen (avsnitt 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar det aktuella grafikläget, från GraphicsMode‑enumerationen (avsnitt 2.1.16). |
| [getExScale()](#getExScale--) | Hämtar eller anger ett 32‑bitars flyttal som specificerar X‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | Hämtar eller anger ett 32‑bitars flyttal som specificerar X‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | Hämtar eller anger ett 32‑bitars flyttal som specificerar Y‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | Hämtar eller anger ett 32‑bitars flyttal som specificerar Y‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE. |
| [getAEmrText()](#getAEmrText--) | Hämtar eller anger en matris av EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängarna i 8‑bitars ASCII‑tecken, med textattribut och avståndsvärden. |
| [setAEmrText(EmfText[] value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Hämtar eller anger en matris av EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängarna i 8‑bitars ASCII‑tecken, med textattribut och avståndsvärden. |
### EmfPolyTextOutA(EmfRecord source) {#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutA(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPolyTextOutA`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfPolyTextOutA() {#EmfPolyTextOutA--}
```
public EmfPolyTextOutA()
```


Initierar en ny instans av klassen [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar den omgivande rektangeln i enhetsenheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar den omgivande rektangeln i enhetsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar det aktuella grafikläget, från GraphicsMode‑enumerationen (avsnitt 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar det aktuella grafikläget, från GraphicsMode‑enumerationen (avsnitt 2.1.16).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar X‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar X‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar Y‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Hämtar eller anger ett 32‑bitars flyttal som specificerar Y‑skalan från sid-enheter till .01 mm‑enheter om grafikläget är GM\_COMPATIBLE.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText[] getAEmrText()
```


Hämtar eller anger en matris av EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängarna i 8‑bitars ASCII‑tecken, med textattribut och avståndsvärden. Antalet EmrText‑objekt anges av cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setAEmrText(EmfText[] value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setAEmrText(EmfText[] value)
```


Hämtar eller anger en matris av EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängarna i 8‑bitars ASCII‑tecken, med textattribut och avståndsvärden. Antalet EmrText‑objekt anges av cStrings.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |


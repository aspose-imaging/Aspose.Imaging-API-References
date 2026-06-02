---
title: "EmfPlusStringFormatData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusStringFormatData-objektet specificerar tabbstopp och teckenpositioner för en grafiksträng."
type: docs
weight: 75
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

EmfPlusStringFormatData-objektet specificerar tabbstopp och teckenpositioner för en grafiksträng.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTabStops()](#getTabStops--) | Hämtar eller anger en valfri matris av flyttal som specificerar de valfria tabbstoppens positioner för detta objekt. |
| [setTabStops(float[] value)](#setTabStops-float---) | Hämtar eller anger en valfri matris av flyttal som specificerar de valfria tabbstoppens positioner för detta objekt. |
| [getCharRange()](#getCharRange--) | Hämtar eller anger en valfri matris av RangeCount EmfPlusCharacterRange-objekt som specificerar intervallet av teckenpositioner inom en textsträng. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Hämtar eller anger en valfri matris av RangeCount EmfPlusCharacterRange-objekt som specificerar intervallet av teckenpositioner inom en textsträng. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Hämtar eller anger en valfri matris av flyttal som specificerar de valfria tabbstoppens positioner för detta objekt. Varje tabbstoppvärde representerar antalet mellanslag mellan tabbstopp eller, för det första tabbstoppet, antalet mellanslag mellan början av en textrad och det första tabbstoppet. Detta fält MÅSTE vara närvarande om värdet på TabStopCount-fältet i EmfPlusStringFormat-objektet är större än 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Hämtar eller anger en valfri matris av flyttal som specificerar de valfria tabbstoppens positioner för detta objekt. Varje tabbstoppvärde representerar antalet mellanslag mellan tabbstopp eller, för det första tabbstoppet, antalet mellanslag mellan början av en textrad och det första tabbstoppet. Detta fält MÅSTE vara närvarande om värdet på TabStopCount-fältet i EmfPlusStringFormat-objektet är större än 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Hämtar eller anger en valfri matris av RangeCount EmfPlusCharacterRange-objekt som specificerar intervallet av teckenpositioner inom en textsträng. Det avgränsande området definieras av det skärmområde som upptas av en grupp tecken specificerade av teckenintervallet. Detta fält MÅSTE vara närvarande om värdet på RangeCount-fältet i EmfPlusStringFormat-objektet är större än 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Hämtar eller anger en valfri matris av RangeCount EmfPlusCharacterRange-objekt som specificerar intervallet av teckenpositioner inom en textsträng. Det avgränsande området definieras av det skärmområde som upptas av en grupp tecken specificerade av teckenintervallet. Detta fält MÅSTE vara närvarande om värdet på RangeCount-fältet i EmfPlusStringFormat-objektet är större än 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |


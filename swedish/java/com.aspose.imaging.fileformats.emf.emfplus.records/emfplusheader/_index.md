---
title: "EmfPlusHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusHeader‑posten specificerar början av EMF‑data i metafilen."
type: docs
weight: 40
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

EmfPlusHeader-posten specificerar början av EMF+‑data i metafilen. EmfPlusHeader-posten MÅSTE vara inbäddad i en EMF EMR\_COMMENT\_EMFPLUS‑post, som MÅSTE vara posten som omedelbart följer EMF‑huvudet i metafilen. EMR\_COMMENT\_EMFPLUS‑posten specificeras i [MS-EMF] avsnitt 2.3.3.2.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusHeader`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDualMode()](#getDualMode--) | Hämtar eller anger ett värde som indikerar om [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Hämtar eller anger ett värde som indikerar om [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | Hämtar eller anger ett värde som indikerar om videovisning. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Hämtar eller anger ett värde som indikerar om videovisning. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Hämtar eller anger EMF‑plus‑flaggorna. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Hämtar eller anger EMF‑plus‑flaggorna. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Hämtar eller anger det logiska dpi‑x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Hämtar eller anger det logiska dpi‑x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Hämtar eller anger det logiska dpi‑y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Hämtar eller anger det logiska dpi‑y. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Hämtar eller anger versionen. |
| [isValid()](#isValid--) | Hämtar ett värde som indikerar om denna instans är giltig. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusHeader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Hämtar eller anger ett värde som indikerar om [dual mode]. Om flaggan är satt indikerar den att denna metafil är \"dual-mode\", vilket betyder att den innehåller två uppsättningar poster, där varje uppsättning fullständigt specificerar grafikens innehåll. Om flaggan är rensad specificeras grafikens innehåll av EMF+‑poster, och eventuellt EMF‑poster som föregås av en EmfPlusGetDC‑post. Om denna flagga är satt bör enbart EMF‑poster räcka för att definiera grafikens innehåll. Observera att oavsett om \"dual-mode\"‑flaggan är satt eller inte, finns vissa EMF‑poster alltid närvarande, nämligen EMF‑kontrollposter och EMF‑poster som innehåller EMF+‑poster. EMF‑kontrollposter specificeras i [MS-EMF] avsnitt 2.3.4.

Värde: `true` om [dual mode]; annars `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Hämtar eller anger ett värde som indikerar om [dual mode]. Om flaggan är satt indikerar den att denna metafil är \"dual-mode\", vilket betyder att den innehåller två uppsättningar poster, där varje uppsättning fullständigt specificerar grafikens innehåll. Om flaggan är rensad specificeras grafikens innehåll av EMF+‑poster, och eventuellt EMF‑poster som föregås av en EmfPlusGetDC‑post. Om denna flagga är satt bör enbart EMF‑poster räcka för att definiera grafikens innehåll. Observera att oavsett om \"dual-mode\"‑flaggan är satt eller inte, finns vissa EMF‑poster alltid närvarande, nämligen EMF‑kontrollposter och EMF‑poster som innehåller EMF+‑poster. EMF‑kontrollposter specificeras i [MS-EMF] avsnitt 2.3.4.

Värde: `true` om [dual mode]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Hämtar eller anger ett värde som indikerar om videovisning. Om flaggan är satt indikerar den att metafilen spelades in med en referensenhet för en videovisning. Om flaggan är rensad spelades metafilen in med en referensenhet för en skrivare.

Värde: `true` om [video display]; annars `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Hämtar eller anger ett värde som indikerar om videovisning. Om flaggan är satt indikerar den att metafilen spelades in med en referensenhet för en videovisning. Om flaggan är rensad spelades metafilen in med en referensenhet för en skrivare.

Värde: `true` om [video display]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Hämtar eller anger EMF‑plus‑flaggorna. Ett 32‑bitars osignerat heltal som innehåller information om hur denna metafil spelades in. Om det 31:a bitet i fältet är satt indikerar flaggan att metafilen spelades in med en referensenhet för en videovisning. Om flaggan är rensad spelades metafilen in med en referensenhet för en skrivare.

Värde: EMF‑plus‑flaggorna.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Hämtar eller anger EMF‑plus‑flaggorna. Ett 32‑bitars osignerat heltal som innehåller information om hur denna metafil spelades in. Om det 31:a bitet i fältet är satt indikerar flaggan att metafilen spelades in med en referensenhet för en videovisning. Om flaggan är rensad spelades metafilen in med en referensenhet för en skrivare.

Värde: EMF‑plus‑flaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Hämtar eller anger det logiska dpi‑x. Ett 32‑bitars osignerat heltal som specificerar den horisontella upplösningen som metafilen spelades in för, i enheter av pixlar per tum.

Värde: Det logiska dpi‑x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Hämtar eller anger det logiska dpi‑x. Ett 32‑bitars osignerat heltal som specificerar den horisontella upplösningen som metafilen spelades in för, i enheter av pixlar per tum.

Värde: Det logiska dpi‑x.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Hämtar eller anger det logiska dpi‑y. Ett 32‑bitars osignerat heltal som specificerar den vertikala upplösningen som metafilen spelades in för, i enheter av linjer per tum

Värde: Det logiska dpi‑y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Hämtar eller anger det logiska dpi‑y. Ett 32‑bitars osignerat heltal som specificerar den vertikala upplösningen som metafilen spelades in för, i enheter av linjer per tum

Värde: Det logiska dpi‑y.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Hämtar eller anger versionen. Ett EmfPlusGraphicsVersion‑objekt (avsnitt 2.2.2.19) som specificerar versionen av operativsystemets grafik som användes för att skapa denna metafil.

Värde: Versionen.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Hämtar eller anger versionen. Ett EmfPlusGraphicsVersion‑objekt (avsnitt 2.2.2.19) som specificerar versionen av operativsystemets grafik som användes för att skapa denna metafil.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Hämtar ett värde som indikerar om denna instans är giltig.

Värde: `true` om denna instans är giltig; annars `false`.

**Returns:**
boolean

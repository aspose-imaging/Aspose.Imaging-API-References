---
title: "EmfExtTextOutW"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_EXTTEXTOUTW ritar en ASCII‑textsträng med det aktuella teckensnittet och textfärgerna."
type: docs
weight: 57
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutW extends EmfDrawingRecordType
```

Den EMR_EXTTEXTOUTW-posten ritar en ASCII-textsträng med det aktuella teckensnittet och textfärgerna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfExtTextOutW(EmfRecord source)](#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfExtTextOutW`. |
| [EmfExtTextOutW()](#EmfExtTextOutW--) | Initierar en ny instans av klassen `EmfExtTextOutW`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget från GraphicsMode‑enumerationen (avsnitt 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget från GraphicsMode‑enumerationen (avsnitt 2.1.16). |
| [getExScale()](#getExScale--) | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs X‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. |
| [setExScale(float value)](#setExScale-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs X‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. |
| [getEyScale()](#getEyScale--) | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs Y‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. |
| [setEyScale(float value)](#setEyScale-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs Y‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. |
| [getWEmrText()](#getWEmrText--) | Hämtar eller anger ett EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängen i 16‑bitars Unicode UTF16‑LE‑tecken, med textattribut och avståndsvärden. |
| [setWEmrText(EmfText value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Hämtar eller anger ett EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängen i 16‑bitars Unicode UTF16‑LE‑tecken, med textattribut och avståndsvärden. |
### EmfExtTextOutW(EmfRecord source) {#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutW(EmfRecord source)
```


Initierar en ny instans av klassen `EmfExtTextOutW`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


Initierar en ny instans av klassen `EmfExtTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19). Det används inte och MÅSTE ignoreras vid mottagning.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19). Det används inte och MÅSTE ignoreras vid mottagning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget från GraphicsMode‑enumerationen (avsnitt 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget från GraphicsMode‑enumerationen (avsnitt 2.1.16).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs X‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. Detta BÖR endast användas om grafikläget som specificeras av iGraphicsMode är GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs X‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. Detta BÖR endast användas om grafikläget som specificeras av iGraphicsMode är GM\_COMPATIBLE.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs Y‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. Detta BÖR endast användas om grafikläget som specificeras av iGraphicsMode är GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn som ska tillämpas längs Y‑axeln för att konvertera från enheter i sidrymd till .01 mm‑enheter. Detta BÖR endast användas om grafikläget som specificeras av iGraphicsMode är GM\_COMPATIBLE.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText getWEmrText()
```


Hämtar eller anger ett EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängen i 16‑bitars Unicode UTF16‑LE‑tecken, med textattribut och avståndsvärden.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setWEmrText(EmfText value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setWEmrText(EmfText value)
```


Hämtar eller anger ett EmrText‑objekt (avsnitt 2.2.5) som specificerar utdata‑strängen i 16‑bitars Unicode UTF16‑LE‑tecken, med textattribut och avståndsvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |


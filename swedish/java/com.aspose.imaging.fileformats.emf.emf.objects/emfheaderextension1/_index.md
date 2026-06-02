---
title: "EmfHeaderExtension1"
second_title: "Aspose.Imaging för Java API-referens"
description: "HeaderExtension1-objektet definierar den första utökningen av EMF‑metafilsrubriken."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

HeaderExtension1-objektet definierar den första utökningen av EMF-metafilhuvudet. Det lägger till stöd för ett PixelFormatDescriptor-objekt (avsnitt 2.2.22) och OpenGL [OPENGL]-poster (avsnitt 2.3.9).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på PixelFormatDescriptor-objektet. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på PixelFormatDescriptor-objektet. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen till PixelFormatDescriptor-objektet. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen till PixelFormatDescriptor-objektet. |
| [getBOpenGl()](#getBOpenGl--) | Hämtar eller anger ett 32-bitars osignerat heltal som indikerar om OpenGL-kommandon finns i metafilen. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som indikerar om OpenGL-kommandon finns i metafilen. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på PixelFormatDescriptor-objektet. Detta MÅSTE vara 0x00000000 om inget pixelformat är angivet.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på PixelFormatDescriptor-objektet. Detta MÅSTE vara 0x00000000 om inget pixelformat är angivet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen till PixelFormatDescriptor-objektet. Detta MÅSTE vara 0x00000000 om inget pixelformat är angivet.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen till PixelFormatDescriptor-objektet. Detta MÅSTE vara 0x00000000 om inget pixelformat är angivet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Hämtar eller anger ett 32-bitars osignerat heltal som indikerar om OpenGL-kommandon finns i metafilen. 0x00000000 OpenGL-poster är inte närvarande i metafilen. 0x00000001 OpenGL-poster är närvarande i metafilen.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som indikerar om OpenGL-kommandon finns i metafilen. 0x00000000 OpenGL-poster är inte närvarande i metafilen. 0x00000001 OpenGL-poster är närvarande i metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


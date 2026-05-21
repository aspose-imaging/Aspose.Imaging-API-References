---
title: "EmfPlusImageAttributes"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusImageAttributes-objektet specificerar hur bitmap-bildfärger manipuleras under rendering."
type: docs
weight: 48
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

EmfPlusImageAttributes-objektet specificerar hur bitmap-bildfärger manipuleras under rendering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur kantförhållanden ska hanteras med ett värde från WrapMode‑enumerationen (avsnitt 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur kantförhållanden ska hanteras med ett värde från WrapMode‑enumerationen (avsnitt 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Hämtar eller anger EmfPlusARGB‑objekt (avsnitt 2.2.2.1) som specificerar kantfärgen att använda när WrapMode‑värdet är WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Hämtar eller anger EmfPlusARGB‑objekt (avsnitt 2.2.2.1) som specificerar kantfärgen att använda när WrapMode‑värdet är WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar objektets klämningsbeteende. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar objektets klämningsbeteende. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur kantförhållanden ska hanteras med ett värde från WrapMode‑enumerationen (avsnitt 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur kantförhållanden ska hanteras med ett värde från WrapMode‑enumerationen (avsnitt 2.1.1.34).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Hämtar eller anger EmfPlusARGB‑objekt (avsnitt 2.2.2.1) som specificerar kantfärgen att använda när WrapMode‑värdet är WrapModeClamp. Denna färg är synlig när källrektangeln som bearbetas av en EmfPlusDrawImage‑post (avsnitt 2.3.4.8) är större än själva bilden.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Hämtar eller anger EmfPlusARGB‑objekt (avsnitt 2.2.2.1) som specificerar kantfärgen att använda när WrapMode‑värdet är WrapModeClamp. Denna färg är synlig när källrektangeln som bearbetas av en EmfPlusDrawImage‑post (avsnitt 2.3.4.8) är större än själva bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar objektets klämningsbeteende. Den används inte förrän detta objekt tillämpas på en bild som ritas. Detta värde MÅSTE vara ett av värdena som definieras i följande tabell.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar objektets klämningsbeteende. Den används inte förrän detta objekt tillämpas på en bild som ritas. Detta värde MÅSTE vara ett av värdena som definieras i följande tabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


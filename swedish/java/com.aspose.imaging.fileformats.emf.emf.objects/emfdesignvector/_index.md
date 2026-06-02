---
title: "EmfDesignVector"
second_title: "Aspose.Imaging för Java API-referens"
description: "DesignVector‑sektion 2.2.3‑objektet definierar designvektorn som specificerar värden för teckensnittets axlar i ett multiple‑master‑teckensnitt."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

DesignVector (avsnitt 2.2.3)-objektet definierar designvektorn, som specificerar värden för teckensnittets axlar i ett multiple‑master‑teckensnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSignature()](#getSignature--) | Hämtar eller anger ett 32‑bitars osignerat heltal som MUST vara satt till värdet 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som MUST vara satt till värdet 0x08007664. |
| [getNumAxes()](#getNumAxes--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet element i Values‑arrayen. |
| [setNumAxes(int value)](#setNumAxes-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet element i Values‑arrayen. |
| [getValues()](#getValues--) | Hämtar eller anger en valfri array av 32‑bitars signerade heltal som specificerar värdena för teckensnittets axlar i ett multiple‑master‑OpenType‑teckensnitt. |
| [setValues(int[] value)](#setValues-int---) | Hämtar eller anger en valfri array av 32‑bitars signerade heltal som specificerar värdena för teckensnittets axlar i ett multiple‑master‑OpenType‑teckensnitt. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som MUST vara satt till värdet 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som MUST vara satt till värdet 0x08007664.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet element i Values‑arrayen. Det MUST vara i intervallet 0 till 16, inklusive.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet element i Values‑arrayen. Det MUST vara i intervallet 0 till 16, inklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Hämtar eller anger en valfri array av 32‑bitars signerade heltal som specificerar värdena för teckensnittets axlar i ett multiple‑master‑OpenType‑teckensnitt. Det maximala antalet värden i arrayen är 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Hämtar eller anger en valfri array av 32‑bitars signerade heltal som specificerar värdena för teckensnittets axlar i ett multiple‑master‑OpenType‑teckensnitt. Det maximala antalet värden i arrayen är 16.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |


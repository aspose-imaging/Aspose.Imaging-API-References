---
title: "ResourceEvent"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller dimensioner för ett ritat objekt."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Innehåller dimensioner för ett ritat objekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initierar en ny instans av klassen `ResourceEvent`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAction()](#getAction--) | Hämtar åtgärd. |
| [setAction(String value)](#setAction-java.lang.String-) | Ställer in åtgärd. |
| [getChanged()](#getChanged--) | Hämtar den semikolonavgränsade listan över delarna av resursen som ändrades sedan föregående händelsehistorik. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Ställer in den semikolonavgränsade listan över delarna av resursen som ändrades sedan föregående händelsehistorik. |
| [getInstanceId()](#getInstanceId--) | Hämtar värdet för xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Hämtar eller anger värdet för xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | Hämtar eller anger den ytterligare beskrivningen av åtgärden. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Hämtar eller anger den ytterligare beskrivningen av åtgärden. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Hämtar eller anger namnet på programvaruagenten. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Hämtar eller anger namnet på programvaruagenten. |
| [getActionDate()](#getActionDate--) | Hämtar eller anger datumet för åtgärden. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Hämtar eller anger datumet för åtgärden. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar det stränginnehållande värdet i XMP-format. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initierar en ny instans av klassen `ResourceEvent`.

### getAction() {#getAction--}
```
public String getAction()
```


Hämtar åtgärd.

Definierade värden är: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nya värden bör vara verb i dåtid.

**Returns:**
java.lang.String - Åtgärden.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Ställer in åtgärd.

Definierade värden är: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Nya värden bör vara verb i dåtid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Åtgärden. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Hämtar den semikolonavgränsade listan över delarna av resursen som ändrades sedan föregående händelsehistorik.

**Returns:**
java.lang.String - Den semikolonavgränsade listan över delarna av resursen som ändrades sedan föregående händelsehistorik.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Ställer in den semikolonavgränsade listan över delarna av resursen som ändrades sedan föregående händelsehistorik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Den semikolonavgränsade listan över delarna av resursen som ändrades sedan föregående händelsehistorik. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Hämtar värdet för xmpMM:InstanceId.

**Returns:**
java.util.UUID - Värdet för xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Hämtar eller anger värdet för xmpMM:InstanceId.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID | Värdet för xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Hämtar eller anger den ytterligare beskrivningen av åtgärden.

Värde: Den ytterligare beskrivningen av åtgärden.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Hämtar eller anger den ytterligare beskrivningen av åtgärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Den ytterligare beskrivningen av åtgärden. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Hämtar eller anger namnet på programvaruagenten.

**Returns:**
java.lang.String - Namnet på programvaruagenten.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Hämtar eller anger namnet på programvaruagenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Namnet på programvaruagenten. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Hämtar eller anger datumet för åtgärden.

**Returns:**
java.util.Date - Datum för åtgärden.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Hämtar eller anger datumet för åtgärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date | Datum för åtgärden. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Hämtar det stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.

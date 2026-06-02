---
title: "ResourceEvent"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält Abmessungen für ein gezeichnetes Objekt."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Enthält Abmessungen für ein gezeichnetes Objekt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initialisiert eine neue Instanz der `ResourceEvent`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAction()](#getAction--) | Gibt die Aktion zurück. |
| [setAction(String value)](#setAction-java.lang.String-) | Setzt die Aktion. |
| [getChanged()](#getChanged--) | Liefert die durch Semikolons getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Legt die durch Semikolons getrennte Liste der Teile der Ressource fest, die seit der vorherigen Ereignisgeschichte geändert wurden. |
| [getInstanceId()](#getInstanceId--) | Liefert den Wert von xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Liefert oder legt den Wert von xmpMM:InstanceId fest. |
| [getParameters()](#getParameters--) | Liefert oder legt die zusätzliche Beschreibung der Aktion fest. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Liefert oder legt die zusätzliche Beschreibung der Aktion fest. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Liefert oder legt den Namen des Software‑Agents fest. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Liefert oder legt den Namen des Software‑Agents fest. |
| [getActionDate()](#getActionDate--) | Liefert oder legt das Aktionsdatum fest. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Liefert oder legt das Aktionsdatum fest. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenfolgenwert im XMP‑Format. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initialisiert eine neue Instanz der `ResourceEvent`-Klasse.

### getAction() {#getAction--}
```
public String getAction()
```


Gibt die Aktion zurück.

Definierte Werte sind: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Neue Werte sollten Verben im Präteritum sein.

**Returns:**
java.lang.String - Die Aktion.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Setzt die Aktion.

Definierte Werte sind: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Neue Werte sollten Verben im Präteritum sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die Aktion. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Liefert die durch Semikolons getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden.

**Returns:**
java.lang.String - Die durch Semikolons getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Legt die durch Semikolons getrennte Liste der Teile der Ressource fest, die seit der vorherigen Ereignisgeschichte geändert wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die durch Semikolons getrennte Liste der Teile der Ressource, die seit der vorherigen Ereignisgeschichte geändert wurden. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Liefert den Wert von xmpMM:InstanceId.

**Returns:**
java.util.UUID - Der Wert von xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Liefert oder legt den Wert von xmpMM:InstanceId fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID | Der Wert von xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Liefert oder legt die zusätzliche Beschreibung der Aktion fest.

Wert: Die zusätzliche Beschreibung der Aktion.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Liefert oder legt die zusätzliche Beschreibung der Aktion fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Die zusätzliche Beschreibung der Aktion. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Liefert oder legt den Namen des Software‑Agents fest.

**Returns:**
java.lang.String - Der Name des Software‑Agents.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Liefert oder legt den Namen des Software‑Agents fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Name des Software‑Agents. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Liefert oder legt das Aktionsdatum fest.

**Returns:**
java.util.Date - Das Aktionsdatum.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Liefert oder legt das Aktionsdatum fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date | Das Aktionsdatum. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenfolgenwert im XMP‑Format.

**Returns:**
java.lang.String - Gibt den im String enthaltenen Wert im XMP-Format zurück.

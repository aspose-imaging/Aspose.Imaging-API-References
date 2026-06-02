---
title: "ResourceEvent"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contenant les dimensions d'un objet dessiné."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Contenant les dimensions d'un objet dessiné.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initialise une nouvelle instance de la classe `ResourceEvent`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAction()](#getAction--) | Obtient l'action. |
| [setAction(String value)](#setAction-java.lang.String-) | Définit l'action. |
| [getChanged()](#getChanged--) | Obtient la liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événements précédent. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Définit la liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événements précédent. |
| [getInstanceId()](#getInstanceId--) | Obtient la valeur de xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Obtient ou définit la valeur de xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | Obtient ou définit la description supplémentaire de l'action. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Obtient ou définit la description supplémentaire de l'action. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Obtient ou définit le nom de l'agent logiciel. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Obtient ou définit le nom de l'agent logiciel. |
| [getActionDate()](#getActionDate--) | Obtient ou définit la date de l'action. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Obtient ou définit la date de l'action. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initialise une nouvelle instance de la classe `ResourceEvent`.

### getAction() {#getAction--}
```
public String getAction()
```


Obtient l'action.

Les valeurs définies sont : converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Les nouvelles valeurs doivent être des verbes au passé.

**Returns:**
java.lang.String - L'action.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Définit l'action.

Les valeurs définies sont : converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Les nouvelles valeurs doivent être des verbes au passé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | L'action. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Obtient la liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événements précédent.

**Returns:**
java.lang.String - La liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événements précédent.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Définit la liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événements précédent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La liste délimitée par des points-virgules des parties de la ressource qui ont été modifiées depuis l'historique d'événements précédent. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Obtient la valeur de xmpMM:InstanceId.

**Returns:**
java.util.UUID - La valeur de xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Obtient ou définit la valeur de xmpMM:InstanceId.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID | La valeur de xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Obtient ou définit la description supplémentaire de l'action.

Valeur : La description supplémentaire de l'action.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Obtient ou définit la description supplémentaire de l'action.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La description supplémentaire de l'action. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Obtient ou définit le nom de l'agent logiciel.

**Returns:**
java.lang.String - Le nom de l'agent logiciel.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Obtient ou définit le nom de l'agent logiciel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le nom de l'agent logiciel. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Obtient ou définit la date de l'action.

**Returns:**
java.util.Date - La date de l'action.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Obtient ou définit la date de l'action.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date | La date de l'action. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.

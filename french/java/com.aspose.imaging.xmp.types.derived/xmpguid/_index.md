---
title: "XmpGuid"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'identifiant unique global XMP."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Représente l'identifiant unique global XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Initialise une nouvelle instance de la classe `XmpGuid`. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Initialise une nouvelle instance de la classe `XmpGuid`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPrefix()](#getPrefix--) | Obtient ou définit le préfixe comme uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Obtient ou définit le préfixe comme uuid. |
| [getValue()](#getValue--) | Obtient ou définit la valeur. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Obtient ou définit la valeur. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtient la valeur de chaîne contenue au format XMP. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Initialise une nouvelle instance de la classe `XmpGuid`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | La valeur. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Initialise une nouvelle instance de la classe `XmpGuid`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| guid | java.util.UUID | L'identifiant unique. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtient ou définit le préfixe comme uuid.

Valeur : le préfixe comme uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Obtient ou définit le préfixe comme uuid.

Valeur : le préfixe comme uuid.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Obtient ou définit la valeur.

Valeur : la valeur.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Obtient ou définit la valeur.

Valeur : la valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtient la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne la valeur de chaîne contenue au format XMP.

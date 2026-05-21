---
title: "XmpDate"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente la date dans le paquet XMP."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Représente la date dans le paquet XMP.

Une valeur date‑heure est représentée en utilisant un sous‑ensemble des formats définis dans Formats de date et d'heure : YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initialise une nouvelle instance de la classe `XmpDate`. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initialise une nouvelle instance de la classe `XmpDate`. |
## Champs

| Champ | Description |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | La chaîne de format ISO 8601 (aller-retour). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Obtient ou définit la valeur de date. |
| [setValue(Date value)](#setValue-java.util.Date-) | Obtient ou définit la valeur de date. |
| [getFormat()](#getFormat--) | Obtient la chaîne de format pour la valeur actuelle. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Renvoie la valeur de chaîne contenue au format XMP. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initialise une nouvelle instance de la classe `XmpDate`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date | Une valeur date-heure représentée à l'aide d'un sous-ensemble du format ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initialise une nouvelle instance de la classe `XmpDate`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dateString | java.lang.String | La représentation sous forme de chaîne de la date. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


La chaîne de format ISO 8601 (aller-retour).

Voir plus : [ ici ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Obtient ou définit la valeur de date.

Valeur : la valeur de date.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Obtient ou définit la valeur de date.

Valeur : la valeur de date.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Obtient la chaîne de format pour la valeur actuelle.

Valeur : la chaîne de format pour la valeur actuelle.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Renvoie la valeur de chaîne contenue au format XMP.

**Returns:**
java.lang.String - Retourne une chaîne contenant la représentation xmp

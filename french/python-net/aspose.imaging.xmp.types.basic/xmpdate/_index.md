---
title: "Classe XmpDate"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Initialise une nouvelle instance de la classe [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Initialise une nouvelle instance de la classe [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | La chaîne de format ISO 8601 (aller-retour). |
| format | string | r | Obtient la chaîne de format pour la valeur actuelle. |
| value | System.DateTime | r/w | Obtient ou définit la valeur de la date. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |
| [get_xmp_representation()](#get_xmp_representation__2) | Renvoie la valeur de chaîne contenue au format XMP. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Initialise une nouvelle instance de la classe [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| date_string | string | La représentation sous forme de chaîne de la date. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Initialise une nouvelle instance de la classe [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| date_time | System.DateTime | Une valeur date-heure représentée à l'aide d'un sous-ensemble du format ISO RFC 8601. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Un clone membre à membre. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Renvoie la valeur de chaîne contenue au format XMP.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie une chaîne contenant la représentation xmp. |



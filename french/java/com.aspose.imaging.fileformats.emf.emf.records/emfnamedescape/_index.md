---
title: "EmfNamedEscape"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement MR_NAMEDESCAPE transmet des informations arbitraires à un pilote d'imprimante spécifié."
type: docs
weight: 75
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

L'enregistrement MR\_NAMEDESCAPE transmet des informations arbitraires à un pilote d'imprimante spécifié.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfNamedEscape`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets dans le champ DriverName. |
| [setCjDriver(int value)](#setCjDriver-int-) | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets dans le champ DriverName. |
| [getCjIn()](#getCjIn--) | Obtient ou définit un entier non signé de 32 bits indiquant le nombre d'octets à transmettre au pilote d'imprimante. |
| [setCjIn(int value)](#setCjIn-int-) | Obtient ou définit un entier non signé de 32 bits indiquant le nombre d'octets à transmettre au pilote d'imprimante. |
| [getDriverName()](#getDriverName--) | Obtient ou définit une chaîne de caractères Unicode de 16 bits qui indique le nom du pilote d'imprimante qui recevra les données. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Obtient ou définit une chaîne de caractères Unicode de 16 bits qui indique le nom du pilote d'imprimante qui recevra les données. |
| [getData()](#getData--) | Obtient ou définit les données à transmettre au pilote d'imprimante. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit les données à transmettre au pilote d'imprimante. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfNamedEscape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets dans le champ DriverName. Cette valeur DOIT être un nombre pair.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets dans le champ DriverName. Cette valeur DOIT être un nombre pair.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Obtient ou définit un entier non signé de 32 bits indiquant le nombre d'octets à transmettre au pilote d'imprimante.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Obtient ou définit un entier non signé de 32 bits indiquant le nombre d'octets à transmettre au pilote d'imprimante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Obtient ou définit une chaîne de caractères Unicode de 16 bits qui indique le nom du pilote d'imprimante qui recevra les données. Cette valeur DOIT avoir une longueur de cjDriver octets et DOIT être terminée par un caractère nul.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Obtient ou définit une chaîne de caractères Unicode de 16 bits qui indique le nom du pilote d'imprimante qui recevra les données. Cette valeur DOIT avoir une longueur de cjDriver octets et DOIT être terminée par un caractère nul.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit les données à transmettre au pilote d'imprimante. Il DOIT y avoir cjIn octets disponibles.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit les données à transmettre au pilote d'imprimante. Il DOIT y avoir cjIn octets disponibles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


---
title: "EmfGlsRecord"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_GLSRECORD spécifie une fonction OpenGL."
type: docs
weight: 64
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

L'enregistrement EMR\_GLSRECORD spécifie une fonction OpenGL.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfGlsRecord`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCbData()](#getCbData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| [setCbData(int value)](#setCbData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| [getData()](#getData--) | Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfGlsRecord`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. Si cette valeur est zéro, aucune donnée n'est attachée à cet enregistrement.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. Si cette valeur est zéro, aucune donnée n'est attachée à cet enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


---
title: "EmfGlsBoundedRecord"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_GLSBOUNDEDRECORD spécifie une fonction OpenGL avec un rectangle englobant pour la sortie."
type: docs
weight: 63
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

L'enregistrement EMR\_GLSBOUNDEDRECORD spécifie une fonction OpenGL avec un rectangle de délimitation pour la sortie.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfGlsBoundedRecord`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit un rectangle englobant, en unités de dispositif, pour la sortie produite par l'exécution de la fonction OpenGL. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit un rectangle englobant, en unités de dispositif, pour la sortie produite par l'exécution de la fonction OpenGL. |
| [getCbData()](#getCbData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| [setCbData(int value)](#setCbData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| [getData()](#getData--) | Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfGlsBoundedRecord`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit un rectangle englobant, en unités de dispositif, pour la sortie produite par l'exécution de la fonction OpenGL.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit un rectangle englobant, en unités de dispositif, pour la sortie produite par l'exécution de la fonction OpenGL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

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


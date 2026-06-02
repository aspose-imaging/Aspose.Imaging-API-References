---
title: "EmfPlusDrawPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusDrawPath spécifie le dessin d'un chemin graphique."
type: docs
weight: 25
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusDrawPath spécifie le dessin d'un chemin graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusDrawPath`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getPenId()](#getPenId--) | Obtient ou définit l'identifiant du stylo Un entier non signé de 32 bits qui spécifie un indice dans la table d'objets EMF+ pour un objet EmfPlusPen (section 2.2.1.7) à utiliser pour le dessin du EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | Obtient ou définit l'identifiant du stylo Un entier non signé de 32 bits qui spécifie un indice dans la table d'objets EMF+ pour un objet EmfPlusPen (section 2.2.1.7) à utiliser pour le dessin du EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusDrawPath`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'indice de l'objet EmfPlusPath (section 2.2.1.6) à dessiner, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'indice de l'objet EmfPlusPath (section 2.2.1.6) à dessiner, dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Obtient ou définit l'identifiant du stylo Un entier non signé de 32 bits qui spécifie un indice dans la table d'objets EMF+ pour un objet EmfPlusPen (section 2.2.1.7) à utiliser pour le dessin du EmfPlusPath. La valeur DOIT être comprise entre 0 et 63, inclus.

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Obtient ou définit l'identifiant du stylo Un entier non signé de 32 bits qui spécifie un indice dans la table d'objets EMF+ pour un objet EmfPlusPen (section 2.2.1.7) à utiliser pour le dessin du EmfPlusPath. La valeur DOIT être comprise entre 0 et 63, inclus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


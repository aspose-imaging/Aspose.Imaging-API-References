---
title: "EmfPlusMetafile"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusMetafileData spécifie un métafichier contenant une image graphique"
type: docs
weight: 55
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

L'objet EmfPlusMetafileData spécifie un métafichier contenant une image graphique
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Initialise une nouvelle instance de la classe `EmfPlusMetafile`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le type de métafichier intégré dans le champ MetafileData. |
| [setType(int value)](#setType-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le type de métafichier intégré dans le champ MetafileData. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets des données du métafichier dans le champ MetafileData. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets des données du métafichier dans le champ MetafileData. |
| [getMetafileData()](#getMetafileData--) | Obtient ou définit des données de longueur variable qui spécifient le métafichier intégré. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Obtient ou définit des données de longueur variable qui spécifient le métafichier intégré. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Initialise une nouvelle instance de la classe `EmfPlusMetafile`.

### getType() {#getType--}
```
public int getType()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le type de métafichier intégré dans le champ MetafileData. Cette valeur DOIT être définie dans l'énumération MetafileDataType (section 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le type de métafichier intégré dans le champ MetafileData. Cette valeur DOIT être définie dans l'énumération MetafileDataType (section 2.1.1.21).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets des données du métafichier dans le champ MetafileData.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets des données du métafichier dans le champ MetafileData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Obtient ou définit des données de longueur variable qui spécifient le métafichier intégré. Le contenu et le format des données peuvent différer selon chaque type de métafichier.

Les images graphiques sont spécifiées par des objets EmfPlusImage (section 2.2.1.4). Un objet EmfPlusMetafile DOIT être présent dans le champ ImageData d'un objet EmfPlusImage si ImageTypeMetafile est indiqué dans son champ Type. Cet objet est générique et est utilisé pour différents types de données, notamment : un métafichier WMF [MS-WMF] ; un métafichier WMF qui peut être placé ; un métafichier EMF [MS-EMF] ; un métafichier EMF+ qui spécifie uniquement des opérations graphiques avec des enregistrements EMF+ ; et un métafichier EMF+ qui spécifie des opérations graphiques avec à la fois des enregistrements EMF+ et EMF. Voir la section 2.2.2 pour la spécification d'objets structurels supplémentaires.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Obtient ou définit des données de longueur variable qui spécifient le métafichier intégré. Le contenu et le format des données peuvent différer selon chaque type de métafichier.

Les images graphiques sont spécifiées par des objets EmfPlusImage (section 2.2.1.4). Un objet EmfPlusMetafile DOIT être présent dans le champ ImageData d'un objet EmfPlusImage si ImageTypeMetafile est indiqué dans son champ Type. Cet objet est générique et est utilisé pour différents types de données, notamment : un métafichier WMF [MS-WMF] ; un métafichier WMF qui peut être placé ; un métafichier EMF [MS-EMF] ; un métafichier EMF+ qui spécifie uniquement des opérations graphiques avec des enregistrements EMF+ ; et un métafichier EMF+ qui spécifie des opérations graphiques avec à la fois des enregistrements EMF+ et EMF. Voir la section 2.2.2 pour la spécification d'objets structurels supplémentaires.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


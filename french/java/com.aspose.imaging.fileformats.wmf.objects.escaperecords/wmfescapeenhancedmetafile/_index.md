---
title: "WmfEscapeEnhancedMetafile"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement Escape Enhanced Meta file."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

L'enregistrement Escape Enhanced Meta file.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtient ou définit l'identifiant du commentaire. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtient ou définit l'identifiant du commentaire. |
| [getCommentType()](#getCommentType--) | Obtient ou définit le type du commentaire. |
| [setCommentType(int value)](#setCommentType-int-) | Obtient ou définit le type du commentaire. |
| [getVersion()](#getVersion--) | Obtient ou définit la version. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit la version. |
| [getChecksum()](#getChecksum--) | Obtient ou définit la somme de contrôle. |
| [setChecksum(int value)](#setChecksum-int-) | Obtient ou définit la somme de contrôle. |
| [getFlags()](#getFlags--) | Obtient ou définit les indicateurs. |
| [setFlags(int value)](#setFlags-int-) | Obtient ou définit les indicateurs. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Obtient ou définit le nombre d’enregistrements de commentaire. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Obtient ou définit le nombre d’enregistrements de commentaire. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Obtient ou définit la taille de l’enregistrement actuel. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Obtient ou définit la taille de l’enregistrement actuel. |
| [getRemainingBytes()](#getRemainingBytes--) | Obtient ou définit les octets restants. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Obtient ou définit les octets restants. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Obtient ou définit la taille des données du métafichier amélioré. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Obtient ou définit la taille des données du métafichier amélioré. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Obtient ou définit les données du métafichier amélioré. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Obtient ou définit les données du métafichier amélioré. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtient ou définit l'identifiant du commentaire.

Valeur : Un entier non signé de 32 bits qui définit cet enregistrement comme un enregistrement de commentaire WMF. Cette valeur DOIT être 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtient ou définit l'identifiant du commentaire.

Valeur : Un entier non signé de 32 bits qui définit cet enregistrement comme un enregistrement de commentaire WMF. Cette valeur DOIT être 0x43464D57.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Obtient ou définit le type du commentaire.

Valeur : Un entier non signé de 32 bits qui identifie le type de commentaire dans cet enregistrement. Cette valeur DOIT être 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Obtient ou définit le type du commentaire.

Valeur : Un entier non signé de 32 bits qui identifie le type de commentaire dans cet enregistrement. Cette valeur DOIT être 0x00000001.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit la version.

Valeur : Un entier non signé de 32 bits qui spécifie l’interopérabilité du métafichier EMF. Cela DEVRAIT être 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit la version.

Valeur : Un entier non signé de 32 bits qui spécifie l’interopérabilité du métafichier EMF. Cela DEVRAIT être 0x00010000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Obtient ou définit la somme de contrôle.

Valeur : Un entier non signé de 16 bits utilisé pour valider la conformité du flux EMF incorporé. Cette valeur DOIT être le complément à un du résultat de l’application d’une opération XOR à tous les WORD du flux EMF.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Obtient ou définit la somme de contrôle.

Valeur : Un entier non signé de 16 bits utilisé pour valider la conformité du flux EMF incorporé. Cette valeur DOIT être le complément à un du résultat de l’application d’une opération XOR à tous les WORD du flux EMF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtient ou définit les indicateurs.

Valeur : Cet entier non signé de 32 bits n’est pas utilisé et DOIT être mis à zéro.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtient ou définit les indicateurs.

Valeur : Cet entier non signé de 32 bits n’est pas utilisé et DOIT être mis à zéro.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Obtient ou définit le nombre d’enregistrements de commentaire.

Valeur : Un entier non signé de 32 bits qui indique le nombre total d’enregistrements consécutifs META_ESCAPE_ENHANCED_METAFILE contenant le métafichier EMF incorporé.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Obtient ou définit le nombre d’enregistrements de commentaire.

Valeur : Un entier non signé de 32 bits qui indique le nombre total d’enregistrements consécutifs META_ESCAPE_ENHANCED_METAFILE contenant le métafichier EMF incorporé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Obtient ou définit la taille de l’enregistrement actuel.

Valeur : Un entier non signé de 32 bits qui indique la taille, en octets, du champ EnhancedMetafileData. Cette valeur DOIT être inférieure ou égale à 8 192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Obtient ou définit la taille de l’enregistrement actuel.

Valeur : Un entier non signé de 32 bits qui indique la taille, en octets, du champ EnhancedMetafileData. Cette valeur DOIT être inférieure ou égale à 8 192.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Obtient ou définit les octets restants.

Valeur : Un entier non signé de 32 bits qui indique le nombre d’octets du flux EMF restant à traiter après cet enregistrement. Ces octets EMF supplémentaires DOIVENT suivre dans les champs EnhancedMetafileData des enregistrements d’échappement META_ESCAPE_ENHANDED_METAFILE subséquents.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Obtient ou définit les octets restants.

Valeur : Un entier non signé de 32 bits qui indique le nombre d’octets du flux EMF restant à traiter après cet enregistrement. Ces octets EMF supplémentaires DOIVENT suivre dans les champs EnhancedMetafileData des enregistrements d’échappement META_ESCAPE_ENHANDED_METAFILE subséquents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Obtient ou définit la taille des données du métafichier amélioré.

Valeur : Un entier non signé de 32 bits qui indique la taille totale du flux EMF incorporé dans cette séquence d’enregistrements META_ESCAPE_ENHANCED_METAFILE.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Obtient ou définit la taille des données du métafichier amélioré.

Valeur : Un entier non signé de 32 bits qui indique la taille totale du flux EMF incorporé dans cette séquence d’enregistrements META_ESCAPE_ENHANCED_METAFILE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Obtient ou définit les données du métafichier amélioré.

Valeur : Un segment d’un fichier EMF. Les octets des enregistrements consécutifs META_ESCAPE_ENHANCED_METAFILE DOIVENT être concaténés pour représenter le fichier EMF complet incorporé.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Obtient ou définit les données du métafichier amélioré.

Valeur : Un segment d’un fichier EMF. Les octets des enregistrements consécutifs META_ESCAPE_ENHANCED_METAFILE DOIVENT être concaténés pour représenter le fichier EMF complet incorporé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |


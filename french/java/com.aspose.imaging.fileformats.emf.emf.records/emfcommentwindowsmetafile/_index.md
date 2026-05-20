---
title: "EmfCommentWindowsMetaFile"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COMMENT_WINDOWS_METAFILE spécifie une image dans un métafichier WMF intégré."
type: docs
weight: 33
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

L'enregistrement EMR\_COMMENT\_WINDOWS\_METAFILE spécifie une image dans un métafichier WMF intégré.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCommentWindowsMetaFile`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la version du métafichier WMF en termes de prise en charge des bitmaps indépendants du dispositif (DIB), à partir de l'énumération WMF MetafileVersion ([MS-WMF] section 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la version du métafichier WMF en termes de prise en charge des bitmaps indépendants du dispositif (DIB), à partir de l'énumération WMF MetafileVersion ([MS-WMF] section 2.1.1.19). |
| [getChecksum()](#getChecksum--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la somme de contrôle de cet enregistrement. |
| [setChecksum(int value)](#setChecksum-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la somme de contrôle de cet enregistrement. |
| [getFlags()](#getFlags--) | Obtient ou définit une valeur de 32 bits qui DOIT être 0x00000000 et DOIT être ignorée. |
| [setFlags(int value)](#setFlags-int-) | Obtient ou définit une valeur de 32 bits qui DOIT être 0x00000000 et DOIT être ignorée. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du métafichier WMF dans le champ WinMetafile. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du métafichier WMF dans le champ WinMetafile. |
| [getWinMetafile()](#getWinMetafile--) | Obtient ou définit un tampon qui contient le métafichier WMF. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Obtient ou définit un tampon qui contient le métafichier WMF. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCommentWindowsMetaFile`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la version du métafichier WMF en termes de prise en charge des bitmaps indépendants du dispositif (DIB), à partir de l'énumération WMF MetafileVersion ([MS-WMF] section 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la version du métafichier WMF en termes de prise en charge des bitmaps indépendants du dispositif (DIB), à partir de l'énumération WMF MetafileVersion ([MS-WMF] section 2.1.1.19).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la somme de contrôle de cet enregistrement.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la somme de contrôle de cet enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtient ou définit une valeur de 32 bits qui DOIT être 0x00000000 et DOIT être ignorée.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtient ou définit une valeur de 32 bits qui DOIT être 0x00000000 et DOIT être ignorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du métafichier WMF dans le champ WinMetafile.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du métafichier WMF dans le champ WinMetafile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Obtient ou définit un tampon qui contient le métafichier WMF.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Obtient ou définit un tampon qui contient le métafichier WMF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |


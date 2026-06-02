---
title: "EmfCreateMonoBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_CREATEMONOBRUSH définit une brosse à motif monochrome pour les opérations graphiques."
type: docs
weight: 39
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_CREATEMONOBRUSH définit une brosse à motif monochrome pour les opérations graphiques. Le motif est spécifié par un DIB monochrome.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCreateMonoBrush`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau à motif monochrome dans la table d'objets EMF (section 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau à motif monochrome dans la table d'objets EMF (section 3.1.1.1). |
| [getUsage()](#getUsage--) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table des couleurs dans l'en-tête DIB. |
| [setUsage(int value)](#setUsage-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs de la table des couleurs dans l'en-tête DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Obtient ou définit un tampon contenant un DIB empaqueté sous la forme d'un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon contenant un DIB empaqueté sous la forme d'un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCreateMonoBrush`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau à motif monochrome dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau à motif monochrome dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table des couleurs de l’en-tête DIB. Cette valeur DOIT appartenir à l’énumération DIBColors (section 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table des couleurs de l’en-tête DIB. Cette valeur DOIT appartenir à l’énumération DIBColors (section 2.1.9).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Obtient ou définit un tampon contenant un DIB empaqueté sous la forme d’un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). Il n’est pas nécessaire qu’il soit contigu avec la partie fixe de l’enregistrement EMR\_CREATEDIBPATTERNBRUSHPT.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon contenant un DIB empaqueté sous la forme d’un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). Il n’est pas nécessaire qu’il soit contigu avec la partie fixe de l’enregistrement EMR\_CREATEDIBPATTERNBRUSHPT.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |


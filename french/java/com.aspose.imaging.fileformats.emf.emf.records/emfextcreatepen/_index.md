---
title: "EmfExtCreatePen"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_EXTCREATEPEN définit un crayon logique étendu pour les opérations graphiques."
type: docs
weight: 52
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_EXTCREATEPEN définit un crayon logique étendu pour les opérations graphiques. Un DIB optionnel peut être spécifié pour être utilisé comme style de ligne.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfExtCreatePen`. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Initialise une nouvelle instance de la classe `EmfExtCreatePen`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPen()](#getIhPen--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique étendu dans la table d'objets EMF (section 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique étendu dans la table d'objets EMF (section 3.1.1.1). |
| [getElp()](#getElp--) | Obtient ou définit un objet LogPenEx (section 2.2.20) qui spécifie un stylo logique étendu avec des attributs incluant un tableau de styles de ligne optionnel. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Obtient ou définit un objet LogPenEx (section 2.2.20) qui spécifie un stylo logique étendu avec des attributs incluant un tableau de styles de ligne optionnel. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Obtient ou définit un tampon optionnel contenant un DIB empaqueté sous la forme d'un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit un tampon optionnel contenant un DIB empaqueté sous la forme d'un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Initialise une nouvelle instance de la classe `EmfExtCreatePen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | L'enregistrement. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Initialise une nouvelle instance de la classe `EmfExtCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique étendu dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique étendu dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Obtient ou définit un objet LogPenEx (section 2.2.20) qui spécifie un stylo logique étendu avec des attributs incluant un tableau de styles de ligne optionnel.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Obtient ou définit un objet LogPenEx (section 2.2.20) qui spécifie un stylo logique étendu avec des attributs incluant un tableau de styles de ligne optionnel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Obtient ou définit un tampon optionnel contenant un DIB empaqueté sous la forme d'un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). Il n'est pas nécessaire qu'il soit contigu avec la partie fixe de l'enregistrement EMR\_EXTCREATEPEN.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Obtient ou définit un tampon optionnel contenant un DIB empaqueté sous la forme d'un objet WMF DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). Il n'est pas nécessaire qu'il soit contigu avec la partie fixe de l'enregistrement EMR\_EXTCREATEPEN.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |


---
title: "Classe EmfPlusSerializableObject"
type: docs
weight: 440
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

**Summary:** The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSerializableObject(source)](#EmfPlusSerializableObject_source_1) | Initialise une nouvelle instance de la classe [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| tampon | System.Byte | r/w | Obtient ou définit un tableau de BufferSize octets contenant le bloc de paramètres des effets d'image sérialisés<br/>            qui correspond au GUID dans le champ ObjectGUID. Cela DOIT être l'un des objets Image Effects (section 2.2.3). |
| buffer_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets du champ Buffer aligné sur 32 bits. |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. Ce champ DOIT être mis à zéro<br/>            et DOIT être ignoré à la réception. |
| image_effect | [EmfPlusImageEffectsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype/) | r/w | Obtient ou définit l'effet d'image. |
| object_guid | [GuidPacketRepresentation](/imaging/python-net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/) | r/w | Obtient ou définit la valeur de représentation du paquet GUID ([MS-DTYP] section 2.3.4.2)<br/>            pour l'effet d'image. Cela DOIT correspondre à l'un des identifiants ImageEffects (section 2.1.3.1). |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusSerializableObject(source) {#EmfPlusSerializableObject_source_1}


```
 EmfPlusSerializableObject(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |


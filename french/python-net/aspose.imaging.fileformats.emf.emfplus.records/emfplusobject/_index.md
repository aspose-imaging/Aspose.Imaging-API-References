---
title: "Classe EmfPlusObject"
type: docs
weight: 330
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Initialise une nouvelle instance de la classe [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui DOIT définir le nombre aligné sur 32 bits de<br/>            octets de données dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| flags | int | r/w | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont<br/>            l'opération doit être effectuée et sur la structure de l'enregistrement. |
| is_continuable | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est continuable.<br/>            Indique que la définition de l'objet se poursuit dans l'enregistrement EmfPlusObject suivant<br/>            . Ce drapeau n'est jamais défini dans l'enregistrement final qui définit l'objet. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Obtient ou définit un tableau d'octets contenant les données pour le type d'objet spécifié dans<br/>            le champ Flags. Le contenu et le format des données peuvent différer selon chaque type d'objet. Voir<br/>            les définitions individuelles des objets dans la section 2.2.1 pour plus d'informations. |
| object_id | System.Byte | r/w | Obtient ou définit l'identifiant de l'objet.<br/>            L'index dans la table d'objets EMF+ à associer à l'objet<br/>            créé par cet enregistrement. La valeur DOIT être comprise entre 0 et 63, inclus. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Obtient ou définit le type de l'objet. |
| size | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre aligné sur 32 bits d'octets<br/>            dans l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| total_object_size | int | r/w | Obtient ou définit la taille totale de l'objet.<br/>            Si l'enregistrement est continuable, lorsque le bit de continuation est défini, ce champ<br/>            sera présent. Les objets continués possèdent plusieurs enregistrements EMF+ commençant par<br/>            EmfPlusContineudObjectRecord. Chaque EmfPlusContinuedObjectRecord contiendra un<br/>            TotalObjectSize. Une fois le nombre d'octets indiqué par TotalObjectSize lu, l'enregistrement EMF+ suivant ne sera plus considéré comme faisant partie de l'objet continu. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Initialise une nouvelle instance de la classe [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La source. |


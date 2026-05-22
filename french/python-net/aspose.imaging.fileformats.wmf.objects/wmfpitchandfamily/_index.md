---
title: "WmfPitchAndFamily Classe"
type: docs
weight: 480
url: /fr/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---

**Summary:** The PitchAndFamily object specifies the pitch and family properties of a<br/>                Font object (section 2.2.1.2). Pitch refers to the width of the<br/>                characters, and family refers to the general appearance of a font.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily__1) | Initialise une nouvelle instance de la classe WmfPitchAndFamily |
| [WmfPitchAndFamily(byte_data)](#WmfPitchAndFamily_byte_data_2) | Initialise une nouvelle instance de la [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            structure. |
| [WmfPitchAndFamily(pitch, family)](#WmfPitchAndFamily_pitch_family_3) | Initialise une nouvelle instance de la [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            structure. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| byte_data | System.Byte | r/w | Définit les données **byte**. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | r | Obtient une propriété d'une police qui décrit son apparence générale.<br/>                Cette valeur DOIT être une valeur dans l'énumération FamilyFont |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | r | Obtient une propriété d'une police qui décrit le crénage, des<br/>                caractères. Cette valeur DOIT être une valeur dans l'énumération PitchFont. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_byte()](#to_byte__1) | Vers le byte. |


### Constructor: WmfPitchAndFamily() {#WmfPitchAndFamily__1}


```
 WmfPitchAndFamily() 
```

Initialise une nouvelle instance de la classe WmfPitchAndFamily

### Constructor: WmfPitchAndFamily(byte_data) {#WmfPitchAndFamily_byte_data_2}


```
 WmfPitchAndFamily(byte_data) 
```

Initialise une nouvelle instance de la [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            structure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| byte_data | System.Byte | Les données **byte**. |

### Constructor: WmfPitchAndFamily(pitch, family) {#WmfPitchAndFamily_pitch_family_3}


```
 WmfPitchAndFamily(pitch, family) 
```

Initialise une nouvelle instance de la [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            structure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | Le crénage. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | La famille. |

### Method: to_byte() {#to_byte__1}


```
 to_byte() 
```

Vers le byte.

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | La valeur du byte. |



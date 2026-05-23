---
title: "WmfPitchAndFamily Classe"
type: docs
weight: 480
url: /it/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---

**Summary:** The PitchAndFamily object specifies the pitch and family properties of a<br/>                Font object (section 2.2.1.2). Pitch refers to the width of the<br/>                characters, and family refers to the general appearance of a font.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily__1) | Inizializza una nuova istanza della classe WmfPitchAndFamily |
| [WmfPitchAndFamily(byte_data)](#WmfPitchAndFamily_byte_data_2) | Inizializza una nuova istanza della [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct. |
| [WmfPitchAndFamily(pitch, family)](#WmfPitchAndFamily_pitch_family_3) | Inizializza una nuova istanza della [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| byte_data | System.Byte | r/w | Imposta i dati **byte**. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | r | Ottiene una proprietà di un font che descrive il suo aspetto generale.<br/>                Questo DEVE essere un valore nell'enumerazione FamilyFont |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | r | Ottiene una proprietà di un font che descrive la spaziatura, dei<br/>                caratteri. Questo DEVE essere un valore nell'enumerazione PitchFont. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [to_byte()](#to_byte__1) | Al byte. |


### Constructor: WmfPitchAndFamily() {#WmfPitchAndFamily__1}


```
 WmfPitchAndFamily() 
```

Inizializza una nuova istanza della classe WmfPitchAndFamily

### Constructor: WmfPitchAndFamily(byte_data) {#WmfPitchAndFamily_byte_data_2}


```
 WmfPitchAndFamily(byte_data) 
```

Inizializza una nuova istanza della [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| byte_data | System.Byte | I dati **byte**. |

### Constructor: WmfPitchAndFamily(pitch, family) {#WmfPitchAndFamily_pitch_family_3}


```
 WmfPitchAndFamily(pitch, family) 
```

Inizializza una nuova istanza della [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/)<br/>            struct.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pitch | [WmfPitchFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfpitchfont/) | La spaziatura. |
| family | [WmfFamilyFont](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffamilyfont/) | La famiglia. |

### Method: to_byte() {#to_byte__1}


```
 to_byte() 
```

Al byte.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | Il valore byte. |



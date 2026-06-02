---
title: "Classe EmfHeaderExtension2"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---

**Summary:** The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the<br/>            ability to measure device surfaces in micrometers, which enhances the resolution and scalability of EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension2

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfHeaderExtension2()](#EmfHeaderExtension2__1) | Initialise une nouvelle instance de la classe EmfHeaderExtension2 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives <br/>            en unités de dispositif du plus petit rectangle pouvant être dessiné autour de l'image stockée dans <br/>            le métafichier |
| octets | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique la taille du métafichier, en octets |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui indique la taille du dispositif de référence, en pixels |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en .01 millimètre <br/>            unités, d'un rectangle qui entoure l'image stockée dans le métafichier |
| handles | int | r/w | Obtient ou définit un entier non signé de 16 bits qui indique le nombre d'objets graphiques qui seront utilisés pendant le traitement du métafichier |
| micrometers_x | int | r/w | Obtient ou définit la taille horizontale de 32 bits du dispositif d'affichage pour lequel l'image du métafichier a été générée, en micromètres |
| micrometers_y | int | r/w | Obtient ou définit la taille verticale de 32 bits du dispositif d'affichage pour lequel l'image du métafichier a été générée, en micromètres. |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtient ou définit un objet WMF SizeL qui indique la taille du dispositif de référence, en millimètres |
| n_desription | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le nombre de caractères dans le tableau <br/>            qui contient la description du contenu du métafichier. Cette valeur est zéro s'il n'y a pas de chaîne de description. |
| n_pal_entries | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'entrées dans la palette du métafichier <br/>            . La palette se trouve dans l'enregistrement EMR_EOF |
| off_description | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le décalage depuis le début de cet <br/>            enregistrement jusqu'au tableau qui contient la description du contenu du métafichier |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Obtient ou définit un entier non signé de 32 bits qui indique la signature de l'enregistrement. Cette valeur DOIT être ENHMETA_SIGNATURE, <br/>            provenant de l'énumération FormatSignature (section 2.1.14). |
| enregistrements | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'enregistrements dans le métafichier |
| réservé | int | r/w | Obtient ou définit un entier non signé de 16 bits qui DOIT être 0x0000 et DOIT être ignoré |
| valid | bool | r | Obtient une valeur indiquant si cet [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) est valide. |
| version | int | r/w | Obtient ou définit Version (4 octets) : un entier non signé de 32 bits qui spécifie l’interopérabilité du métafichier EMF. Cette valeur SHOULD être 0x00010000 |


### Constructor: EmfHeaderExtension2() {#EmfHeaderExtension2__1}


```
 EmfHeaderExtension2() 
```

Initialise une nouvelle instance de la classe EmfHeaderExtension2


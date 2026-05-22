---
title: "Classe EmfHeaderExtension1"
type: docs
weight: 90
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | Initialise une nouvelle instance de la classe EmfHeaderExtension1 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique si les commandes OpenGL sont présentes dans le métafichier.<br/>            0x00000000 Les enregistrements OpenGL ne sont pas présents dans le métafichier.<br/>            0x00000001 Les enregistrements OpenGL sont présents dans le métafichier. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie les limites rectangulaires inclusives-inclusives <br/>            en unités de dispositif du plus petit rectangle pouvant être dessiné autour de l'image stockée dans <br/>            le métafichier |
| octets | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique la taille du métafichier, en octets |
| cb_pixel_format | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille de l'objet PixelFormatDescriptor. <br/>            Cela DOIT être 0x00000000 si aucun format de pixel n'est défini |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtient ou définit un objet WMF SizeL ([MS-WMF] section 2.2.2.22) qui indique la taille du dispositif de référence, en pixels |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL qui spécifie les dimensions rectangulaires inclusives-inclusives, en .01 millimètre <br/>            unités, d'un rectangle qui entoure l'image stockée dans le métafichier |
| handles | int | r/w | Obtient ou définit un entier non signé de 16 bits qui indique le nombre d'objets graphiques qui seront utilisés pendant le traitement du métafichier |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtient ou définit un objet WMF SizeL qui indique la taille du dispositif de référence, en millimètres |
| n_desription | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le nombre de caractères dans le tableau <br/>            qui contient la description du contenu du métafichier. Cette valeur est zéro s'il n'y a pas de chaîne de description. |
| n_pal_entries | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'entrées dans la palette du métafichier <br/>            . La palette se trouve dans l'enregistrement EMR_EOF |
| off_description | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le décalage depuis le début de cet <br/>            enregistrement jusqu'au tableau qui contient la description du contenu du métafichier |
| off_pixel_format | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage vers l'objet PixelFormatDescriptor.<br/>            Cela DOIT être 0x00000000 si aucun format de pixel n'est défini. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Obtient ou définit un entier non signé de 32 bits qui indique la signature de l'enregistrement. Cette valeur DOIT être ENHMETA_SIGNATURE, <br/>            provenant de l'énumération FormatSignature (section 2.1.14). |
| enregistrements | int | r/w | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'enregistrements dans le métafichier |
| réservé | int | r/w | Obtient ou définit un entier non signé de 16 bits qui DOIT être 0x0000 et DOIT être ignoré |
| valid | bool | r | Obtient une valeur indiquant si cet [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) est valide. |
| version | int | r/w | Obtient ou définit Version (4 octets) : un entier non signé de 32 bits qui spécifie l’interopérabilité du métafichier EMF. Cette valeur SHOULD être 0x00010000 |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

Initialise une nouvelle instance de la classe EmfHeaderExtension1


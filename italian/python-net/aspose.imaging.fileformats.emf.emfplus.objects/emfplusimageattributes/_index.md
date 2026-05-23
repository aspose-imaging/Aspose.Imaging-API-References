---
title: "EmfPlusImageAttributes Classe"
type: docs
weight: 390
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Inizializza una nuova istanza della classe EmfPlusImageAttributes |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore del bordo da utilizzare <br/>            quando il valore WrapMode è WrapModeClamp. Questo colore è visibile quando il <br/>            rettangolo sorgente elaborato da un record EmfPlusDrawImage (sezione 2.3.4.8)<br/>            è più grande dell'immagine stessa. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il comportamento di clamp dell'oggetto.<br/>            Non viene utilizzato finché questo oggetto non viene applicato a un'immagine in <br/>            fase di disegno. Questo valore DEVE essere uno dei valori definiti nella <br/>            tabella seguente. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Ottiene o imposta la versione. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come gestire le condizioni di bordo con <br/>            un valore dell'enumerazione WrapMode (sezione 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Inizializza una nuova istanza della classe EmfPlusImageAttributes


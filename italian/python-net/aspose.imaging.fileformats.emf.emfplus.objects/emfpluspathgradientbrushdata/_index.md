---
title: "EmfPlusPathGradientBrushData Classe"
type: docs
weight: 500
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Inizializza una nuova istanza della classe EmfPlusPathGradientBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Ottiene o imposta il confine del pennello a gradiente di percorso, che è specificato da un percorso o da una spline cardinale chiusa. <br/>            Se il flag BrushDataPath è impostato nel campo BrushDataFlags, questo campo DEVE contenere un oggetto EmfPlusBoundaryPathData (sezione 2.2.2.6); <br/>            altrimenti, questo campo DEVE contenere un oggetto EmfPlusBoundaryPointData (sezione 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData.<br/>            Questo valore DEVE essere composto dai flag BrushData (sezione 2.1.2.1). I seguenti flag sono rilevanti per un pennello a gradiente di percorso: |
| center_argb_32_color | int | r/w | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del <br/>            pennello a gradiente di percorso, che è il colore che appare nel punto centrale del pennello. <br/>            Il colore del pennello cambia gradualmente dal colore del confine <br/>            al colore centrale man mano che si sposta dal confine al punto centrale. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello a gradiente di percorso, <br/>            che è il colore che appare nel punto centrale del pennello. Il colore del<br/>            pennello cambia gradualmente dal colore del confine al colore centrale man mano che si sposta<br/>            dal confine al punto centrale. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Ottiene o imposta un oggetto opzionale EmfPlusPathGradientBrushOptionalData (sezione 2.2.2.30) che <br/>            specifica dati aggiuntivi per il pennello a gradiente di percorso. <br/>            Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags. |
| surrounding_argb_32_colors | int[] | r/w | Ottiene o imposta un array di SurroundingColorCount oggetti EmfPlusARGB <br/>            che specificano i colori per punti discreti sul confine del pennello. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica<br/>            se dipingere l'area al di fuori del confine del pennello. Quando si dipinge <br/>            al di fuori del confine, la modalità di avvolgimento specifica come il gradiente di colore viene ripetuto |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Inizializza una nuova istanza della classe EmfPlusPathGradientBrushData


---
title: "Classe CmxImageFill"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Inizializza una nuova istanza della classe CmxImageFill |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Ottiene o imposta le immagini. |
| is_relative | bool | r/w | Ottiene o imposta un valore che indica se i valori di dimensione dei pattern sono relativi. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Ottiene o imposta il tipo di offset tra le piastrelle adiacenti. |
| pattern_height | float | r/w | Ottiene o imposta l'altezza del pattern.<br/>            Utilizza l'unità di misura di distanza comune del documento nel caso in cui [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) sia <c>false</c>,<br/>            altrimenti ha la dimensione della frazione di altezza del pixel dell'immagine. |
| pattern_width | float | r/w | Ottiene o imposta la larghezza del pattern.<br/>            Utilizza l'unità di misura di distanza comune del documento nel caso in cui [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) sia <c>false</c>,<br/>            altrimenti ha la dimensione della frazione di larghezza del pixel dell'immagine. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Ottiene o imposta la procedura. |
| rcp_offset | float | r/w | Ottiene o imposta l'offset relativo tra le righe o le colonne delle piastrelle (dipende da [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            La dimensione è frazioni dell'altezza o della larghezza. |
| rotate180 | bool | r/w | Ottiene o imposta un valore che indica se questo [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) è capovolto. |
| tile_offset_x | float | r/w | Ottiene o imposta il tile offset X. |
| tile_offset_y | float | r/w | Ottiene o imposta il tile offset Y. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Inizializza una nuova istanza della classe CmxImageFill


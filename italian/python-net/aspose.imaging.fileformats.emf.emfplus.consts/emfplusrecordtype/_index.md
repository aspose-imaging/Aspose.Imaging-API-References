---
title: "Enumerazione EmfPlusRecordType"
type: docs
weight: 360
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

L'enumerazione RecordType definisce i tipi di record utilizzati nei metafili EMF+.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | Questo record apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso. I contenitori grafici sono usati per conservare gli elementi dello stato grafico. |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | Questo record apre un nuovo contenitore di stato grafico. |
| EMF_PLUS_CLEAR | Questo record cancella lo <c>spazio di coordinate</c> di output e lo inizializza con un colore di sfondo e trasparenza specificati. |
| EMF_PLUS_COMMENT | Questo record specifica dati privati arbitrari. |
| EMF_PLUS_DRAW_ARC | Il record definisce i tratti della penna per disegnare un arco di un'ellisse. |
| EMF_PLUS_DRAW_BEZIERS | Questo record definisce i tratti della penna per disegnare una spline di Bezier. |
| EMF_PLUS_DRAW_CLOSED_CURVE | Questo record definisce la penna e i tratti per disegnare una spline cardinale chiusa. |
| EMF_PLUS_DRAW_CURVE | Questo record definisce i tratti della penna per disegnare una spline cardinale. |
| EMF_PLUS_DRAW_DRIVER_STRING | Questo record specifica l'output di testo con le posizioni dei caratteri. |
| EMF_PLUS_DRAW_ELLIPSE | Questo record definisce i tratti della penna per disegnare un'ellisse. |
| EMF_PLUS_DRAW_IMAGE | Questo record definisce un oggetto [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) scalato (sezione 2.2.1.4). Un'immagine può consistere sia di dati bitmap sia di dati metafile. |
| EMF_PLUS_DRAW_IMAGE_POINTS | Questo record definisce un oggetto EmfPlusImage scalato all'interno di un parallelogramma. Un'immagine può consistere sia di dati bitmap sia di dati metafile. |
| EMF_PLUS_DRAW_LINES | Questo record definisce i tratti della penna per disegnare una serie di linee collegate. |
| EMF_PLUS_DRAW_PATH | Il record definisce i tratti di penna per disegnare le figure in un percorso grafico. Un percorso è un oggetto che definisce una sequenza arbitraria di linee, curve e forme. |
| EMF_PLUS_DRAW_PIE | Questo record definisce i tratti di penna per disegnare una sezione di un'ellisse. |
| EMF_PLUS_DRAW_RECTS | Questo record definisce i tratti di penna per disegnare una serie di rettangoli. |
| EMF_PLUS_DRAW_STRING | Questo record definisce una stringa di testo basata su un carattere, un rettangolo di layout e un formato. |
| EMF_PLUS_END_CONTAINER | Questo record chiude un contenitore di stato grafico che era stato precedentemente aperto da un'operazione di inizio contenitore. |
| EMF_PLUS_END_OF_FILE | Questo record specifica la fine dei dati EMF+ nel metafile. |
| EMF_PLUS_FILL_CLOSED_CURVE | Questo record definisce come riempire l'interno di una spline cardinale chiusa usando un pennello specificato. |
| EMF_PLUS_FILL_ELLIPSE | Questo record definisce come riempire gli interni di un'ellisse, usando un pennello specificato. |
| EMF_PLUS_FILL_PATH | Il record definisce come riempire gli interni delle figure definite in un percorso grafico con un pennello specificato. Un percorso è un oggetto che definisce una sequenza arbitraria di linee, curve e forme. |
| EMF_PLUS_FILL_PIE | Questo record definisce come riempire una sezione di una parte interna di un'ellisse usando un pennello specificato. |
| EMF_PLUS_FILL_POLYGON | Questo record definisce i dati per riempire l'interno di un poligono, usando un pennello specificato. |
| EMF_PLUS_FILL_RECTS | Questo record definisce come riempire gli interni di una serie di rettangoli, usando un pennello specificato. |
| EMF_PLUS_FILL_REGION | Questo record definisce come riempire l'interno di una regione usando un pennello specificato. |
| EMF_PLUS_GET_DC | Questo record specifica che i successivi record EMF incontrati nel metafile DEVONO essere elaborati. I record EMF smettono di essere elaborati quando viene incontrato il successivo record EMF+. |
| EMF_PLUS_HEADER | Questo record specifica l'inizio dei dati EMF+ nel metafile. Deve essere incorporato nel primo record EMF dopo il record [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) ([MS-EMF] sezione 2.3.4.2 record). |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | Questo record moltiplica lo spazio mondiale corrente per una matrice di trasformazione specificata. |
| EMF_PLUS_MULTI_FORMAT_END | Questo record è riservato e NON DEVE essere utilizzato. |
| EMF_PLUS_MULTI_FORMAT_SECTION | Questo record è riservato e NON DEVE essere utilizzato. |
| EMF_PLUS_MULTI_FORMAT_START | Questo record è riservato e NON DEVE essere utilizzato. |
| EMF_PLUS_OBJECT | Questo record specifica un oggetto da utilizzare nelle operazioni grafiche. |
| EMF_PLUS_OFFSET_CLIP | Questo record applica una trasformazione di traslazione sulla regione di ritaglio corrente dello spazio mondiale. |
| EMF_PLUS_RESET_CLIP | Questo record ripristina la regione di ritaglio corrente per lo spazio mondiale all'infinito. |
| EMF_PLUS_RESET_WORLD_TRANSFORM | Questo record ripristina la trasformazione corrente dello spazio mondiale alla matrice identità. |
| EMF_PLUS_RESTORE | Questo record ripristina lo stato grafico, identificato da un indice specificato, da una pila di stati grafici salvati. Ogni indice della pila è associato a uno stato salvato particolare, e l'indice è definito da un record [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) (sezione 2.3.7.5) per salvare lo stato. |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | Questo record ruota lo spazio mondiale corrente di un angolo specificato. |
| EMF_PLUS_SAVE | Questo record salva lo stato grafico, identificato da un indice specificato, su una pila di stati grafici salvati. Ogni indice della pila è associato a uno stato salvato particolare, e l'indice è utilizzato da un record [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) (sezione 2.3.7.4) per ripristinare lo stato. |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | Questo record applica una trasformazione di scala allo spazio mondiale corrente mediante fattori di scala orizzontali e verticali specificati. |
| EMF_PLUS_SERIALIZABLE_OBJECT | Questo record definisce un blocco di parametri per effetti immagine che è stato serializzato in un buffer di dati. |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | Questo record definisce se abilitare o disabilitare l'anti-aliasing del testo. L'anti-aliasing del testo è un metodo per rendere le linee e i bordi dei glifi dei caratteri più lisci quando vengono disegnati su una superficie di output. |
| EMF_PLUS_SET_CLIP_PATH | Questo record combina la regione di ritaglio corrente con un percorso grafico. |
| EMF_PLUS_SET_CLIP_RECT | Questo record combina la regione di ritaglio corrente con un rettangolo. |
| EMF_PLUS_SET_CLIP_REGION | Questo record combina la regione di ritaglio corrente con un'altra regione grafica. |
| EMF_PLUS_SET_COMPOSITING_MODE | Questo record definisce la modalità di composizione in base allo stato della fusione alfa, che specifica come i colori di origine vengono combinati con i colori di sfondo. |
| EMF_PLUS_SET_COMPOSITING_QUALITY | Questo record definisce la qualità di composizione, che descrive il livello desiderato di qualità per creare immagini composite da più oggetti. |
| EMF_PLUS_SET_INTERPOLATION_MODE | Questo record definisce la modalità di interpolazione di un oggetto in base al tipo specificato di filtraggio dell'immagine. La modalità di interpolazione influenza come viene eseguita la scalatura (allungamento e riduzione). |
| EMF_PLUS_SET_PAGE_TRANSFORM | Questo record specifica fattori di scalatura aggiuntivi per la trasformazione dello spazio mondo corrente. |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | Questo record definisce la modalità di offset dei pixel in base al valore di centratura dei pixel specificato. |
| EMF_PLUS_SET_RENDERING_ORIGIN | Questo record definisce l'origine del rendering alle coordinate orizzontali e verticali specificate. Questo si applica ai pennelli a tratteggio e ai pattern di dithering a 8 e 16 bit per pixel. |
| EMF_PLUS_SET_TEXT_CONTRAST | Questo record imposta il contrasto del testo in base al valore gamma del testo specificato. |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | Questo record definisce il processo utilizzato per il rendering del testo. |
| EMF_PLUS_SET_TS_CLIP | Questo record specifica le aree di ritaglio nel contesto del dispositivo grafico per un server terminale. |
| EMF_PLUS_SET_TS_GRAPHICS | Questo record specifica lo stato del contesto del dispositivo grafico per un server terminale. |
| EMF_PLUS_SET_WORLD_TRANSFORM | Questo record definisce la trasformazione dello spazio mondiale corrente nel device_context di riproduzione, secondo una matrice di trasformazione specificata. |
| EMF_PLUS_STROKE_FILL_PATH | Questo record chiude eventuali figure aperte in un percorso, traccia il contorno del percorso usando la penna corrente e riempie il suo interno usando il pennello corrente. |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | Questo record applica una trasformazione di traslazione allo spazio mondiale corrente mediante distanze orizzontali e verticali specificate. |

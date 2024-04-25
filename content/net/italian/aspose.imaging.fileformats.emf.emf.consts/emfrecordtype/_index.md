---
title: EmfRecordType
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione RecordType definisce valori che identificano in modo univoco i record EMF. Questi valori sono forniti nel campo Tipo di ciascun record.
type: docs
weight: 2820
url: /it/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

L'enumerazione RecordType definisce valori che identificano in modo univoco i record EMF. Questi valori sono forniti nel campo Tipo di ciascun record.

```csharp
public enum EmfRecordType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| EMR_HEADER | `1` | Questo record definisce l'inizio del metafile e ne specifica le caratteristiche; il suo contenuto, comprese le dimensioni dell'immagine incorporata; il numero di record nel metafile; e la risoluzione del dispositivo su cui è stata creata l'immagine incorporata. Questi valori consentono al metafile di essere indipendente dal dispositivo. |
| EMR_POLYBEZIER | `2` | Questo record definisce una o più curve di Bezier. Le curve di Bezier cubiche vengono definite utilizzando i punti finali e i punti di controllo specificati e vengono tracciate con la penna corrente. |
| EMR_POLYGON | `3` | Questo record definisce un poligono costituito da due o più vertici collegati da linee rette . Il poligono viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente e la modalità riempimento poligono. Il poligono viene chiuso automaticamente tracciando una linea dall'ultimo vertice al primo. |
| EMR_POLYLINE | `4` | Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato. |
| EMR_POLYBEZIERTO | `5` | Questo record definisce una o più curve di Bezier in base alla posizione corrente. |
| EMR_POLYLINETO | `6` | Questo record definisce una o più linee rette in base alla posizione corrente. Viene tracciata una linea dalla posizione corrente al primo punto specificato dal campo dei punti utilizzando la penna corrente. Per ogni linea aggiuntiva, il disegno viene eseguito dal punto finale della linea precedente al punto successivo specificato da punti. |
| EMR_POLYPOLYLINE | `7` | Questo record definisce più serie di segmenti di linea collegati. I segmenti di linea vengono disegnati usando la penna corrente. Le figure formate dai segmenti non sono riempite. T La posizione attuale non è né utilizzata né aggiornata da questo record. |
| EMR_POLYPOLYGON | `8` | Questo record definisce una serie di poligoni chiusi. Ogni poligono viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente e la modalità di riempimento del poligono. I poligoni definiti da questo record possono sovrapporsi. |
| EMR_SETWINDOWEXTEX | `9` | Questo record definisce l'estensione della finestra. |
| EMR_SETWINDOWORGEX | `10` | Questo record definisce l'origine della finestra. |
| EMR_SETVIEWPORTEXTEX | `11` | Questo record definisce l'estensione della finestra. |
| EMR_SETVIEWPORTORGEX | `12` | Questo record definisce l'origine del viewport. |
| EMR_SETBRUSHORGEX | `13` | Questo record definisce l'origine del pennello corrente. |
| EMR_EOF | `14` | Questo record indica la fine del metafile. |
| EMR_SETPIXELV | `15` | Questo record definisce il colore del pixel alle coordinate logiche specificate. |
| EMR_SETMAPPERFLAGS | `16` | Questo record specifica i parametri del processo di corrispondenza dei caratteri logici con i caratteri fisici , che viene eseguito dal mappatore dei caratteri. |
| EMR_SETMAPMODE | `17` | Questo record definisce la modalità di mappatura del contesto del dispositivo di riproduzione. La modalità di mappatura definisce l'unità di misura utilizzata per trasformare le unità di spazio pagina in unità di spazio dispositivo, e definisce anche l'orientamento degli assi x e y del dispositivo. |
| EMR_SETBKMODE | `18` | Questo record definisce la modalità di missaggio in background del contesto del dispositivo di riproduzione. La modalità background mix viene utilizzata con testo, pennelli tratteggiati e stili di penna che non sono linee continue. |
| EMR_SETPOLYFILLMODE | `19` | Questo record definisce la modalità di riempimento del poligono. |
| EMR_SETROP2 | `20` | Questo record definisce la modalità operativa raster binaria. |
| EMR_SETSTRETCHBLTMODE | `21` | Questo record definisce la modalità di estensione bitmap. |
| EMR_SETTEXTALIGN | `22` | Questo record definisce l'allineamento del testo. |
| EMR_SETCOLORADJUSTMENT | `23` | Questo record definisce i valori di regolazione del colore per il contesto del dispositivo di riproduzione utilizzando i valori specificati. |
| EMR_SETTEXTCOLOR | `24` | Questo record definisce il colore del testo corrente. |
| EMR_SETBKCOLOR | `25` | Questo record definisce il colore di sfondo. |
| EMR_OFFSETCLIPRGN | `26` | Questo record ridefinisce l'area di ritaglio del contesto del dispositivo di riproduzione in base agli offset specificati. |
| EMR_MOVETOEX | `27` | Questo record definisce le coordinate della nuova posizione attuale, in unità logiche. |
| EMR_SETMETARGN | `28` | Questo record interseca la regione di ritaglio corrente per il contesto del dispositivo di riproduzione con la meta regione corrente e salva la regione combinata come nuova meta regione. L'area di ritaglio viene reimpostata su un'area nulla. |
| EMR_EXCLUDECLIPRECT | `29` | Questo record definisce una nuova area di ritaglio che consiste nell'area di ritaglio esistente meno il rettangolo specificato. |
| EMR_INTERSECTCLIPRECT | `30` | Questo record definisce una nuova regione di ritaglio dall'intersezione della regione di ritaglio corrente e il rettangolo specificato. |
| EMR_SCALEVIEWPORTEXTEX | `31` | Questo record ridefinisce il viewport per il contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicandi e dai divisori specificati. |
| EMR_SCALEWINDOWEXTEX | `32` | Questo record ridefinisce la finestra per il contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicandi e dai divisori specificati. |
| EMR_SAVEDC | `33` | Questo record salva lo stato corrente del contesto del dispositivo di riproduzione copiando i dati che descrivono gli oggetti selezionati e le modalità grafiche, inclusi bitmap, pennello, tavolozza, font , penna, area, modalità disegno e modalità mappatura, in una pila di contesti del dispositivo. |
| EMR_RESTOREDC | `34` | Questo record ripristina il contesto del dispositivo di riproduzione allo stato salvato specificato. Il contesto del dispositivo di riproduzione viene ripristinato eliminando le informazioni sullo stato da uno stack di contesti del dispositivo salvati creati da record EMR_SAVEDC (sezione 2.3.11) precedenti. |
| EMR_SETWORLDTRANSFORM | `35` | Questo record definisce una trasformazione lineare bidimensionale tra lo spazio del mondo e lo spazio della pagina (per ulteriori informazioni, vedere [MSDN-WRLDPGSPC]) per il contesto del dispositivo di riproduzione. Questa trasformazione può essere utilizzata per ridimensionare, ruotare, inclinare o tradurre l'output grafico. |
| EMR_MODIFYWORLDTRANSFORM | `36` | Questo record ridefinisce la trasformazione del mondo per il contesto del dispositivo di riproduzione utilizzando la modalità specificata. |
| EMR_SELECTOBJECT | `37` | Questo record aggiunge un oggetto al contesto del dispositivo di riproduzione, identificandolo tramite il suo indice nella tabella oggetti EMF (sezione 3.1.1.1). |
| EMR_CREATEPEN | `38` | Questo record definisce una penna logica con lo stile, la larghezza e il colore specificati. La penna può essere successivamente selezionata nel contesto del dispositivo di riproduzione e utilizzata per disegnare linee e curve. |
| EMR_CREATEBRUSHINDIRECT | `39` | Questo record definisce un pennello logico per il riempimento di figure nelle operazioni grafiche. |
| EMR_DELETEOBJECT | `40` | Questo record elimina un oggetto grafico, cancellandone l'indice nella tabella oggetti EMF. Se l'oggetto eliminato è selezionato nel contesto del dispositivo di riproduzione, l'oggetto predefinito per quella proprietà del contesto DEVE essere ripristinato. |
| EMR_ANGLEARC | `41` | Questo record definisce un segmento di linea di un arco. Il segmento di linea viene disegnato dalla posizione corrente all'inizio dell'arco. L'arco viene disegnato lungo il perimetro di un cerchio con raggio e centro dati. La lunghezza dell'arco è definita da gli angoli di inizio e di ampiezza indicati. |
| EMR_ELLIPSE | `42` | Questo record definisce un'ellisse. Il centro dell'ellisse è il centro del rettangolo di delimitazione specificato . L'ellisse viene delineata utilizzando la penna corrente e viene riempita utilizzando il pennello corrente. |
| EMR_RECTANGLE | `43` | Questo record definisce un rettangolo. Il rettangolo viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| EMR_ROUNDRECT | `44` | Questo record definisce un rettangolo con angoli arrotondati. Il rettangolo viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| EMR_ARC | `45` | Questo record definisce un arco ellittico. |
| EMR_CHORD | `46` | Questo record definisce una corda (una regione delimitata dall'intersezione di un'ellisse e un segmento di linea, chiamato secante). L'accordo viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| EMR_PIE | `47` | Questo record definisce un cuneo a forma di torta delimitato dall'intersezione di un'ellisse e due radiali. La torta viene delineata usando la penna corrente e riempita usando il pennello corrente. |
| EMR_SELECTPALETTE | `48` | Questo record aggiunge un oggetto LogPalette (sezione 2.2.17) al contesto del dispositivo di riproduzione , identificandolo tramite il suo indice nella tabella oggetti EMF. |
| EMR_CREATEPALETTE | `49` | Questo record definisce un oggetto LogPalette. |
| EMR_SETPALETTEENTRIES | `50` | Questo record definisce i valori di colore RGB (rosso-verde-blu) in un intervallo di voci in un oggetto LogPalette. |
| EMR_RESIZEPALETTE | `51` | Questo record aumenta o diminuisce la dimensione di una tavolozza logica. |
| EMR_REALIZEPALETTE | `52` | Questo record mappa le voci dalla tavolozza logica corrente alla tavolozza di sistema. |
| EMR_EXTFLOODFILL | `53` | Questo record riempie un'area della superficie di visualizzazione con il pennello corrente. |
| EMR_LINETO | `54` | Questo record definisce una linea dalla posizione corrente fino a, ma escluso, il punto specificato. Reimposta la posizione corrente al punto specificato. |
| EMR_ARCTO | `55` | Questo record definisce un arco ellittico. Reimposta la posizione corrente al punto finale dell'arco. |
| EMR_POLYDRAW | `56` | Questo record definisce un insieme di segmenti di linea e curve di Bezier. |
| EMR_SETARCDIRECTION | `57` | Questo record definisce la direzione del disegno da utilizzare per le operazioni su arco e rettangolo . |
| EMR_SETMITERLIMIT | `58` | Questo record definisce il limite per la lunghezza degli angoli di unione per il contesto del dispositivo di riproduzione . |
| EMR_BEGINPATH | `59` | Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione. |
| EMR_ENDPATH | `60` | Questo record chiude una parentesi di percorso e seleziona il percorso definito dalla parentesi nel contesto del dispositivo di riproduzione. |
| EMR_CLOSEFIGURE | `61` | Questo record chiude una figura aperta in un percorso. |
| EMR_FILLPATH | `62` | Questo record chiude tutte le figure aperte nel percorso corrente e riempie l'interno del percorso utilizzando il pennello corrente e la modalità di riempimento del poligono. |
| EMR_STROKEANDFILLPATH | `63` | Questo record chiude tutte le figure aperte in un tracciato, traccia il contorno del tracciato di usando la penna corrente e ne riempie l'interno usando il pennello corrente. |
| EMR_STROKEPATH | `64` | Questo record esegue il rendering del percorso specificato utilizzando la penna corrente. |
| EMR_FLATTENPATH | `65` | Questo record trasforma qualsiasi curva nel percorso selezionato nel contesto del dispositivo di riproduzione , trasformando ogni curva in una sequenza di linee. |
| EMR_WIDENPATH | `66` | Questo record ridefinisce il percorso corrente come l'area che verrebbe dipinta se il percorso fosse tracciato utilizzando la penna attualmente selezionata nel contesto del dispositivo di riproduzione. |
| EMR_SELECTCLIPPATH | `67` | Questo record definisce il percorso corrente come un'area di ritaglio per il contesto del dispositivo di riproduzione , combinando la nuova regione con qualsiasi area di ritaglio esistente utilizzando la modalità specificata. |
| EMR_ABORTPATH | `68` | Questo record interrompe una parentesi di percorso o elimina il percorso da una parentesi di percorso chiusa. |
| EMR_COMMENT | `70` | Questo record specifica dati privati arbitrari. |
| EMR_FILLRGN | `71` | Questo record riempie l'area specificata utilizzando il pennello specificato. |
| EMR_FRAMERGN | `72` | Questo record disegna un bordo attorno alla regione specificata utilizzando il pennello specificato. |
| EMR_INVERTRGN | `73` | Questo record inverte i colori nella regione specificata. |
| EMR_PAINTRGN | `74` | Questo record dipinge l'area specificata utilizzando il pennello attualmente selezionato in il contesto del dispositivo di riproduzione. |
| EMR_EXTSELECTCLIPRGN | `75` | Questo record combina la regione specificata con la regione di clip corrente utilizzando la modalità specificata . |
| EMR_BITBLT | `76` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , facoltativamente in combinazione con un motivo a pennello, in base a un'operazione raster specificata. |
| EMR_STRETCHBLT | `77` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un pattern di pennello, in base a un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| EMR_MASKBLT | `78` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un motivo a pennello e con l'applicazione di una bitmap di maschera di colore , in base alle operazioni raster di primo piano e sfondo specificate. |
| EMR_PLGBLT | `79` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un parallelogramma di destinazione, con l'applicazione di una bitmap di maschera di colore. |
| EMR_SETDIBITSTODEVICE | `80` | Questo record specifica un trasferimento a blocchi di pixel dalle linee di scansione specificate di una bitmap sorgente a un rettangolo di destinazione. |
| EMR_STRETCHDIBITS | `81` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un pattern di pennello, in base a un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario . |
| EMR_EXTCREATEFONTINDIRECTW | `82` | Questo record definisce un font logico che ha le caratteristiche specificate. Il carattere può essere successivamente selezionato come carattere corrente per il contesto del dispositivo di riproduzione. |
| EMR_EXTTEXTOUTA | `83` | Questo record disegna una stringa di testo ASCII utilizzando il font e i colori del testo correnti. Nota EMR_EXTTEXTOUTA DOVREBBE essere emulato con un record EMR_EXTTEXTOUTW (sezione 2.3.5.8). Ciò richiede che la stringa di testo ASCII nell'oggetto EmrText sia convertita nella codifica Unicode UTF16-LE. |
| EMR_EXTTEXTOUTW | `84` | Questo record disegna una stringa di testo Unicode utilizzando il carattere e i colori del testo correnti. |
| EMR_POLYBEZIER16 | `85` | Questo record definisce una o più curve di Bezier. Le curve sono disegnate usando la penna corrente. |
| EMR_POLYGON16 | `86` | Questo record definisce un poligono costituito da due o più vertici collegati da linee rette. Il poligono viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente e la modalità di riempimento poligono . Il poligono viene chiuso automaticamente tracciando una linea dall'ultimo vertice al primo. |
| EMR_POLYLINE16 | `87` | Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato. |
| EMR_POLYBEZIERTO16 | `88` | Questo record definisce una o più curve di Bezier in base alla posizione corrente. |
| EMR_POLYLINETO16 | `89` | Questo record definisce una o più linee rette in base alla posizione corrente. Viene tracciata una linea dalla posizione corrente al primo punto specificato dal campo Punti utilizzando la penna corrente. Per ogni linea aggiuntiva, il disegno viene eseguito dal punto finale della linea precedente al punto successivo specificato da Points. |
| EMR_POLYPOLYLINE16 | `90` | Questo record definisce più serie di segmenti di linea collegati. |
| EMR_POLYPOLYGON16 | `91` | Questo record definisce una serie di poligoni chiusi. Ogni poligono viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente e la modalità di riempimento del poligono. I poligoni specificati da questo record possono sovrapporsi. |
| EMR_POLYDRAW16 | `92` | Questo record definisce un insieme di segmenti di linea e curve di Bezier. |
| EMR_CREATEMONOBRUSH | `93` | Questo record definisce un pennello logico con il modello bitmap specificato. La bitmap può essere una bitmap di sezione DIB (Device-Independent Bitmap) oppure può essere una bitmap dipendente dal dispositivo. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | Questo record definisce un pennello logico che ha il modello specificato dal DIB. |
| EMR_EXTCREATEPEN | `95` | Questo record definisce una penna cosmetica o geometrica logica che ha lo stile, la larghezza e gli attributi del pennello specificati. |
| EMR_POLYTEXTOUTA | `96` | Questo record disegna una o più stringhe di testo ASCII utilizzando il font e i colori del testo correnti. Nota EMR_POLYTEXTOUTA DOVREBBE essere emulato con una serie di record EMR_EXTTEXTOUTW, uno per stringa |
| EMR_POLYTEXTOUTW | `97` | Questo record disegna una o più stringhe di testo Unicode utilizzando il font e i colori del testo correnti. Nota EMR_POLYTEXTOUTW DOVREBBE essere emulato con una serie di record EMR_EXTTEXTOUTW, uno per stringa |
| EMR_SETICMMODE | `98` | Questo record specifica la modalità di gestione del colore dell'immagine (ICM) per le operazioni grafiche. |
| EMR_CREATECOLORSPACE | `99` | Questo record crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri ASCII |
| EMR_SETCOLORSPACE | `100` | Questo record definisce l'oggetto spazio colore logico corrente per le operazioni grafiche. |
| EMR_DELETECOLORSPACE | `101` | Questo record elimina un oggetto logico dello spazio colore. Nota Un record EMR_DELETEOBJECT DOVREBBE essere utilizzato invece di EMR_DELETECOLORSPACE per eliminare uno spazio colore logico object |
| EMR_GLSRECORD | `102` | Questo record specifica una funzione OpenGL. |
| EMR_GLSBOUNDEDRECORD | `103` | Questo record specifica una funzione OpenGL con un rettangolo di delimitazione per l'output. |
| EMR_PIXELFORMAT | `104` | Questo record specifica il formato pixel da utilizzare per le operazioni grafiche |
| EMR_DRAWESCAPE | `105` | Questo record trasmette informazioni arbitrarie al conducente. L'intento è che l'informazione comporterà l'esecuzione del disegno. |
| EMR_EXTESCAPE | `106` | Questo record trasmette informazioni arbitrarie al conducente. L'intento è che le informazioni non comporteranno l'esecuzione del disegno. |
| EMR_SMALLTEXTOUT | `108` | Questo record genera una stringa. |
| EMR_FORCEUFIMAPPING | `109` | Questo record forza il mappatore dei caratteri a far corrispondere i caratteri in base al loro UniversalFontId nella preferenza alle loro informazioni LogFont. |
| EMR_NAMEDESCAPE | `110` | Questo record passa informazioni arbitrarie al driver denominato specificato. |
| EMR_COLORCORRECTPALETTE | `111` | Questo record specifica come correggere le voci di un oggetto tavolozza logica utilizzando Windows Color System (WCS) 1.0 values |
| EMR_SETICMPROFILEA | `112` | Questo record specifica un profilo colore in un file con un nome composto da caratteri ASCII, per l'output grafico. |
| EMR_SETICMPROFILEW | `113` | Questo record specifica un profilo colore in un file con un nome composto da caratteri Unicode, per output grafico |
| EMR_ALPHABLEND | `114` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione, inclusi i dati di trasparenza alfa, in base a un'operazione di fusione specificata. |
| EMR_SETLAYOUT | `115` | Questo record specifica l'ordine in cui vengono disegnati testo e grafica |
| EMR_TRANSPARENTBLT | `116` | Questo record specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione, trattando un colore specificato come trasparente, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario |
| EMR_GRADIENTFILL | `118` | Questo record specifica il riempimento di rettangoli o triangoli con sfumature di colore |
| EMR_SETLINKEDUFIS | `119` | Questo record imposta gli UniversalFontIds dei caratteri collegati da utilizzare durante la ricerca dei caratteri. |
| EMR_SETTEXTJUSTIFICATION | `120` | Questo record specifica la quantità di spazio extra da aggiungere ai caratteri di interruzione ai fini della giustificazione . |
| EMR_COLORMATCHTOTARGETW | `121` | Questo record specifica se eseguire la corrispondenza dei colori con un profilo colore specificato in un file con un nome composto da caratteri Unicode. |
| EMR_CREATECOLORSPACEW | `122` | Questo record crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri Unicode |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->

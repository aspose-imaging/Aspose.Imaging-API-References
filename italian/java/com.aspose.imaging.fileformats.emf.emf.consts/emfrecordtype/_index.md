---
title: "EmfRecordType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione RecordType definisce i valori che identificano in modo univoco i record EMF."
type: docs
weight: 38
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

L'enumerazione RecordType definisce valori che identificano in modo univoco i record EMF. Questi valori sono forniti nel campo Type di ciascun record.
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | Questo record definisce l'inizio del metafile e specifica le sue caratteristiche; il suo contenuto, incluse le dimensioni dell'immagine incorporata; il numero di record nel metafile; e la risoluzione del dispositivo su cui è stata creata l'immagine incorporata. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | Questo record definisce una o più curve di Bézier. |
| [EMR_POLYGON](#EMR-POLYGON) | Questo record definisce un poligono composto da due o più vertici collegati da linee rette. |
| [EMR_POLYLINE](#EMR-POLYLINE) | Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | Questo record definisce una o più curve di Bézier basate sulla posizione corrente. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | Questo record definisce una o più linee rette basate sulla posizione corrente. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | Questo record definisce più serie di segmenti di linea collegati. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | Questo record definisce una serie di poligoni chiusi. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | Questo record definisce l'estensione della finestra. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | Questo record definisce l'origine della finestra. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | Questo record definisce l'estensione del viewport. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | Questo record definisce l'origine del viewport. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | Questo record definisce l'origine del pennello corrente. |
| [EMR_EOF](#EMR-EOF) | Questo record indica la fine del metafile. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | Questo record definisce il colore del pixel alle coordinate logiche specificate. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | Questo record specifica i parametri del processo di associazione dei font logici a quelli fisici, eseguito dal mapper dei font. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | Questo record definisce la modalità di mappatura del contesto del dispositivo di riproduzione. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | Questo record definisce la modalità di miscelazione dello sfondo del contesto del dispositivo di riproduzione. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | Questo record definisce la modalità di riempimento del poligono. |
| [EMR_SETROP2](#EMR-SETROP2) | Questo record definisce la modalità di operazione raster binaria. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | Questo record definisce la modalità di stretching del bitmap. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | Questo record definisce l'allineamento del testo. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | Questo record definisce i valori di regolazione del colore per il contesto del dispositivo di riproduzione utilizzando i valori specificati. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | Questo record definisce il colore corrente del testo. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | Questo record definisce il colore di sfondo. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | Questo record ridefinisce la regione di ritaglio del contesto del dispositivo di riproduzione mediante gli offset specificati. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | Questo record definisce le coordinate della nuova posizione corrente, in unità logiche. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | Questo record interseca la regione di ritaglio corrente per il contesto del dispositivo di riproduzione con la meta regione corrente e salva la regione combinata come nuova meta regione. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | Questo record definisce una nuova regione di ritaglio composta dalla regione di ritaglio esistente meno il rettangolo specificato. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | Questo record definisce una nuova regione di ritaglio dall'intersezione della regione di ritaglio corrente e del rettangolo specificato. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | Questo record ridefinisce la viewport per il contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicatori e divisori specificati. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | Questo record ridefinisce la finestra per il contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicatori e divisori specificati. |
| [EMR_SAVEDC](#EMR-SAVEDC) | Questo record salva lo stato corrente del contesto del dispositivo di riproduzione copiando i dati che descrivono gli oggetti selezionati e le modalità grafiche\\u2014inclusi il bitmap, il pennello, la tavolozza, il carattere, la penna, la regione, la modalità di disegno e la modalità di mappatura\\u2014in una pila di contesti di dispositivo salvati. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | Questo record ripristina il contesto del dispositivo di riproduzione allo stato salvato specificato. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | Questo record definisce una trasformazione lineare bidimensionale tra lo spazio mondo e lo spazio pagina (per maggiori informazioni, vedere [MSDN-WRLDPGSPC]) per il contesto del dispositivo di riproduzione. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | Questo record ridefinisce la trasformazione del mondo per il contesto del dispositivo di riproduzione utilizzando la modalità specificata. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | Questo record aggiunge un oggetto al contesto del dispositivo di riproduzione, identificandolo per il suo indice nella EMF Object Table (sezione 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | Questo record definisce una penna logica che ha lo stile, la larghezza e il colore specificati. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | Questo record definisce un pennello logico per il riempimento delle figure nelle operazioni grafiche. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | Questo record elimina un oggetto grafico, cancellando il suo indice nella EMF Object Table. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | Questo record definisce un segmento di linea di un arco. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | Questo record definisce un'ellisse. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | Questo record definisce un rettangolo. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | Questo record definisce un rettangolo con angoli arrotondati. |
| [EMR_ARC](#EMR-ARC) | Questo record definisce un arco ellittico. |
| [EMR_CHORD](#EMR-CHORD) | Questo record definisce una corda (una regione delimitata dall'intersezione di un'ellisse e di un segmento di linea, chiamata secante). |
| [EMR_PIE](#EMR-PIE) | Questo record definisce una sezione a forma di torta delimitata dall'intersezione di un'ellisse e due raggi. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | Questo record aggiunge un oggetto LogPalette (sezione 2.2.17) al contesto del dispositivo di riproduzione, identificandolo per il suo indice nella Tabella degli Oggetti EMF. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | Questo record definisce un oggetto LogPalette. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | Questo record definisce i valori di colore RGB (rosso-verde-blu) in un intervallo di voci in un oggetto LogPalette. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | Questo record aumenta o diminuisce la dimensione di una palette logica. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | Questo record mappa le voci dalla palette logica corrente alla palette di sistema. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | Questo record riempie un'area della superficie di visualizzazione con il pennello corrente. |
| [EMR_LINETO](#EMR-LINETO) | Questo record definisce una linea dalla posizione corrente fino, ma non includendo, il punto specificato. |
| [EMR_ARCTO](#EMR-ARCTO) | Questo record definisce un arco ellittico. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | Questo record definisce un insieme di segmenti di linea e curve di Bézier. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | Questo record definisce la direzione di disegno da utilizzare per le operazioni di arco e rettangolo. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | Questo record definisce il limite per la lunghezza delle giunzioni a spigolo per il contesto del dispositivo di riproduzione. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione. |
| [EMR_ENDPATH](#EMR-ENDPATH) | Questo record chiude una parentesi di percorso e seleziona il percorso definito dalla parentesi nel contesto del dispositivo di riproduzione. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | Questo record chiude una figura aperta in un percorso. |
| [EMR_FILLPATH](#EMR-FILLPATH) | Questo record chiude tutte le figure aperte nel percorso corrente e riempie l'interno del percorso utilizzando il pennello corrente e la modalità di riempimento dei poligoni. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | Questo record chiude tutte le figure aperte in un percorso, traccia il contorno del percorso usando la penna corrente e riempie il suo interno usando il pennello corrente. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | Questo record rende il percorso specificato usando la penna corrente. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | Questo record trasforma qualsiasi curva nel percorso selezionata nel contesto del dispositivo di riproduzione, convertendo ogni curva in una sequenza di linee. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | Questo record ridefinisce il percorso corrente come l'area che verrebbe dipinta se il percorso fosse tracciato usando la penna attualmente selezionata nel contesto del dispositivo di riproduzione. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | Questo record definisce il percorso corrente come una regione di ritaglio per il contesto del dispositivo di riproduzione, combinando la nuova regione con qualsiasi regione di ritaglio esistente usando la modalità specificata. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | Questo record annulla una parentesi di percorso o scarta il percorso da una parentesi di percorso chiusa. |
| [EMR_COMMENT](#EMR-COMMENT) | Questo record specifica dati privati arbitrari. |
| [EMR_FILLRGN](#EMR-FILLRGN) | Questo record riempie la regione specificata usando il pennello specificato. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | Questo record disegna un bordo attorno alla regione specificata usando il pennello specificato. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | Questo record inverte i colori nella regione specificata. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | Questo record dipinge la regione specificata usando il pennello attualmente selezionato nel contesto del dispositivo di riproduzione. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | Questo record combina la regione specificata con la regione di ritaglio corrente usando la modalità specificata. |
| [EMR_BITBLT](#EMR-BITBLT) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| [EMR_MASKBLT](#EMR-MASKBLT) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello e con l'applicazione di un bitmap di maschera colore, secondo le operazioni raster specificate per il primo piano e lo sfondo. |
| [EMR_PLGBLT](#EMR-PLGBLT) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un parallelogramma di destinazione, con l'applicazione di un bitmap di maschera colore. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | Questo record specifica un trasferimento a blocchi di pixel da linee di scansione specificate di un bitmap sorgente a un rettangolo di destinazione. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | Questo record definisce un carattere logico che possiede le caratteristiche specificate. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | Questo record disegna una stringa di testo ASCII usando il carattere corrente e i colori del testo. Nota EMR\_EXTTEXTOUTA DEVE essere emulato con un record EMR\_EXTTEXTOUTW (sezione 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | Questo record disegna una stringa di testo Unicode usando il carattere corrente e i colori del testo. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | Questo record definisce una o più curve di Bézier. |
| [EMR_POLYGON16](#EMR-POLYGON16) | Questo record definisce un poligono composto da due o più vertici collegati da linee rette. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | Questo record definisce una o più curve di Bézier basate sulla posizione corrente. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | Questo record definisce una o più linee rette basate sulla posizione corrente. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | Questo record definisce più serie di segmenti di linea collegati. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | Questo record definisce una serie di poligoni chiusi. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | Questo record definisce un insieme di segmenti di linea e curve di Bézier. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | Questo record definisce un pennello logico con il modello bitmap specificato. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | Questo record definisce un pennello logico che ha il modello specificato dal DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | Questo record definisce una penna cosmetica o geometrica logica che ha lo stile, la larghezza e gli attributi del pennello specificati. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | Questo record disegna una o più stringhe di testo ASCII usando il carattere corrente e i colori del testo. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | Questo record disegna una o più stringhe di testo Unicode usando il carattere corrente e i colori del testo. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | Questo record specifica la modalità di Image Color Management (ICM) per le operazioni grafiche. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | Questo record crea un oggetto di spazio colore logico da un profilo colore con un nome composto da caratteri ASCII |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | Questo record definisce l'oggetto di spazio colore logico corrente per le operazioni grafiche. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | Questo record elimina un oggetto di spazio colore logico. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | Questo record specifica una funzione OpenGL. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | Questo record specifica una funzione OpenGL con un rettangolo di delimitazione per l'output. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | Questo record specifica il formato pixel da utilizzare per le operazioni grafiche |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | Questo record passa informazioni arbitrarie al driver. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | Questo record passa informazioni arbitrarie al driver. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | Questo record emette una stringa. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | Questo record forza il mapper dei caratteri a corrispondere i font in base al loro UniversalFontId preferendo le informazioni LogFont. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | Questo record passa informazioni arbitrarie al driver nominato specificato. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | Questo record specifica come correggere le voci di un oggetto palette logica utilizzando i valori di Windows Color System (WCS) 1.0 |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | Questo record specifica un profilo colore in un file con un nome composto da caratteri ASCII, per l'output grafico. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | Questo record specifica un profilo colore in un file con un nome composto da caratteri Unicode, per l'output grafico |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, includendo dati di trasparenza alfa, secondo un'operazione di fusione specificata. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | Questo record specifica l'ordine in cui testo e grafica vengono disegnati |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, trattando un colore specificato come trasparente, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | Questo record specifica il riempimento di rettangoli o triangoli con gradienti di colore |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | Questo record imposta gli UniversalFontIds dei font collegati da utilizzare durante la ricerca dei caratteri. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | Questo record specifica la quantità di spazio extra da aggiungere ai caratteri di interruzione per scopi di giustificazione. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | Questo record specifica se eseguire l'abbinamento colore con un profilo colore specificato in un file con un nome composto da caratteri Unicode. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | Questo record crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri Unicode |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


Questo record definisce l'inizio del metafile e ne specifica le caratteristiche; il suo contenuto, incluse le dimensioni dell'immagine incorporata; il numero di record nel metafile; e la risoluzione del dispositivo su cui l'immagine incorporata è stata creata. Questi valori rendono possibile che il metafile sia indipendente dal dispositivo.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


Questo record definisce una o più curve di Bézier. Le curve di Bézier cubiche sono definite usando punti finali e punti di controllo specificati, e sono tracciate con la penna corrente.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


Questo record definisce un poligono composto da due o più vertici collegati da linee rette. Il poligono è contornato usando la penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono. Il poligono è chiuso automaticamente disegnando una linea dal ultimo vertice al primo.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


Questo record definisce una o più curve di Bézier basate sulla posizione corrente.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


Questo record definisce una o più linee rette basate sulla posizione corrente. Una linea è disegnata dalla posizione corrente al primo punto specificato dal campo points usando la penna corrente. Per ogni linea aggiuntiva, il disegno viene eseguito dal punto finale della linea precedente al punto successivo specificato da points.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


Questo record definisce più serie di segmenti di linea collegati. I segmenti di linea sono disegnati usando la penna corrente. Le figure formate dai segmenti non sono riempite. La posizione corrente non è né usata né aggiornata da questo record.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


Questo record definisce una serie di poligoni chiusi. Ogni poligono è contornato usando la penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono. I poligoni definiti da questo record possono sovrapporsi.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


Questo record definisce l'estensione della finestra.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


Questo record definisce l'origine della finestra.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


Questo record definisce l'estensione del viewport.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


Questo record definisce l'origine del viewport.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


Questo record definisce l'origine del pennello corrente.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


Questo record indica la fine del metafile.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


Questo record definisce il colore del pixel alle coordinate logiche specificate.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


Questo record specifica i parametri del processo di associazione dei font logici a quelli fisici, eseguito dal mapper dei font.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


Questo record definisce la modalità di mappatura del contesto dispositivo di riproduzione. La modalità di mappatura definisce l'unità di misura usata per trasformare le unità dello spazio pagina in unità dello spazio dispositivo, e definisce anche l'orientamento dell'asse x e y del dispositivo.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


Questo record definisce la modalità di miscelazione dello sfondo del contesto dispositivo di riproduzione. La modalità di miscelazione dello sfondo è usata con testo, pennelli tratteggiati e stili di penna che non sono linee solide.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


Questo record definisce la modalità di riempimento del poligono.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


Questo record definisce la modalità di operazione raster binaria.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


Questo record definisce la modalità di stretching del bitmap.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


Questo record definisce l'allineamento del testo.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


Questo record definisce i valori di regolazione del colore per il contesto del dispositivo di riproduzione utilizzando i valori specificati.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


Questo record definisce il colore corrente del testo.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


Questo record definisce il colore di sfondo.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


Questo record ridefinisce la regione di ritaglio del contesto del dispositivo di riproduzione mediante gli offset specificati.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


Questo record definisce le coordinate della nuova posizione corrente, in unità logiche.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


Questo record interseca la regione di ritaglio corrente per il contesto dispositivo di riproduzione con la regione meta corrente e salva la regione combinata come nuova regione meta. La regione di ritaglio viene reimpostata a una regione nulla.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


Questo record definisce una nuova regione di ritaglio composta dalla regione di ritaglio esistente meno il rettangolo specificato.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


Questo record definisce una nuova regione di ritaglio dall'intersezione della regione di ritaglio corrente e del rettangolo specificato.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


Questo record ridefinisce la viewport per il contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicatori e divisori specificati.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


Questo record ridefinisce la finestra per il contesto del dispositivo di riproduzione utilizzando i rapporti formati dai moltiplicatori e divisori specificati.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


Questo record salva lo stato corrente del contesto del dispositivo di riproduzione copiando i dati che descrivono gli oggetti selezionati e le modalità grafiche\\u2014inclusi il bitmap, il pennello, la tavolozza, il carattere, la penna, la regione, la modalità di disegno e la modalità di mappatura\\u2014in una pila di contesti di dispositivo salvati.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


Questo record ripristina il contesto dispositivo di riproduzione allo stato salvato specificato. Il contesto dispositivo di riproduzione è ripristinato rimuovendo le informazioni di stato da una pila di contesti dispositivo salvati creata da record EMR\_SAVEDC precedenti (sezione 2.3.11).

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


Questo record definisce una trasformazione lineare bidimensionale tra lo spazio mondo e lo spazio pagina (per ulteriori informazioni, vedere [MSDN-WRLDPGSPC]) per il contesto dispositivo di riproduzione. Questa trasformazione può essere usata per scalare, ruotare, inclinare o traslare l'output grafico.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


Questo record ridefinisce la trasformazione del mondo per il contesto del dispositivo di riproduzione utilizzando la modalità specificata.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


Questo record aggiunge un oggetto al contesto del dispositivo di riproduzione, identificandolo per il suo indice nella EMF Object Table (sezione 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


Questo record definisce una penna logica con lo stile, la larghezza e il colore specificati. La penna può successivamente essere selezionata nel contesto dispositivo di riproduzione e usata per disegnare linee e curve.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


Questo record definisce un pennello logico per il riempimento delle figure nelle operazioni grafiche.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


Questo record elimina un oggetto grafico, cancellando il suo indice nella EMF Object Table. Se l'oggetto eliminato è selezionato nel contesto dispositivo di riproduzione, l'oggetto predefinito per quella proprietà del contesto DEVE essere ripristinato.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


Questo record definisce un segmento di linea di un arco. Il segmento di linea è disegnato dalla posizione corrente all'inizio dell'arco. L'arco è disegnato lungo il perimetro di un cerchio con il raggio e il centro dati. La lunghezza dell'arco è definita dagli angoli di inizio e di sweep forniti.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


Questo record definisce un'ellisse. Il centro dell'ellisse è il centro del rettangolo di delimitazione specificato. L'ellisse è contornata usando la penna corrente e riempita usando il pennello corrente.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


Questo record definisce un rettangolo. Il rettangolo è contornato usando la penna corrente e riempito usando il pennello corrente.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


Questo record definisce un rettangolo con angoli arrotondati. Il rettangolo è contornato usando la penna corrente e riempito usando il pennello corrente.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


Questo record definisce un arco ellittico.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


Questo record definisce una corda (una regione delimitata dall'intersezione di un'ellisse e di un segmento di linea, chiamata secante). La corda è contornata usando la penna corrente e riempita usando il pennello corrente.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


Questo record definisce una fetta a forma di torta delimitata dall'intersezione di un'ellisse e due raggi. La fetta è contornata usando la penna corrente e riempita usando il pennello corrente.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


Questo record aggiunge un oggetto LogPalette (sezione 2.2.17) al contesto del dispositivo di riproduzione, identificandolo per il suo indice nella Tabella degli Oggetti EMF.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


Questo record definisce un oggetto LogPalette.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


Questo record definisce i valori di colore RGB (rosso-verde-blu) in un intervallo di voci in un oggetto LogPalette.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


Questo record aumenta o diminuisce la dimensione di una palette logica.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


Questo record mappa le voci dalla palette logica corrente alla palette di sistema.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


Questo record riempie un'area della superficie di visualizzazione con il pennello corrente.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


Questo record definisce una linea dalla posizione corrente fino, ma non includendo, il punto specificato. Reimposta la posizione corrente al punto specificato.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


Questo record definisce un arco ellittico. Reimposta la posizione corrente al punto finale dell'arco.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


Questo record definisce un insieme di segmenti di linea e curve di Bézier.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


Questo record definisce la direzione di disegno da utilizzare per le operazioni di arco e rettangolo.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


Questo record definisce il limite per la lunghezza delle giunzioni a spigolo per il contesto del dispositivo di riproduzione.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione.

--------------------

Dopo che una parentesi di percorso è aperta, un'applicazione può iniziare a elaborare i record per definire i punti che si trovano nel percorso. Un'applicazione DEVE chiudere una parentesi di percorso aperta elaborando il record EMR\_ENDPATH. Quando un'applicazione elabora il record EMR\_BEGINPATH, tutti i percorsi precedenti DEVONO essere scartati dal contesto del dispositivo di riproduzione.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


Questo record chiude una parentesi di percorso e seleziona il percorso definito dalla parentesi nel contesto del dispositivo di riproduzione.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


Questo record chiude una figura aperta in un percorso.

--------------------

Elaborare il record EMR\_CLOSEFIGURE DEVE chiudere la figura disegnando una linea dalla posizione corrente al primo punto della figura, e poi DEVE collegare le linee usando lo stile di giunzione delle linee. Se una figura è chiusa elaborando il record EMR\_LINETO invece del record EMR\_CLOSEFIGURE, le estremità sono usate per creare l'angolo invece di una giunzione. EMR\_LINETO è specificato nella sezione 2.3.5.13. Il record EMR\_CLOSEFIGURE DOVREBBE essere usato solo se c'è una parentesi di percorso aperta nel contesto del dispositivo di riproduzione. Una figura in un percorso è aperta a meno che non sia esplicitamente chiusa elaborando questo record. Nota: Una figura può essere aperta anche se il punto corrente e il punto di partenza della figura sono gli stessi. Dopo aver elaborato il record EMR\_CLOSEFIGURE, aggiungere una linea o una curva al percorso DEVE avviare una nuova figura.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


Questo record chiude tutte le figure aperte nel percorso corrente e riempie l'interno del percorso utilizzando il pennello corrente e la modalità di riempimento dei poligoni.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


Questo record chiude tutte le figure aperte in un percorso, traccia il contorno del percorso usando la penna corrente e riempie il suo interno usando il pennello corrente.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


Questo record rende il percorso specificato usando la penna corrente.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


Questo record trasforma qualsiasi curva nel percorso selezionata nel contesto del dispositivo di riproduzione, convertendo ogni curva in una sequenza di linee.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


Questo record ridefinisce il percorso corrente come l'area che verrebbe dipinta se il percorso fosse tracciato usando la penna attualmente selezionata nel contesto del dispositivo di riproduzione.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


Questo record definisce il percorso corrente come una regione di ritaglio per il contesto del dispositivo di riproduzione, combinando la nuova regione con qualsiasi regione di ritaglio esistente usando la modalità specificata.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


Questo record annulla una parentesi di percorso o scarta il percorso da una parentesi di percorso chiusa.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


Questo record specifica dati privati arbitrari.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


Questo record riempie la regione specificata usando il pennello specificato.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


Questo record disegna un bordo attorno alla regione specificata usando il pennello specificato.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


Questo record inverte i colori nella regione specificata.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


Questo record dipinge la regione specificata usando il pennello attualmente selezionato nel contesto del dispositivo di riproduzione.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


Questo record combina la regione specificata con la regione di ritaglio corrente usando la modalità specificata.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello e con l'applicazione di un bitmap di maschera colore, secondo le operazioni raster specificate per il primo piano e lo sfondo.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un parallelogramma di destinazione, con l'applicazione di un bitmap di maschera colore.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


Questo record specifica un trasferimento a blocchi di pixel da linee di scansione specificate di un bitmap sorgente a un rettangolo di destinazione.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


Questo record definisce un font logico che ha le caratteristiche specificate. Il font può successivamente essere selezionato come font corrente per il contesto del dispositivo di riproduzione.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


Questo record disegna una stringa di testo ASCII usando il font corrente e i colori del testo. Nota EMR\_EXTTEXTOUTA DOVREBBE essere emulato con un record EMR\_EXTTEXTOUTW (sezione 2.3.5.8). Ciò richiede che la stringa di testo ASCII nell'oggetto EmrText sia convertita nella codifica Unicode UTF16-LE.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


Questo record disegna una stringa di testo Unicode usando il carattere corrente e i colori del testo.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


Questo record definisce una o più curve di Bézier. Le curve sono disegnate usando la penna corrente.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


Questo record definisce un poligono composto da due o più vertici collegati da linee rette. Il poligono è contornato usando la penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono. Il poligono è chiuso automaticamente disegnando una linea dal ultimo vertice al primo.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


Questo record definisce una o più curve di Bézier basate sulla posizione corrente.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


Questo record definisce una o più linee rette basate sulla posizione corrente. Una linea è disegnata dalla posizione corrente al primo punto specificato dal campo Points usando la penna corrente. Per ogni linea aggiuntiva, il disegno è eseguito dal punto finale della linea precedente al punto successivo specificato da Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


Questo record definisce più serie di segmenti di linea collegati.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


Questo record definisce una serie di poligoni chiusi. Ogni poligono è contornato usando la penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono. I poligoni specificati da questo record possono sovrapporsi.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


Questo record definisce un insieme di segmenti di linea e curve di Bézier.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


Questo record definisce un pennello logico con il motivo bitmap specificato. Il bitmap può essere una sezione bitmap device-independent (DIB) o può essere un bitmap device-dependent.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


Questo record definisce un pennello logico che ha il modello specificato dal DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


Questo record definisce una penna cosmetica o geometrica logica che ha lo stile, la larghezza e gli attributi del pennello specificati.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


Questo record disegna una o più stringhe di testo ASCII usando il font corrente e i colori del testo. Nota EMR\_POLYTEXTOUTA DOVREBBE essere emulato con una serie di record EMR\_EXTTEXTOUTW, uno per stringa

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


Questo record disegna una o più stringhe di testo Unicode usando il font corrente e i colori del testo. Nota EMR\_POLYTEXTOUTW DOVREBBE essere emulato con una serie di record EMR\_EXTTEXTOUTW, uno per stringa

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


Questo record specifica la modalità di Image Color Management (ICM) per le operazioni grafiche.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


Questo record crea un oggetto di spazio colore logico da un profilo colore con un nome composto da caratteri ASCII

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


Questo record definisce l'oggetto di spazio colore logico corrente per le operazioni grafiche.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


Questo record elimina un oggetto spazio colore logico. Nota Un record EMR\_DELETEOBJECT DOVREBBE essere usato invece di EMR\_DELETECOLORSPACE per eliminare un oggetto spazio colore logico

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


Questo record specifica una funzione OpenGL.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


Questo record specifica una funzione OpenGL con un rettangolo di delimitazione per l'output.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


Questo record specifica il formato pixel da utilizzare per le operazioni grafiche

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


Questo record passa informazioni arbitrarie al driver. L'intento è che le informazioni risultino in un disegno eseguito.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


Questo record passa informazioni arbitrarie al driver. L'intento è che le informazioni non risultino in un disegno eseguito.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


Questo record emette una stringa.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


Questo record forza il mapper dei caratteri a corrispondere i font in base al loro UniversalFontId preferendo le informazioni LogFont.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


Questo record passa informazioni arbitrarie al driver nominato specificato.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


Questo record specifica come correggere le voci di un oggetto palette logica utilizzando i valori di Windows Color System (WCS) 1.0

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


Questo record specifica un profilo colore in un file con un nome composto da caratteri ASCII, per l'output grafico.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


Questo record specifica un profilo colore in un file con un nome composto da caratteri Unicode, per l'output grafico

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, includendo dati di trasparenza alfa, secondo un'operazione di fusione specificata.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


Questo record specifica l'ordine in cui testo e grafica vengono disegnati

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione, trattando un colore specificato come trasparente, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


Questo record specifica il riempimento di rettangoli o triangoli con gradienti di colore

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


Questo record imposta gli UniversalFontIds dei font collegati da utilizzare durante la ricerca dei caratteri.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


Questo record specifica la quantità di spazio extra da aggiungere ai caratteri di interruzione per scopi di giustificazione.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


Questo record specifica se eseguire l'abbinamento colore con un profilo colore specificato in un file con un nome composto da caratteri Unicode.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


Questo record crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri Unicode


---
title: "Enumerazione EmfRecordType"
type: docs
weight: 290
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

L'enumerazione RecordType definisce i valori che identificano in modo univoco i record EMF.<br/>            Questi valori sono forniti nel campo Type di ciascun record.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| EMR_ABORTPATH | Questo record annulla una parentesi di percorso o scarta il percorso da una parentesi di percorso chiusa. |
| EMR_ALPHABLEND | Questo record specifica un trasferimento a blocchi di pixel da un bitmap di origine a un rettangolo di destinazione,<br/>             includendo dati di trasparenza alfa, secondo un'operazione di fusione specificata. |
| EMR_ANGLEARC | Questo record definisce un segmento di linea di un arco. Il segmento è disegnato dalla <br/>            posizione corrente all'inizio dell'arco. L'arco è tracciato lungo il perimetro <br/>            di un cerchio con il raggio e il centro forniti. La lunghezza dell'arco è definita dagli <br/>            angoli di inizio e di sweep forniti. |
| EMR_ARC | Questo record definisce un arco ellittico. |
| EMR_ARCTO | Questo record definisce un arco ellittico. Reimposta la posizione corrente al <br/>            punto finale dell'arco. |
| EMR_BEGINPATH | Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione. |
| EMR_BITBLT | Questo record specifica un trasferimento a blocchi di pixel da un bitmap di origine a un rettangolo di destinazione<br/>             opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata. |
| EMR_CHORD | Questo record definisce una corda (una regione delimitata dall'intersezione di un'ellisse <br/>            e un segmento di linea, chiamata secante). La corda è delineata usando la penna corrente <br/>            e riempita usando il pennello corrente. |
| EMR_CLOSEFIGURE | Questo record chiude una figura aperta in un percorso. |
| EMR_COLORCORRECTPALETTE | Questo record specifica come correggere le voci di un oggetto palette logica usando i valori del Windows <br/>            Color System (WCS) 1.0. |
| EMR_COLORMATCHTOTARGETW | Questo record specifica se eseguire l'abbinamento del colore con un profilo colore specificato in un file il cui nome è composto da caratteri Unicode. |
| EMR_COMMENT | Questo record specifica dati privati arbitrari. |
| EMR_CREATEBRUSHINDIRECT | Questo record definisce un pennello logico per il riempimento delle figure nelle operazioni grafiche. |
| EMR_CREATECOLORSPACE | Questo record crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri ASCII |
| EMR_CREATECOLORSPACEW | Questo record crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri Unicode |
| EMR_CREATEDIBPATTERNBRUSHPT | Questo record definisce un pennello logico che ha il motivo specificato dal DIB. |
| EMR_CREATEMONOBRUSH | Questo record definisce un pennello logico con il modello bitmap specificato. Il bitmap può<br/>             essere una bitmap indipendente dal dispositivo (DIB) bitmap di sezione o può essere una bitmap dipendente dal dispositivo. |
| EMR_CREATEPALETTE | Questo record definisce un oggetto LogPalette. |
| EMR_CREATEPEN | Questo record definisce una penna logica che ha lo stile, la larghezza e il colore specificati. <br/>            La penna può successivamente essere selezionata nel contesto dispositivo di riproduzione e utilizzata per disegnare linee e curve. |
| EMR_DELETECOLORSPACE | Questo record elimina un oggetto spazio colore logico. Nota: un record EMR_DELETEOBJECT DOVREBBE essere <br/>            usato al posto di EMR_DELETECOLORSPACE per eliminare un oggetto spazio colore logico |
| EMR_DELETEOBJECT | Questo record elimina un oggetto grafico, cancellando il suo indice nella Tabella Oggetti EMF. <br/>            Se l'oggetto eliminato è selezionato nel contesto dispositivo di riproduzione, l'oggetto predefinito <br/>            per quella proprietà del contesto DEVE essere ripristinato. |
| EMR_DRAWESCAPE | Questo record passa informazioni arbitrarie al driver. L'intento è che le informazioni <br/>            provochino l'esecuzione del disegno. |
| EMR_ELLIPSE | Questo record definisce un'ellisse. Il centro dell'ellisse è il centro del <br/>            rettangolo di delimitazione specificato. L'ellisse è tracciata usando la penna corrente e <br/>            è riempita usando il pennello corrente. |
| EMR_ENDPATH | Questo record chiude una parentesi di percorso e seleziona il percorso definito dalla parentesi <br/>            nel contesto del dispositivo di riproduzione. |
| EMR_EOF | Questo record indica la fine del metafile. |
| EMR_EXCLUDECLIPRECT | Questo record definisce una nuova regione di ritaglio che consiste nella regione di ritaglio esistente <br/>            meno il rettangolo specificato. |
| EMR_EXTCREATEFONTINDIRECTW | Questo record definisce un carattere logico che ha le caratteristiche specificate. Il carattere <br/>            può successivamente essere selezionato come carattere corrente per il contesto del dispositivo di riproduzione. |
| EMR_EXTCREATEPEN | Questo record definisce una penna cosmetica o geometrica logica che ha lo stile, <br/>            la larghezza e gli attributi del pennello specificati. |
| EMR_EXTESCAPE | Questo record passa informazioni arbitrarie al driver. L'intento è che le informazioni <br/>            non comportino alcun disegno. |
| EMR_EXTFLOODFILL | Questo record riempie un'area della superficie di visualizzazione con il pennello corrente. |
| EMR_EXTSELECTCLIPRGN | Questo record combina la regione specificata con la regione di ritaglio corrente usando la <br/>            modalità specificata. |
| EMR_EXTTEXTOUTA | Questo record disegna una stringa di testo ASCII usando il carattere corrente e i colori del testo. Nota <br/>            EMR_EXTTEXTOUTA DEVE essere emulato con un record EMR_EXTTEXTOUTW (sezione 2.3.5.8).  <br/>            Ciò richiede che la stringa di testo ASCII nell'oggetto EmrText sia convertita in codifica Unicode UTF16-LE. |
| EMR_EXTTEXTOUTW | Questo record disegna una stringa di testo Unicode usando il carattere corrente e i colori del testo. |
| EMR_FILLPATH | Questo record chiude tutte le figure aperte nel percorso corrente e riempie l'interno del percorso <br/>            usando il pennello corrente e la modalità di riempimento dei poligoni. |
| EMR_FILLRGN | Questo record riempie la regione specificata usando il pennello specificato. |
| EMR_FLATTENPATH | Questo record trasforma qualsiasi curva nel percorso selezionato nel contesto del dispositivo di riproduzione <br/>            contesto, trasformando ogni curva in una sequenza di linee. |
| EMR_FORCEUFIMAPPING | Questo record forza il mapper dei caratteri a corrispondere i font in base al loro UniversalFontId <br/>            preferendo le informazioni LogFont. |
| EMR_FRAMERGN | Questo record disegna un bordo attorno all'area specificata usando il pennello specificato. |
| EMR_GLSBOUNDEDRECORD | Questo record specifica una funzione OpenGL con un rettangolo di delimitazione per l'output. |
| EMR_GLSRECORD | Questo record specifica una funzione OpenGL. |
| EMR_GRADIENTFILL | Questo record specifica il riempimento di rettangoli o triangoli con gradienti di colore |
| EMR_HEADER | Questo record definisce l'inizio del metafile e ne specifica le caratteristiche; il suo contenuto, <br/>            incluse le dimensioni dell'immagine incorporata; il numero di record nel metafile; e la <br/>            risoluzione del dispositivo su cui è stata creata l'immagine incorporata. Questi valori rendono possibile che il metafile sia indipendente dal dispositivo. |
| EMR_INTERSECTCLIPRECT | Questo record definisce una nuova regione di ritaglio dall'intersezione della regione di ritaglio corrente <br/>            e del rettangolo specificato. |
| EMR_INVERTRGN | Questo record inverte i colori nella regione specificata. |
| EMR_LINETO | Questo record definisce una linea dalla posizione corrente fino a, ma senza includere,<br/>             il punto specificato. Reimposta la posizione corrente al punto specificato. |
| EMR_MASKBLT | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione<br/>             , opzionalmente in combinazione con un modello di pennello e con l'applicazione di un <br/>            bitmap di maschera colore, secondo le operazioni raster di primo piano e sfondo specificate. |
| EMR_MODIFYWORLDTRANSFORM | Questo record ridefinisce la trasformazione del mondo per il contesto del dispositivo di riproduzione usando la modalità specificata. |
| EMR_MOVETOEX | Questo record definisce le coordinate della nuova posizione corrente, in unità logiche. |
| EMR_NAMEDESCAPE | Questo record trasmette informazioni arbitrarie al driver denominato fornito. |
| EMR_OFFSETCLIPRGN | Questo record ridefinisce la regione di ritaglio del contesto del dispositivo di riproduzione mediante gli offset specificati. |
| EMR_PAINTRGN | Questo record dipinge la regione specificata utilizzando il pennello attualmente selezionato nel <br/>            contesto del dispositivo di riproduzione. |
| EMR_PIE | Questo record definisce una sezione a forma di torta delimitata dall'intersezione di un'ellisse <br/>            e due raggi. La torta è contornata utilizzando la penna corrente e riempita utilizzando <br/>            il pennello corrente. |
| EMR_PIXELFORMAT | Questo record specifica il formato pixel da utilizzare per le operazioni grafiche |
| EMR_PLGBLT | Questo record specifica un trasferimento a blocchi di pixel da una bitmap sorgente a un parallelogramma di destinazione <br/>            , con l'applicazione di una bitmap maschera di colore. |
| EMR_POLYBEZIER | Questo record definisce una o più curve di Bézier. Le curve di Bézier cubiche sono definite utilizzando<br/>            punti finali e punti di controllo specificati, e sono tracciate con la penna corrente. |
| EMR_POLYBEZIER16 | Questo record definisce una o più curve di Bézier. Le curve sono disegnate utilizzando la penna corrente. |
| EMR_POLYBEZIERTO | Questo record definisce una o più curve di Bézier basate sulla posizione corrente. |
| EMR_POLYBEZIERTO16 | Questo record definisce una o più curve di Bézier basate sulla posizione corrente. |
| EMR_POLYDRAW | Questo record definisce un insieme di segmenti di linea e curve di Bézier. |
| EMR_POLYDRAW16 | Questo record definisce un insieme di segmenti di linea e curve di Bézier. |
| EMR_POLYGON | Questo record definisce un poligono costituito da due o più vertici collegati da linee rette <br/>            linee. Il poligono è delineato usando la penna corrente e riempito usando il pennello corrente <br/>            e la modalità di riempimento del poligono. Il poligono viene chiuso automaticamente disegnando una linea dall'ultimo vertice al primo. |
| EMR_POLYGON16 | Questo record definisce un poligono costituito da due o più vertici collegati da linee rette. <br/>            Il poligono è delineato usando la penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono.<br/>             Il poligono viene chiuso automaticamente disegnando una linea dall'ultimo vertice al primo. |
| EMR_POLYLINE | Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato <br/>            array. |
| EMR_POLYLINE16 | Questo record definisce una serie di segmenti di linea collegando i punti nell'array specificato. |
| EMR_POLYLINETO | Questo record definisce una o più linee rette basate sulla posizione corrente. <br/>            Una linea è disegnata dalla posizione corrente al primo punto specificato dal campo points <br/>            usando la penna corrente. Per ogni linea aggiuntiva, il disegno viene eseguito dal punto finale <br/>            della linea precedente al punto successivo specificato da points. |
| EMR_POLYLINETO16 | Questo record definisce una o più linee rette basate sulla posizione corrente.<br/>             Una linea è disegnata dalla posizione corrente al primo punto specificato dal campo Points <br/>            usando la penna corrente. Per ogni linea aggiuntiva, il disegno viene eseguito dal <br/>            punto finale della linea precedente al punto successivo specificato da Points. |
| EMR_POLYPOLYGON | Questo record definisce una serie di poligoni chiusi. Ogni poligono è delineato usando la <br/>            penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono. I poligoni definiti da questo record possono sovrapporsi. |
| EMR_POLYPOLYGON16 | Questo record definisce una serie di poligoni chiusi. Ogni poligono è delineato usando <br/>            la penna corrente e riempito usando il pennello corrente e la modalità di riempimento del poligono. I poligoni<br/>             specificati da questo record possono sovrapporsi. |
| EMR_POLYPOLYLINE | Questo record definisce più serie di segmenti di linea collegati. I segmenti di linea sono <br/>            disegnati usando la penna corrente. Le figure formate dai segmenti non sono riempite. L<br/>            a posizione corrente non è né usata né aggiornata da questo record. |
| EMR_POLYPOLYLINE16 | Questo record definisce più serie di segmenti di linea collegati. |
| EMR_POLYTEXTOUTA | Questo record disegna una o più stringhe di testo ASCII usando il font corrente e i colori del testo.<br/>             Nota EMR_POLYTEXTOUTA DEVE essere emulato con una serie di record EMR_EXTTEXTOUTW, uno per stringa |
| EMR_POLYTEXTOUTW | Questo record disegna una o più stringhe di testo Unicode usando il font corrente e i colori del testo.<br/>            Nota EMR_POLYTEXTOUTW DEVE essere emulato con una serie di record EMR_EXTTEXTOUTW, uno per stringa |
| EMR_REALIZEPALETTE | Questo record mappa le voci dalla palette logica corrente alla palette di sistema. |
| EMR_RECTANGLE | Questo record definisce un rettangolo. Il rettangolo è delineato utilizzando la penna corrente <br/>            e riempito utilizzando il pennello corrente. |
| EMR_RESIZEPALETTE | Questo record aumenta o diminuisce le dimensioni di una palette logica. |
| EMR_RESTOREDC | Questo record ripristina il contesto del dispositivo di riproduzione allo stato salvato specificato. <br/>            Il contesto del dispositivo di riproduzione viene ripristinato rimuovendo le informazioni di stato da una pila di <br/>            contesti di dispositivo salvati creati da precedenti record EMR_SAVEDC (sezione 2.3.11). |
| EMR_ROUNDRECT | Questo record definisce un rettangolo con angoli arrotondati. Il rettangolo è delineato <br/>            utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| EMR_SAVEDC | Questo record salva lo stato corrente del contesto del dispositivo di riproduzione copiando i dati <br/>            che descrivono gli oggetti selezionati e le modalità grafiche—incluse la bitmap, il pennello, la palette, <br/>            il carattere, la penna, la regione, la modalità di disegno e la modalità di mappatura—su una pila di contesti di dispositivo salvati. |
| EMR_SCALEVIEWPORTEXTEX | Questo record ridefinisce il viewport per il contesto del dispositivo di riproduzione utilizzando i rapporti <br/>            formati dai moltiplicatori e divisori specificati. |
| EMR_SCALEWINDOWEXTEX | Questo record ridefinisce la finestra per il contesto del dispositivo di riproduzione utilizzando i rapporti formati <br/>            dai moltiplicatori e divisori specificati. |
| EMR_SELECTCLIPPATH | Questo record definisce il percorso corrente come regione di ritaglio per il contesto del dispositivo di <br/>            riproduzione, combinando la nuova regione con qualsiasi regione di ritaglio esistente utilizzando la modalità specificata. |
| EMR_SELECTOBJECT | Questo record aggiunge un oggetto al contesto del dispositivo di riproduzione, identificandolo tramite il suo <br/>            indice nella Tabella degli Oggetti EMF (sezione 3.1.1.1). |
| EMR_SELECTPALETTE | Questo record aggiunge un oggetto LogPalette (sezione 2.2.17) al contesto del dispositivo di <br/>            riproduzione, identificandolo tramite il suo indice nella Tabella degli Oggetti EMF. |
| EMR_SETARCDIRECTION | Questo record definisce la direzione di disegno da utilizzare per le operazioni di arco e rettangolo<br/>             . |
| EMR_SETBKCOLOR | Questo record definisce il colore di sfondo. |
| EMR_SETBKMODE | Questo record definisce la modalità di miscelazione dello sfondo del contesto del dispositivo di riproduzione. La modalità di miscelazione dello sfondo<br/>             è utilizzata con testo, pennelli tratteggiati e stili di penna che non sono linee solide. |
| EMR_SETBRUSHORGEX | Questo record definisce l'origine del pennello corrente. |
| EMR_SETCOLORADJUSTMENT | Questo record definisce i valori di regolazione del colore per il contesto del dispositivo di riproduzione utilizzando i valori specificati. |
| EMR_SETCOLORSPACE | Questo record definisce l'oggetto spazio colore logico corrente per le operazioni grafiche. |
| EMR_SETDIBITSTODEVICE | Questo record specifica un trasferimento a blocchi di pixel dalle linee di scansione specificate di una bitmap di origine<br/>             a un rettangolo di destinazione. |
| EMR_SETICMMODE | Questo record specifica la modalità di Image Color Management (ICM) per le operazioni grafiche. |
| EMR_SETICMPROFILEA | Questo record specifica un profilo colore in un file con un nome composto da caratteri ASCII,<br/>             per l'output grafico. |
| EMR_SETICMPROFILEW | Questo record specifica un profilo colore in un file con un nome composto da caratteri Unicode,<br/>             per l'output grafico |
| EMR_SETLAYOUT | Questo record specifica l'ordine in cui testo e grafica vengono disegnati |
| EMR_SETLINKEDUFIS | Questo record imposta gli UniversalFontIds dei font collegati da utilizzare durante la ricerca dei caratteri. |
| EMR_SETMAPMODE | Questo record definisce la modalità di mappatura del contesto del dispositivo di riproduzione. La modalità di mappatura<br/>             definisce l'unità di misura utilizzata per trasformare le unità di spazio pagina in unità di spazio dispositivo,<br/>             e definisce anche l'orientamento dell'asse x e dell'asse y del dispositivo. |
| EMR_SETMAPPERFLAGS | Questo record specifica i parametri del processo di corrispondenza dei font logici ai font fisici <br/>            font, che è eseguito dal mapper dei font. |
| EMR_SETMETARGN | Questo record interseca la regione di ritaglio corrente per il contesto del dispositivo di riproduzione con la <br/>            regione meta corrente e salva la regione combinata come nuova regione meta. La regione di ritaglio viene reimpostata a una regione nulla. |
| EMR_SETMITERLIMIT | Questo record definisce il limite per la lunghezza delle giunzioni a spigolo per la riproduzione <br/>            contesto del dispositivo. |
| EMR_SETPALETTEENTRIES | Questo record definisce i valori di colore RGB (rosso-verde-blu) in un intervallo di voci <br/>            in un oggetto LogPalette. |
| EMR_SETPIXELV | Questo record definisce il colore del pixel alle coordinate logiche specificate. |
| EMR_SETPOLYFILLMODE | Questo record definisce la modalità di riempimento del poligono. |
| EMR_SETROP2 | Questo record definisce la modalità di operazione raster binaria. |
| EMR_SETSTRETCHBLTMODE | Questo record definisce la modalità di stretching della bitmap. |
| EMR_SETTEXTALIGN | Questo record definisce l'allineamento del testo. |
| EMR_SETTEXTCOLOR | Questo record definisce il colore corrente del testo. |
| EMR_SETTEXTJUSTIFICATION | Questo record specifica la quantità di spazio extra da aggiungere ai caratteri di interruzione per la giustificazione<br/>             scopi. |
| EMR_SETVIEWPORTEXTEX | Questo record definisce l'estensione del viewport. |
| EMR_SETVIEWPORTORGEX | Questo record definisce l'origine del viewport. |
| EMR_SETWINDOWEXTEX | Questo record definisce l'estensione della finestra. |
| EMR_SETWINDOWORGEX | Questo record definisce l'origine della finestra. |
| EMR_SETWORLDTRANSFORM | Questo record definisce una trasformazione lineare bidimensionale tra lo spazio mondo e <br/> lo spazio pagina (per ulteriori informazioni, vedere [MSDN-WRLDPGSPC]) per il contesto del dispositivo di riproduzione. <br/> Questa trasformazione può essere usata per scalare, ruotare, inclinare o tradurre l'output grafico. |
| EMR_SMALLTEXTOUT | Questo record emette una stringa. |
| EMR_STRETCHBLT | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione<br/> opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata<br/> , allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| EMR_STRETCHDIBITS | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione <br/> opzionalmente in combinazione con un modello di pennello, secondo un'operazione raster specificata, <br/> allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| EMR_STROKEANDFILLPATH | Questo record chiude tutte le figure aperte in un percorso, traccia il contorno del percorso usando <br/> la penna corrente, e riempie il suo interno usando il pennello corrente. |
| EMR_STROKEPATH | Questo record rende il percorso specificato usando la penna corrente. |
| EMR_TRANSPARENTBLT | Questo record specifica un trasferimento a blocchi di pixel da un bitmap sorgente a un rettangolo di destinazione,<br/> trattando un colore specificato come trasparente, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| EMR_WIDENPATH | Questo record ridefinisce il percorso corrente come l'area che verrebbe dipinta se il percorso <br/> fosse tracciato usando la penna attualmente selezionata nel contesto del dispositivo di riproduzione. |

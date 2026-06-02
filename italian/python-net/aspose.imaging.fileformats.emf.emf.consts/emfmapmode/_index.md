---
title: "Enumerazione EmfMapMode"
type: docs
weight: 210
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---

L'enumerazione MapMode è usata per definire l'unità di misura per trasformare le unità di spazio della pagina <br/>            in unità di spazio del dispositivo e per definire l'orientamento degli assi di disegno.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfMapMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| MM_ANISOTROPIC | Le unità logiche sono mappate a unità arbitrarie con assi scalati arbitrariamente. <br/>            I record EMR_SETWINDOWEXTEX e EMR_SETVIEWPORTEXTEX DEVONO essere usati per specificare le unità, <br/>            l'orientamento e la scala. |
| MM_HIENGLISH | Ogni unità logica è mappata a 0,001 pollice. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto. |
| MM_HIMETRIC | Ogni unità logica è mappata a 0,01 millimetro. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto. |
| MM_ISOTROPIC | Le unità logiche sono mappate a unità arbitrarie con assi scalati in modo uguale; cioè, un'unità <br/>            lungo l'asse x è uguale a un'unità lungo l'asse y. I record EMR_SETWINDOWEXTEX e <br/>            EMR_SETVIEWPORTEXTEX DEVONO essere usati per specificare le unità e l'orientamento <br/>            degli assi.<br/>            È necessario effettuare regolazioni, se necessario, per garantire che le unità x e y mantengano la stessa dimensione. <br/>            Ad esempio, quando l'estensione della finestra è impostata, il viewport DEVE essere regolato per mantenere le unità isotrope. |
| MM_LOENGLISH | Ogni unità logica è mappata a 0,01 pollice. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto |
| MM_LOMETRIC | Ogni unità logica è mappata a 0,1 millimetro. L'asse x positivo è verso destra; l'asse y positivo è verso l'alto. |
| MM_TEXT | Ogni unità logica è mappata a un pixel del dispositivo. L'asse x positivo è verso destra; l'asse y positivo è verso il basso. |
| MM_TWIPS | Ogni unità logica è mappata a un ventiduesimo di un punto di stampa <br/>            (1/1440 di pollice, chiamato anche "twip"). L'asse x positivo è verso destra; l'asse y positivo è verso l'alto. |

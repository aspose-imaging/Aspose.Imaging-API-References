---
title: "Enumeración EmfMapMode"
type: docs
weight: 210
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---

La enumeración MapMode se utiliza para definir la unidad de medida para transformar unidades del espacio de página <br/>            en unidades del espacio del dispositivo y para definir la orientación de los ejes de dibujo.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfMapMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| MM_ANISOTROPIC | Las unidades lógicas se asignan a unidades arbitrarias con ejes escalados arbitrariamente. <br/> Los registros EMR_SETWINDOWEXTEX y EMR_SETVIEWPORTEXTEX DEBEN usarse para especificar las unidades, <br/> la orientación y el escalado. |
| MM_HIENGLISH | Cada unidad lógica se asigna a 0.001 pulgada. El eje x positivo está a la derecha; el eje y positivo está hacia arriba. |
| MM_HIMETRIC | Cada unidad lógica se asigna a 0.01 milímetro. El eje x positivo está a la derecha; el eje y positivo está hacia arriba. |
| MM_ISOTROPIC | Las unidades lógicas se asignan a unidades arbitrarias con ejes escalados de manera uniforme; es decir, una unidad <br/> a lo largo del eje x es igual a una unidad a lo largo del eje y. Los registros EMR_SETWINDOWEXTEX y <br/> EMR_SETVIEWPORTEXTEX DEBEN usarse para especificar las unidades y la orientación <br/> de los ejes.<br/> Se DEBEN realizar ajustes según sea necesario para garantizar que las unidades x e y mantengan el mismo tamaño. <br/> Por ejemplo, cuando se establece la extensión de la ventana, la zona de visión DEBE ajustarse para mantener las unidades isotrópicas. |
| MM_LOENGLISH | Cada unidad lógica se asigna a 0.01 pulgada. El eje x positivo está a la derecha; el eje y positivo está hacia arriba |
| MM_LOMETRIC | Cada unidad lógica se asigna a 0.1 milímetro. El eje x positivo está a la derecha; el eje y positivo está hacia arriba. |
| MM_TEXT | Cada unidad lógica se asigna a un píxel del dispositivo. El eje x positivo está a la derecha; el eje y positivo está hacia abajo. |
| MM_TWIPS | Cada unidad lógica se asigna a una vigésima parte del punto de una impresora <br/> (1/1440 pulgada, también llamado "twip"). El eje x positivo está a la derecha; el eje y positivo está hacia arriba. |

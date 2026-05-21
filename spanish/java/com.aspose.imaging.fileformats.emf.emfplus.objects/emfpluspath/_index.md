---
title: "EmfPlusPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPath especifica una serie de segmentos de línea y curva que forman una ruta gráfica."
type: docs
weight: 58
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusPath especifica una serie de segmentos de línea y curva que forman una ruta gráfica. El orden de los puntos de datos Bézier es el punto de inicio, punto de control 1, punto de control 2 y punto final. Para más información vea[MSDN - DrawBeziers].
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Obtiene o establece el recuento de puntos de ruta. Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que define este objeto. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Obtiene o establece el recuento de puntos de ruta. Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que define este objeto. |
| [getPathPoints()](#getPathPoints--) | Obtiene o establece una matriz de puntos de ruta. Una matriz de PathPointCount puntos que especifican la ruta. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Obtiene o establece una matriz de puntos de ruta. Una matriz de PathPointCount puntos que especifican la ruta. |
| [getPathPointTypes()](#getPathPointTypes--) | Obtiene o establece una matriz que especifica cómo se utilizan los puntos en el campo PathPoints para dibujar la ruta. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Obtiene o establece una matriz que especifica cómo se utilizan los puntos en el campo PathPoints para dibujar la ruta. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Obtiene o establece el recuento de puntos de ruta. Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que define este objeto.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Obtiene o establece el recuento de puntos de ruta. Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que define este objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Obtiene o establece una matriz de puntos de ruta. Una matriz de PathPointCount puntos que especifican la ruta. El tipo de objetos en esta matriz se especifica mediante el campo PathPointFlags, como sigue: Si el indicador P está activado, los puntos son ubicaciones relativas que se especifican mediante objetos EmfPlusPointR (sección 2.2.2.37). Si el indicador P está desactivado y el indicador C está activado, los puntos son ubicaciones absolutas que se especifican mediante objetos EmfPlusPoint (sección 2.2.2.35). Si el indicador P está desactivado y el indicador C está desactivado, los puntos son ubicaciones absolutas que se especifican mediante objetos EmfPlusPointF (sección 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Obtiene o establece una matriz de puntos de ruta. Una matriz de PathPointCount puntos que especifican la ruta. El tipo de objetos en esta matriz se especifica mediante el campo PathPointFlags, como sigue: Si el indicador P está activado, los puntos son ubicaciones relativas que se especifican mediante objetos EmfPlusPointR (sección 2.2.2.37). Si el indicador P está desactivado y el indicador C está activado, los puntos son ubicaciones absolutas que se especifican mediante objetos EmfPlusPoint (sección 2.2.2.35). Si el indicador P está desactivado y el indicador C está desactivado, los puntos son ubicaciones absolutas que se especifican mediante objetos EmfPlusPointF (sección 2.2.2.36).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Obtiene o establece una matriz que especifica cómo se utilizan los puntos en el campo PathPoints para dibujar la ruta. El tipo de objetos en esta matriz se especifica mediante el indicador R en el campo PathPointFlags.

Valor: Los tipos de punto de ruta.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Obtiene o establece una matriz que especifica cómo se utilizan los puntos en el campo PathPoints para dibujar la ruta. El tipo de objetos en esta matriz se especifica mediante el indicador R en el campo PathPointFlags.

Valor: Los tipos de punto de ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |


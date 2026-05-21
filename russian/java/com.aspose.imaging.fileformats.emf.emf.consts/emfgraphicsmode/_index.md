---
title: "EmfGraphicsMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление GraphicsMode используется для указания, как интерпретировать данные фигур, такие как координаты прямоугольников."
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

Перечисление GraphicsMode используется для указания, как интерпретировать данные фигур, такие как координаты прямоугольников.
## Поля

| Поле | Описание |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | Текст TrueType MUST быть записан слева направо и в правильной ориентации, даже если остальные графические элементы вращаются вокруг оси x или оси y из‑за текущего преобразования мир‑устройство в контексте воспроизведения устройства. |
| [GM_ADVANCED](#GM-ADVANCED) | Вывод текста TrueType MUST полностью соответствовать текущему преобразованию мир‑устройство в контексте воспроизведения устройства. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


Текст TrueType MUST быть записан слева направо и в правильной ориентации, даже если остальные графические элементы вращаются вокруг оси x или оси y из‑за текущего преобразования мир‑устройство в контексте воспроизведения устройства. Только высота текста SHOULD масштабироваться. Дуги MUST рисоваться с использованием текущего направления дуги в контексте воспроизведения устройства, но они MUST NOT учитывать текущее преобразование мир‑устройство, которое может потребовать вращения вокруг оси x или оси y. Преобразование мир‑устройство SHOULD изменяться только путем изменения размеров и начальных точек окна и области просмотра, используя записи EMR\_SETWINDOWEXTEX (section 2.3.11.30) и EMR\_SETVIEWPORTEXTEX (section 2.3.11.28), а также EMR\_SETWINDOWORGEX (section 2.3.11.31) и EMR\_SETVIEWPORTORGEX (section 2.3.11.30) соответственно. bChanging преобразование напрямую с помощью записей EMR\_MODIFYWORLDTRANSFORM (section 2.3.12.1) или EMR\_SETWORLDTRANSFORM (section 2.3.12.2) MAY NOT поддерживаться. В режиме графики GM\_COMPATIBLE нижние и правые края MUST быть исключены при рисовании прямоугольников

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


Вывод текста TrueType MUST полностью соответствовать текущему преобразованию мир‑устройство в контексте воспроизведения устройства. Дуги MUST рисоваться в направлении против часовой стрелки в мировом пространстве; однако как контрольные точки дуг, так и сами дуги MUST полностью учитывать текущее преобразование мир‑устройство в контексте воспроизведения устройства. Преобразование мир‑устройство MAY изменяться напрямую с помощью записей EMR\_MODIFYWORLDTRANSFORM или EMR\_SETWORLDTRANSFORM, либо косвенно путем изменения размеров и начальных точек окна и области просмотра, используя записи EMR\_SETWINDOWEXTEX (section 2.3.11.30) и EMR\_SETVIEWPORTEXTEX (section 2.3.11.28), а также EMR\_SETWINDOWORGEX (section 2.3.11.31) и EMR\_SETVIEWPORTORGEX (section 2.3.11.30) соответственно. В режиме графики GM\_ADVANCED нижние и правые края MUST быть включены при рисовании прямоугольников.


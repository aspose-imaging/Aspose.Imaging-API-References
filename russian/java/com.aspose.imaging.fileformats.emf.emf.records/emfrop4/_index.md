---
title: "EmfRop4"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Четверичная растровая операция, определяющая тернарные растровые операции для цветов переднего плана и фона растрового изображения."
type: docs
weight: 110
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

Четверичная растровая операция, определяющая тернарные растровые операции для цветов переднего плана и фона растрового изображения. Эти значения определяют, как данные цвета исходного прямоугольника должны комбинироваться с данными цвета целевого прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Инициализирует новый экземпляр класса `EmfRop4`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Получает фоновой ROP3. |
| [getForegroundRop3()](#getForegroundRop3--) | Получает передний ROP3. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Инициализирует новый экземпляр класса `EmfRop4`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dwordData | int | Данные dword. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Получает фоновой ROP3. Беззнаковые, старшие 8 бит 24‑битного значения тернарной растровой операции из перечисления WMF Ternary Raster Operation ([MS-WMF] раздел 2.1.1.31). Этот код определяет, как комбинировать данные фонового цвета исходных и целевых битмапов и узор кисти.

Значение: Фоновый ROP3.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Получает ROP3 переднего плана. Беззнаковые, старшие 8 бит 24‑битного значения тернарной растровой операции из перечисления WMF Ternary Raster Operation. Этот код определяет, как комбинировать данные цвета переднего плана исходных и целевых битмапов и узор кисти.

Значение: ROP3 переднего плана.

**Returns:**
byte

---
title: "Класс Metered"
type: docs
weight: 6150
url: /ru/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Инициализирует новый экземпляр этого класса. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Получает кредит потребления |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Получает размер файла потребления |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Устанавливает публичный и приватный ключ Metered.<br/>            Если вы покупаете лицензию Metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно. <br/>            Однако, если постоянно не удаётся загрузить данные потребления и прошло более 24 часов, лицензия будет переведена в статус оценки, <br/>            чтобы избежать такой ситуации, следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Инициализирует новый экземпляр этого класса.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Получает кредит потребления

**Returns**

| Тип | Описание |
| :- | :- |
| System.Decimal | количество потребления |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Получает размер файла потребления

**Returns**

| Тип | Описание |
| :- | :- |
| System.Decimal | количество потребления |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Устанавливает публичный и приватный ключ Metered.<br/>            Если вы покупаете лицензию Metered, при запуске приложения этот API должен быть вызван, обычно этого достаточно. <br/>            Однако, если постоянно не удаётся загрузить данные потребления и прошло более 24 часов, лицензия будет переведена в статус оценки, <br/>            чтобы избежать такой ситуации, следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| public_key | string | публичный ключ |
| private_key | string | приватный ключ |


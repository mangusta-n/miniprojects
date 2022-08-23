## Исследование данных. Retention матрица. Кластеризация(RFM, KMeans)

### Данные
**E-Commerce Data** This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.'

Имеются следующие данные о транзакциях в период с 01.12.2010 по 12.09.2011:

InvoiceNo — номер транзакции  
StockCode — код товара  
Description — описание товара  
Quantity — количество единиц товара, добавленных в заказ  
InvoiceDate — дата транзакции   
UnitPrice — цена за единицу товара  
CustomerID — id клиента  
Country — страна, где проживает клиент  
  
Данные содержат в себе записи как об успешных транзакциях, так и об отмененных. В данных встречаются строки с Description 'Manual', которые включают данные об удаленных из чека позициях.

### Задачи
* Предобработка и исследование данных.
* Построить Retention matrix
* Провести разделение покупателей на сегменты методом RFM (recency, frequency, monetary).
* Провести разделение покупателей на сегменты методом KMeans.

### Используемые библиотеки и пр.
*pandas, numpy, seaborn, matplotlib, plotly, sklearn*

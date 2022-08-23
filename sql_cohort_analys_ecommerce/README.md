### Описание данных
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


### Особенности

*Датасет находится в Clickhouse, причем доступен только для чтения, что делает невозможным создание представлений, и (специфика СУБД) вынесение подзапросов в CTE. Будем выкручиваться.*

### Задачи
* Проанализировать продажи на внутреннем рынке UK, сгруппировав покупателей в когорты по числу покупок - средствами SQL (Clickhouse).   
* Проанализировать динамику выручки и продаж в динамике в течение года.   
* Оценить новых и повторных клиентов в динамике за 2011 год.  
* Построить таблицу Retention rate средствами SQL.

### Используемые библиотеки и пр.
*SQL(Clickhouse), pandahouse, pandas, numpy, seaborn, matplotlib, redash*

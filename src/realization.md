## Реализация


### 1. Создадим справочник стоимости доставки в страны shipping_country_rates
```SQL






```


### 2. Создадим справочник тарифов доставки вендора по договору shipping_agreement из данных строки vendor_agreement_description
```SQL






```


### 3. Создадим справочник о типах доставки shipping_transfer из строки shipping_transfer_description
```SQL






```


### 4. Создадим таблицу shipping_info с уникальными доставками shippingid и свяжите её с созданными справочниками shipping_country_rates, shipping_agreement, shipping_transfer и константной информацией о доставке shipping_plan_datetime , payment_amount , vendorid
```SQL






```


### 5. Создадим таблицу статусов о доставке shipping_status и включите туда информацию из лога shipping (status , state). Добавим туда вычислимую информацию по фактическому времени доставки shipping_start_fact_datetime, shipping_end_fact_datetime . Отразим для каждого уникального shippingid его итоговое состояние доставки
```SQL






```


### 6. Создадим представление shipping_datamart на основании готовых таблиц для аналитики
```SQL






```

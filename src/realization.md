## Описание



```SQL
CREATE OR REPLACE VIEW analysis.products as (
	select * from production.products);
CREATE OR REPLACE VIEW analysis.orderitems as (
	select * from production.orderitems);
CREATE OR REPLACE VIEW analysis.orders as (
	select * from production.orders);
CREATE OR REPLACE VIEW analysis.orderstatuslog as (
	select * from production.orderstatuslog);
CREATE OR REPLACE VIEW analysis.orderstatuses as (
	select * from production.orderstatuses);
CREATE OR REPLACE VIEW analysis.users as (
	select * from production.users);
```

# sqlTenthTask
## Bu repo [Patika.dev](https://www.patika.dev) tarafından verilen `SQL` ödevini içermektedir.
---
### Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.
### 1- city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
- SELECT city.city, country.country FROM city
- LEFT JOIN country ON city.city_id = country.country_id;
### 2- customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
- SELECT payment_id, first_name, last_name FROM customer
- RIGHT JOIN payment ON payment.staff_id = customer.store_id;
### 3- customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.
- SELECT rental_id, first_name, last_name FROM customer
- FULL JOIN rental ON rental.rental_id = customer.customer_id;

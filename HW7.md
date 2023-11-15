### HW7
1. film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.<br>
```
SELECT rating , COUNT(*) FROM film GROUP BY rating;
```
2. film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.<br>
```
SELECT replacement_cost,COUNT(*) FROM film GROUP BY replacement_cost HAVING COUNT(*) > 50;
```
3. customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir.<br>
```
SELECT store_id , COUNT(*) FROM customer GROUP BY store_id;
```
4. ity tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.<br>
```
SELECT country_id , COUNT(*) FROM City GROUP BY country_id ORDER BY COUNT(City) DESC LIMIT 1;
```
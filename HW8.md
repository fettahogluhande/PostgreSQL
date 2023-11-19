### HW8
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.<br>
```
CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.<br>
```
insert into employee (name, birthday, email) values ('Penelopa', '1998-05-30', 'pdyer0@typepad.com');
insert into employee (name, birthday, email) values ('Caspar', '1980-04-01', 'cstock1@businesswire.com');
insert into employee (name, birthday, email) values ('Shaun', '1944-07-08', 'sgecks2@usa.gov');
insert into employee (name, birthday, email) values ('Cacilie', '2022-07-14', 'cdietsche3@creativecommons.org');
insert into employee (name, birthday, email) values ('Viviyan', '1980-12-16', 'vburdett4@ucoz.com');
insert into employee (name, birthday, email) values ('Obed', '2016-08-25', 'oowbrick5@reference.com');
insert into employee (name, birthday, email) values ('Mira', '1925-05-07', 'mlempke6@engadget.com');
insert into employee (name, birthday, email) values ('Sammy', '1987-12-17', 'swinspur7@google.cn');
insert into employee (name, birthday, email) values ('Adda', '1989-04-06', 'aperkin8@google.de');
insert into employee (name, birthday, email) values ('Esme', '1991-12-07', 'egammel9@pen.io');
insert into employee (name, birthday, email) values ('Ros', '1966-09-01', 'rmacbaina@smugmug.com');
insert into employee (name, birthday, email) values ('Meade', '1921-07-25', 'mbloyb@ebay.co.uk');
insert into employee (name, birthday, email) values ('Omar', '1947-01-25', 'orimerc@adobe.com');
insert into employee (name, birthday, email) values ('Norry', '1978-11-07', 'nslessord@wunderground.com');
insert into employee (name, birthday, email) values ('Huntlee', '1961-12-22', 'hringse@w3.org');
insert into employee (name, birthday, email) values ('Farah', '1988-01-10', 'fklimschakf@jiathis.com');
insert into employee (name, birthday, email) values ('Lelia', '1968-05-09', 'lknowltong@netscape.com');
insert into employee (name, birthday, email) values ('Christabel', '1954-01-03', 'cnicklinsonh@google.com.hk');
insert into employee (name, birthday, email) values ('Seward', '1938-10-27', 'snajarai@shinystat.com');
insert into employee (name, birthday, email) values ('Lorne', '2002-10-25', 'lvauterj@pen.io');
insert into employee (name, birthday, email) values ('Benedetto', '1940-01-06', 'bdebankek@wordpress.org');
insert into employee (name, birthday, email) values ('Sidoney', '2019-05-07', 'sgiblingl@slate.com');
insert into employee (name, birthday, email) values ('Rosaleen', '1969-08-04', 'rcolthurstm@bizjournals.com');
insert into employee (name, birthday, email) values ('Tracie', '2012-08-21', 'tnewsteadn@nbcnews.com');
insert into employee (name, birthday, email) values ('Darby', '1969-06-07', 'dpernello@ifeng.com');
insert into employee (name, birthday, email) values ('Maddi', '1924-10-01', 'mpinarep@foxnews.com');
insert into employee (name, birthday, email) values ('Colby', '1979-08-03', 'cmegaheyq@usgs.gov');
insert into employee (name, birthday, email) values ('Sile', '1935-12-01', 'sbellr@biglobe.ne.jp');
insert into employee (name, birthday, email) values ('Flory', '1949-03-30', 'fdymotts@gravatar.com');
insert into employee (name, birthday, email) values ('Millie', '1939-02-24', 'mwoollonst@fc2.com');
insert into employee (name, birthday, email) values ('Terri-jo', '1988-11-17', 'twitherspoonu@shutterfly.com');
insert into employee (name, birthday, email) values ('Linnet', '1973-11-04', 'ljuschkev@constantcontact.com');
insert into employee (name, birthday, email) values ('Christian', '1941-08-01', 'carnottw@delicious.com');
insert into employee (name, birthday, email) values ('Nicolais', '1978-02-27', 'nresunx@is.gd');
insert into employee (name, birthday, email) values ('Annaliese', '2000-11-27', 'avanniy@instagram.com');
insert into employee (name, birthday, email) values ('Katey', '1960-11-16', 'kferberz@blogspot.com');
insert into employee (name, birthday, email) values ('Pall', '1938-04-20', 'pvanrembrandt10@ucoz.ru');
insert into employee (name, birthday, email) values ('Ami', '1933-04-09', 'asoutherns11@arstechnica.com');
insert into employee (name, birthday, email) values ('Dalt', '1957-11-28', 'dgaw12@marketwatch.com');
insert into employee (name, birthday, email) values ('Meredith', '1967-12-09', 'mmacgraith13@time.com');
insert into employee (name, birthday, email) values ('Shari', '1940-03-30', 'szarb14@apple.com');
insert into employee (name, birthday, email) values ('Locke', '1955-05-09', 'lgander15@pagesperso-orange.fr');
insert into employee (name, birthday, email) values ('Dicky', '2006-02-20', 'dthirkettle16@ca.gov');
insert into employee (name, birthday, email) values ('Guglielma', '1935-07-08', 'gselvester17@loc.gov');
insert into employee (name, birthday, email) values ('Kori', '2010-11-22', 'kcarpe18@ifeng.com');
insert into employee (name, birthday, email) values ('Luis', '1994-03-30', 'lonians19@forbes.com');
insert into employee (name, birthday, email) values ('Herschel', '1926-06-30', 'hodell1a@tuttocitta.it');
insert into employee (name, birthday, email) values ('Ernestus', '1953-12-03', 'ebardell1b@nbcnews.com');
insert into employee (name, birthday, email) values ('Eloisa', '2020-07-30', 'ewinchurch1c@hao123.com');
insert into employee (name, birthday, email) values ('Zuzana', '1950-11-17', 'zschulz1d@washingtonpost.com');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.<br>
```
UPDATE employee 
SET name = 'Hande',
    birthday = '1999-05-09',
    email = 'hande@gmail.com'
WHERE id = 1

UPDATE employee 
SET name = 'Sevda',
    birthday = '1999-05-09',
    email = 'sevda@gmail.com'
WHERE id = 2

UPDATE employee 
SET name = 'Ali',
    birthday = '1999-05-09',
    email = 'ali@gmail.com'
WHERE id = 3

UPDATE employee 
SET name = 'veysi',
    birthday = '1999-05-09',
    email = 'veysi@gmail.com'
WHERE id = 4

UPDATE employee 
SET name = 'Marla',
    birthday = '1999-05-09',
    email = 'marla@gmail.com'
WHERE id = 5
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.<br>
```
DELETE FROM employee
WHERE id IN(10,20,30,40,50);
```
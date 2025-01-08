# SQL (Create Table / Insert Into / Update / Delete Commands) 📋
## 📌Ilk olarak employee isimli sütun bilgileri employee_id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım;
```
CREATE TABLE employee(
employee_id INT PRIMARY KEY AUTO_INCREMENT,
name VARCHAR(50),
birthday DATE,
email VARCHAR(100))
```
## 📌Daha sonra Mockaroo servisini kullanarak olusturdugumuz tabloya 50 adet veri girisi yapalim;
```
insert into employee (name, birthday, email) values ('Ritchie Usher', '1995-02-19', 'rusher0@un.org');
insert into employee (name, birthday, email) values ('Bess Saward', '1981-05-15', 'bsaward1@archive.org');
insert into employee (name, birthday, email) values ('Crichton Bruin', '1981-08-05', 'cbruin2@cdc.gov');
insert into employee (name, birthday, email) values ('Gard Shenfisch', '1980-07-01', 'gshenfisch3@wikimedia.org');
insert into employee (name, birthday, email) values ('Evania Olyfat', '1990-04-20', 'eolyfat4@apache.org');
insert into employee (name, birthday, email) values ('Tobe Lindemann', '1988-03-08', 'tlindemann5@yelp.com');
insert into employee (name, birthday, email) values ('Thatch Mazzeo', '1998-07-03', 'tmazzeo6@dell.com');
insert into employee (name, birthday, email) values ('Filberto Jagels', '1995-12-06', 'fjagels7@zdnet.com');
insert into employee (name, birthday, email) values ('Pamela Saltwell', '2000-07-08', 'psaltwell8@baidu.com');
insert into employee (name, birthday, email) values ('Colas Gierok', '1984-12-14', 'cgierok9@goodreads.com');
insert into employee (name, birthday, email) values ('Mala Roggerone', '1983-03-01', 'mroggeronea@netvibes.com');
insert into employee (name, birthday, email) values ('Ceciley Sivior', '1985-01-22', 'csiviorb@chicagotribune.com');
insert into employee (name, birthday, email) values ('Emlyn Bradder', '1981-05-18', 'ebradderc@vimeo.com');
insert into employee (name, birthday, email) values ('La verne Rodman', '1986-02-07', 'lverned@jigsy.com');
insert into employee (name, birthday, email) values ('Tabbatha Spooner', '1990-08-07', 'tspoonere@about.me');
insert into employee (name, birthday, email) values ('Elaina Brise', '1984-07-02', 'ebrisef@fastcompany.com');
insert into employee (name, birthday, email) values ('Nero Godspeede', '1996-10-20', 'ngodspeedeg@whitehouse.gov');
insert into employee (name, birthday, email) values ('Kellia Stedman', '1980-05-04', 'kstedmanh@technorati.com');
insert into employee (name, birthday, email) values ('Marsiella Prendiville', '1998-04-12', 'mprendivillei@simplemachines.org');
insert into employee (name, birthday, email) values ('Seth McKea', '1987-05-12', 'smckeaj@hp.com');
insert into employee (name, birthday, email) values ('Ferris Paradin', '1981-05-26', 'fparadink@slate.com');
insert into employee (name, birthday, email) values ('Elvira Valentin', '1997-11-03', 'evalentinl@google.com.br');
insert into employee (name, birthday, email) values ('Sorcha Curman', '1981-12-24', 'scurmanm@plala.or.jp');
insert into employee (name, birthday, email) values ('Faye Janz', '1999-11-28', 'fjanzn@house.gov');
insert into employee (name, birthday, email) values ('Danice Keyzor', '1993-01-31', 'dkeyzoro@mysql.com');
insert into employee (name, birthday, email) values ('Conny Nattriss', '1984-01-02', 'cnattrissp@elegantthemes.com');
insert into employee (name, birthday, email) values ('Niccolo Blewis', '1989-12-03', 'nblewisq@phoca.cz');
insert into employee (name, birthday, email) values ('Veronica Eingerfield', '1998-06-02', 'veingerfieldr@sbwire.com');
insert into employee (name, birthday, email) values ('Bethanne Emmer', '1999-06-07', 'bemmers@163.com');
insert into employee (name, birthday, email) values ('Callean McMorland', '1998-03-16', 'cmcmorlandt@ow.ly');
insert into employee (name, birthday, email) values ('Merrick Santus', '1988-02-10', 'msantusu@privacy.gov.au');
insert into employee (name, birthday, email) values ('Jane Dennant', '1983-09-11', 'jdennantv@xrea.com');
insert into employee (name, birthday, email) values ('Alleen McBeith', '1988-09-20', 'amcbeithw@goo.ne.jp');
insert into employee (name, birthday, email) values ('Rob Reddle', '1989-11-27', 'rreddlex@washington.edu');
insert into employee (name, birthday, email) values ('Rakel Tye', '1982-08-16', 'rtyey@networkadvertising.org');
insert into employee (name, birthday, email) values ('Ettie Tussaine', '1988-09-08', 'etussainez@diigo.com');
insert into employee (name, birthday, email) values ('Chery Garbutt', '1982-07-18', 'cgarbutt10@blogs.com');
insert into employee (name, birthday, email) values ('Wernher Mouse', '1982-11-07', 'wmouse11@chronoengine.com');
insert into employee (name, birthday, email) values ('Mickey Melling', '1983-04-03', 'mmelling12@wsj.com');
insert into employee (name, birthday, email) values ('Gert Ceci', '1986-01-16', 'gceci13@bigcartel.com');
insert into employee (name, birthday, email) values ('Judah Hazeldean', '1995-11-11', 'jhazeldean14@stumbleupon.com');
insert into employee (name, birthday, email) values ('Federico Blabie', '1997-02-14', 'fblabie15@auda.org.au');
insert into employee (name, birthday, email) values ('Gisella Hartles', '1987-04-29', 'ghartles16@abc.net.au');
insert into employee (name, birthday, email) values ('Ezechiel Ditt', '1988-12-24', 'editt17@vimeo.com');
insert into employee (name, birthday, email) values ('Ivonne Dumbreck', '1986-05-07', 'idumbreck18@ihg.com');
insert into employee (name, birthday, email) values ('Rodolphe Francombe', '1986-07-18', 'rfrancombe19@tinyurl.com');
insert into employee (name, birthday, email) values ('Abigail McNelis', '1992-08-04', 'amcnelis1a@blogspot.com');
insert into employee (name, birthday, email) values ('Reeba Boydell', '1997-06-12', 'rboydell1b@nps.gov');
insert into employee (name, birthday, email) values ('Dot Hunnicot', '1980-02-19', 'dhunnicot1c@globo.com');
insert into employee (name, birthday, email) values ('Sayer O''Nowlan', '1993-01-23', 'sonowlan1d@illinois.edu');
```
## 📌Simdi olusturdugumuz tabloda sutunlarin her birine gore diger sutunlari guncelleyecek 5 UPDATE islemi yapalim
### employee_id'si 5 ten kucuk olanlarin name bilgisini "New Name" olarak gunceller:
```
UPDATE employee 
SET name="New Name"
WHERE employee_id < 5
```
### name bilgisi "New Name" olanlarin birthday'ini "1999-03-12" olarak gunceller:
```
UPDATE employee
SET birthday="1999-03-12"
WHERE name = "New Name"
```
### birthday tarihi "1999-01-01" dan buyuk olanlarin emailini'ini "gg@sql.com" olarak gunceller:
```
UPDATE employee 
SET email="gg@sql.com"
WHERE birthday  > "1999-01-01"
```
### emaili "gg@sql.com"  olanlarin name bilgisini "SQL Name" olarak gunceller:
```
UPDATE employee
SET name="SQL Name"
WHERE email="gg@sql.com";
```
### name'i G harfi ile baslayanlarin  name bilgisini "New New Name" olarak gunceller:
```
UPDATE employee
SET name="New New Name"
WHERE name LIKE "G%";
```

## 📌Simdi de sutunlarin her birine gore ilgili satiri silecek 5 DELETE islemi yapalim
### name'i "Dot Hunnicot" olan satiri siler
```
DELETE FROM employee
WHERE name = "Dot Hunnicot"
```
### id'si "3" olan satiri siler
```
DELETE FROM employee
WHERE id = 3
```
### birthday'i "1990-04-20" olan satiri siler
```
DELETE FROM employee
WHERE birthday="1990-04-20"
```
### email'i "ebrisef@fastcompany.com" olan satiri siler
```
DELETE FROM employee
WHERE email="ebrisef@fastcompany.com";
```
### name'i e harfiyle biten satirlari siler
```
DELETE FROM employee
WHERE name LIKE "%e";
```

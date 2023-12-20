Soru 1 Cevap :
create table employee (
	id serial primary key,
	name varchar(50),
	email varchar(100),
	birthday date); <br>
 Soru 2 Cevap :
insert into employee (name, email, birthday) values ('Ceil', 'cgarrould0@webnode.com', '2007-11-09');
insert into employee (name, email, birthday) values ('Kym', 'kerickssen1@plala.or.jp', '1998-01-30');
insert into employee (name, email, birthday) values ('Wallace', 'wpenella2@odnoklassniki.ru', '1971-08-17');
insert into employee (name, email, birthday) values ('Saleem', 'smabbutt3@mysql.com', '1943-12-24');
insert into employee (name, email, birthday) values ('Norbie', 'nodocherty4@addtoany.com', '2013-01-02');
insert into employee (name, email, birthday) values ('Fernanda', 'fyearnes5@techcrunch.com', '1956-09-05');
insert into employee (name, email, birthday) values ('Gustav', 'gsmeath6@gizmodo.com', '1991-07-09');
insert into employee (name, email, birthday) values ('Fonzie', 'fanstiss7@reuters.com', '1903-12-31');
insert into employee (name, email, birthday) values ('Deerdre', 'dtrench8@aboutads.info', '1916-07-15');
insert into employee (name, email, birthday) values ('Louie', 'limos9@chronoengine.com', '1959-02-12');
insert into employee (name, email, birthday) values ('Warren', 'wmorana@quantcast.com', '1925-07-30');
insert into employee (name, email, birthday) values ('Neila', 'nfellmanb@hugedomains.com', '1988-08-10');
insert into employee (name, email, birthday) values ('Rodrigo', 'rmabsonc@dot.gov', '2001-11-01');
insert into employee (name, email, birthday) values ('Gerri', 'gbeavond@wp.com', '2001-11-03');
insert into employee (name, email, birthday) values ('Wilmar', 'wfoxalle@wikia.com', '2008-05-16');
insert into employee (name, email, birthday) values ('Kizzee', 'kreymersf@japanpost.jp', '1948-03-17');
insert into employee (name, email, birthday) values ('Lynne', 'lcollomosseg@wordpress.com', '1913-06-07');
insert into employee (name, email, birthday) values ('Mattie', 'mwestmacotth@facebook.com', '2007-08-25');
insert into employee (name, email, birthday) values ('Concettina', 'cmanstoni@wunderground.com', '1921-11-03');
insert into employee (name, email, birthday) values ('Koo', 'khaugj@thetimes.co.uk', '1916-02-14');
insert into employee (name, email, birthday) values ('Nona', 'nleathemk@about.me', '1946-01-14');
insert into employee (name, email, birthday) values ('Jacques', 'jpunshonl@blogger.com', '1940-03-06');
insert into employee (name, email, birthday) values ('Lacee', 'lcauderliem@cyberchimps.com', '1969-10-24');
insert into employee (name, email, birthday) values ('Kara-lynn', 'kbalaamn@ycombinator.com', '1997-10-14');
insert into employee (name, email, birthday) values ('Justis', 'jsmithero@cpanel.net', '2021-09-30');
insert into employee (name, email, birthday) values ('Godiva', 'gboyetp@oracle.com', '1906-01-20');
insert into employee (name, email, birthday) values ('Kaia', 'klichfieldq@is.gd', '1952-12-27');
insert into employee (name, email, birthday) values ('Carlene', 'cabdenr@cnn.com', '1944-11-21');
insert into employee (name, email, birthday) values ('Brittan', 'bbeagins@chron.com', '1959-02-26');
insert into employee (name, email, birthday) values ('Svend', 'smackimmiet@washingtonpost.com', '1929-09-25');
insert into employee (name, email, birthday) values ('Blair', 'bwoodcocku@samsung.com', '1928-05-21');
insert into employee (name, email, birthday) values ('Kalli', 'kcowchav@netscape.com', '1978-10-18');
insert into employee (name, email, birthday) values ('Dierdre', 'dhastlerw@spiegel.de', '1947-02-24');
insert into employee (name, email, birthday) values ('Mildrid', 'mhartnessx@free.fr', '2013-06-10');
insert into employee (name, email, birthday) values ('Shurlocke', 'smassiey@parallels.com', '1911-01-21');
insert into employee (name, email, birthday) values ('Nina', 'ncookesz@msn.com', '2012-12-15');
insert into employee (name, email, birthday) values ('Lorinda', 'lgilfether10@topsy.com', '1981-03-27');
insert into employee (name, email, birthday) values ('Carmita', 'cleftbridge11@state.gov', '1984-01-18');
insert into employee (name, email, birthday) values ('Emera', 'esasser12@ca.gov', '1991-12-08');
insert into employee (name, email, birthday) values ('Brandon', 'bphillipson13@forbes.com', '1921-10-16');
insert into employee (name, email, birthday) values ('Jodi', 'jcamerana14@ezinearticles.com', '1982-12-27');
insert into employee (name, email, birthday) values ('Ulric', 'umapham15@arstechnica.com', '1976-07-07');
insert into employee (name, email, birthday) values ('Rooney', 'roshesnan16@guardian.co.uk', '1984-05-10');
insert into employee (name, email, birthday) values ('Merl', 'msphinxe17@kickstarter.com', '2023-02-15');
insert into employee (name, email, birthday) values ('Lewiss', 'lbowlesworth18@theatlantic.com', '1909-05-27');
insert into employee (name, email, birthday) values ('Fay', 'fdomerq19@weather.com', '1945-02-09');
insert into employee (name, email, birthday) values ('Erv', 'ecoulling1a@zimbio.com', '1976-11-04');
insert into employee (name, email, birthday) values ('Wini', 'wrakestraw1b@youku.com', '2022-04-13');
insert into employee (name, email, birthday) values ('Nerty', 'nklewer1c@istockphoto.com', '1938-01-11');
insert into employee (name, email, birthday) values ('Mercie', 'mdalgarno1d@virginia.edu', '1911-09-09'); <br>
Soru 3 Cevap : <br>
1.Değişiklik :
update employee
set name='Eren'
where id=10; <br>
2.Değişiklik :
update employee
set birthday='2008-08-10'
where birthday='2007-11-09'
returning * <br>
3.Değişiklik :
update employee
set email='eren@basaran.com'
where id=1
returning * <br>
4.Değişiklik :
update employee
set name='Eren'
where id=1
returning * <br>
5.Değişiklik :
update employee
set birthday='1999-10-01'
where birthday='2008-08-10'
returning * <br>
Soru 3 Cevap : <br>
1.Değişiklik :
delete from employee
where id>45
returning * <br>
2.Değişiklik :
delete from employee
where name like 'W%'
returning * <br>
3.Değişiklik :
delete from employee
where birthday > '2023-01-01'
returning * <br>
4.Değişiklik :
delete from employee
where id=5
returning * <br>
5.Değişiklik :
delete from employee
where name like 'B____'
returning * <br>

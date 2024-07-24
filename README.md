### Links úteis

- [Kafka Control Center](http://localhost:9021/)
- [Mongo Express](http://localhost:8085/)

# Instructions
docker compose up -d
docker compose exec -it mysql bash
mysql -uroot -p fullcycle
create table categories (id int auto_increment primary key, name varchar(255));
insert into categories (name) values ('Eletronicos');
select * from categories;


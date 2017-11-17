# Exercicio2DM110
Java EE, entity JPA, serviço REST, session beans


Banco de Dados:

CREATE DATABASE "Clients";

create table dataClients (
id serial not null,
nameClient varchar(50) not null,
emailClient varchar(50) not null,
);
create sequence seq_clients;
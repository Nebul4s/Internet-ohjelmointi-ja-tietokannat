# Internet-ohjelmointi-ja-tietokannat

use rasti;

CREATE TABLE book(
id_book INT primary key auto_increment,
name VARCHAR(255),
author VARCHAR(255),
isbn VARCHAR(20)
);

CREATE TABLE user(
  id_user INT primary key auto_increment,
  username VARCHAR(20),
  password VARCHAR(255),
  UNIQUE (username)
);

CREATE TABLE car(
id_car INT primary key auto_increment,
brand VARCHAR(255),
model VARCHAR(255)
);
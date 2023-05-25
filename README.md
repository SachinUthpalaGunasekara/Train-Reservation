# Train-Reservation
This Project Created Using Java and MYSQL. 

The SQL code will be provide by this.


CREATE TABLE `web_projects`.`user` (
  `idusers` INT NULL AUTO_INCREMENT,
  `uname` VARCHAR(45) NULL,
  `uemail` VARCHAR(45) NULL,
  `upassword` VARCHAR(45) NULL,
  PRIMARY KEY (`idusers`));

use railway;
  
  create table user_reservation(
  Rid int not null AUTO_INCREMENT PRIMARY KEY,
  Rname varchar(20) not null,
  Remail varchar(30) not null,
  Rphone varchar(10) not null,
  Rpax varchar(19) not null,
  Rfrom varchar(30) not null,
  Rto varchar(20)
  
  
  );

use railway;

create table trains(
 tid int primary key auto_increment not null,
tnameuser_reservation varchar(20) not null,
t_from varchar(20),
t_to varchar(20),
price varchar(20)
);

create table Admins(
 adi int primary key  auto_increment,
 anme varchar(29),
 apassword varchar(20)
);

insert into Admins(anme ,apassword ) values ("Admin" , "Admin");

use railway;

select * from user_s
elect * from trains;reservation;

select * from admins;
select * from users;

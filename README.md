# SuperMarket
 
Plz install netbeans 8.2
Mysql Server is required
download the jdbc connector 5 as well
also run the following commands in mysql server
create database supermarket;
use supermarket;
create table product
(
   product_id varchar(100),
   product_name varchar(100),
   product_category varchar(50),
   cutted_price double,
   show_price double,
   stock int,
   re_order_value int,
   image varchar(50),
   description varchar(100),
   star_value int,
   offer int
);

create table shipping
(
   userid varchar(100),
   usrname varchar(50),
   address1 varchar(200),
   address2 varchar(200),
   city varchar(50),
   state varchar(50),
   country varchar(50),
   postalCode varchar(50),
   email varchar(50)
);

create table billing
(
   nameOnCard varchar(100),
   creditCardType varchar(50),
   creditCardNumber varchar(50),
   creditCardExpiration varchar(50)
)

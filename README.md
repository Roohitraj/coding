CREATE TABLE admin_master(
id int(11),
username varchar(100),
password varchar(100),
);

CREATE TABLE category_master(
id int(11),
category_name varchar(100)
);

CREATE TABLE product master(
id  int (11),
category_id(100),
product_sku(100),
product_price(100),
product_image(200),
);

# Simple-Wishlist
Simple Wishlist base on HTML and using Mariadb as database

CREATE DATABASE wishlist;
USE wishlist;
CREATE TABLE wishlist (
    id INT AUTO_INCREMENT PRIMARY KEY,
    item VARCHAR(255) NOT NULL,
    completed BOOLEAN DEFAULT FALSE
);

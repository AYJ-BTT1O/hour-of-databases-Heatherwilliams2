# SQL-Project

CREATE TABLE Clothing_for_Kids(id INTEGER PRIMARY KEY, name TEXT, quantity INTEGER, aisle INTEGER, price INTEGER);
INSERT INTO Clothing_for_Kids VALUES (1, "Baseball Hat", 16, 7, 9.99);
INSERT INTO Clothing_for_Kids VALUES(2, "Jeans", 20, 2, 20.00);
INSERT INTO Clothing_for_Kids VALUES(3, "Hoodies", 9, 13, 15.99);
INSERT INTO Clothing_for_Kids VALUES(4, "Long Sleeve Shirts", 10, 12, 17.99);
INSERT INTO Clothing_for_Kids VALUES(5, "Leggings", 8, 2, 13.99);
INSERT INTO Clothing_for_Kids  VALUES(6, "T-Shirts", 10, 12, 17.99);
INSERT INTO Clothing_for_Kids VALUES(7, "Dresses", 20, 5, 53.00);
INSERT INTO Clothing_for_Kids VALUES(8, "Suits", 20, 10, 50.00);
INSERT INTO Clothing_for_Kids VALUES(9, "Bathing Suits", 10, 14, 17.99);
INSERT INTO Clothing_for_Kids VALUES(10, "Running Shoes", 20, 11, 33.99);
INSERT INTO Clothing_for_Kids  VALUES(11, "Pjamas", 5, 4, 15.00);
INSERT INTO Clothing_for_Kids VALUES(12, "Dress Shoes", 20,11, 43.99);
INSERT INTO Clothing_for_Kids  VALUES(13, "Sun Hat", 5, 7, 9.99);
INSERT INTO Clothing_for_Kids VALUES(14, "Cardigain", 10,13, 17.00);
INSERT INTO Clothing_for_Kids VALUES(15, "Socks", 20,8, 5.99);
INSERT INTO Clothing_for_Kids VALUES(16, "Tanktops",10,12,15.00);


SELECT * FROM Clothing_for_Kids;

 SELECT * FROM Clothing_for_Kids WHERE price > 5 ORDER BY price; 
 
 SELECT * FROM Clothing_for_Kids WHERE aisle > 5 ORDER BY aisle;

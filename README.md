# carshowroom
The provided code is a simple Java program that serves as a basic Showroom Management System. It includes three classes: Showroom, Employees, and Cars, all of which implement the utility interface. The program allows users to add and retrieve information about showrooms, employees, and cars.

Showroom Class:

Manages details about showrooms such as name, address, manager name, total employees, and total cars in stock.
Implements the utility interface for common methods (get_details and set_details).
Employees Class:

Manages details about employees, including an automatically generated employee ID using UUID.
Implements the utility interface for common methods (get_details and set_details).
Cars Class:

Manages details about cars, including name, color, fuel type, price, type, and transmission.
Implements the utility interface for common methods (get_details and set_details).
Main Class:

The Main class acts as the driver class.
It provides a main menu to add or retrieve information about showrooms, employees, and cars.
Utilizes arrays to store instances of showrooms, employees, and cars.
The program uses a loop to continuously display the main menu until the user chooses to exit (choice = 0).

# food_management_system
A DSA based Java project implementing management system from user and admin end.
The project is a food management system which includes various attributes accessible from two ends . 
The project is a two-way ended system namely : 1- User end 2- Admin end 
The project brief is as follows : 
User-End: 
1- The program as seen from the user end gives three options namely : 1-cafe 
2-restro 
3-dessert 
to select from in order to add dishes to your respective order list. 
2- Each option has its own menu and functionality in order to proceed further hence the user is required to select an option to order. 3- The respective order-list of a customer is stored in the admin entity of that particular hotel base. 
4- Once the option is selected it asks for the details of the user like name and contact number to proceed further. 
5-An invalid contact number asks you to re-enter your contact number. 6-Once the customer details are entered and stored in the system it displays the menu of the respective restaurant selected.
7-The user enters the order which gets stored and once the complete order is given 0 is pressed for final processing of the order. 8- Once the final processing is done the bill invoice is generated with the customer details and the order along with the final bill amount applied with tax slabs . 
9- The user is then asked whether to continue or to exit the application. 
10- If the continue is taken into consideration the user can order from other hotels as well . 
Admin-End: 
1- The program as seen from the admin end asks to enter the hotel name . 
2- The admin has access to a queue for enqueue and dequeue operations for the order-list of customers as well as a linked list acting as a hotel database for storing all the given orders . 
2- Then the security code of the hotel is asked to prevent unethical access. 
3-As soon as the correct code is entered the access is granted and gives the following options to select from: 0-Logout 
1-Update menu 
2- Add menu 
3-Deliver and view orders 
4-View all orders to be 
delivered 
5-View all orders received 
6-View total income 
7-Delete 
4-Update menu gives you an option to update the price , time or both of the dishes already present in the menu.
5-Add new menu gives you access to add new dishes in the menu with the time and price . 
6-Deliver and view order details shows you the last order delivered with the customer details and the order details. 
It also asks for a rating and feedback for improvement so that the implementation can be improved. 
7-View all orders to be delivered displays the remaining orders in the queue to be delivered. 
8-View all orders received displays all the orders received in the particular end along with customer details and the order details . 9- View total income displays the total income earned . 10- Delete option is used by the admin to delete any particular existing dish from the respective restaurant menu. 
11-To exit the admin end we need to enter 0. 
OBJECT ORIENTED PRINCIPLES: 
1- The objects of all three hotel types are created in main and then used for implementation of the functionality. 2-The admin of each hotel is different and is implemented using admin object which is the base of object-oriented programming. 
3-The principle of inheritance is used as hotel class properties are inherited by all hotel types in their respective classes so as to reduce lines of code and implement the true sense of object-oriented programming. 
4-The principle of encapsulation is also used to hide the working and to store the code in classes for ease of understanding.
4-List all data structures used and justify why did you select these data structures. 
ANS—DATA STRUCTURES USED: 
1-PRIORITY QUEUE : It is an abstract data type that is similar to a queue, and every element has some priority value associated with it. The priority of the elements in a priority queue determines the order in which elements are served (i.e., the order in which they are removed). If in any case the elements have same priority, they are served as per their ordering in the queue. 
It is used at the admin end to enqueue and dequeue orders and the priority is set according to the time required for preparation of the dish ordered that is the dish prepared faster will be dequeued earlier . 
2-BINARY SEARCH TREE : It is a non-linear tree data structure where left subtree has values less than parent node and right subtree has values greater than parent node. The hotel menu is stored in binary search tree alphabetically and search is performed and recursive inorder is used to display as it has efficient time complexity. 
3-LINKED LIST : 
A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations.
Linked list is storing customer details and other linked list stores order details and this linked list is stored in the other linked list. 
Linked list of order details is stored in priority queue at the admin end for the dequeue operation to be performed.

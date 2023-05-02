## SQL Training - Course-end Project
### Description
<p> Air Cargo is an aviation company that provides air transportation services for passengers and freight. Air Cargo uses its aircraft to provide different services with the help of partnerships or alliances with other airlines. The company wants to prepare reports on regular passengers, busiest routes, ticket sales details, and other scenarios to improve the ease of travel and booking for customers.
 
### Project Objective:
<p> You, as a DBA expert, need to focus on identifying the regular customers to provide offers, analyze the busiest route which helps to increase the number of aircraft required and prepare an analysis to determine the ticket sales details. This will ensure that the company improves its operability and becomes more customer-centric and a favorable choice for air travel. 
<p> Following operations should be performed: <p>

- Task 1: Create an ER diagram for the given airlines database.
- Task 2: Write a query to create a route_details table using suitable data types for the fields, such as route_id, flight_num, origin_airport, destination_airport, aircraft_id, and distance_miles. Implement the check constraint for the flight number and unique constraint for the route_id fields. Also, make sure that the distance miles field is greater than 0.
- Task 3:  Write a query to display all the passengers (customers) who have traveled in routes 01 to 25. Take data  from the passengers_on_flights table.
- Task 4: Write a query to identify the number of passengers and total revenue in business class from the ticket_details table.
- Task 5: Write a query to display the full name of the customer by extracting the first name and last name from the customer table.
- Task 6: Write a query to extract the customers who have registered and booked a ticket. Use data from the customer and ticket_details tables.
- Task 7: Write a query to identify the customer’s first name and last name based on their customer ID and brand(Emirates) from the ticket_details table.
- Task 8: Write a query to identify the customers who have traveled by Economy Plus class using Group By and Having clause on the passengers_on_flights table.
- Task 9: Write a query to identify whether the revenue has crossed 10000 using the IF clause on the ticket_details table.
- Task 10: Write a query to create and grant access to a new user to perform operations on a database.	13
- Task 11: Write a query to find the maximum ticket price for each class using window functions on the ticket_details table.
- Task 12: Write a query to extract the passengers whose route ID is 4 by improving the speed and performance of the passengers_on_flights table.
- Task 13:  For the route ID 4, write a query to view the execution plan of the passengers_on_flights table.
- Task 14: Write a query to calculate the total price of all tickets booked by a customer across different aircraft IDs using rollup function.
- Task 15: Write a query to create a view with only business class customers along with the brand of airlines.
- Task 16: Write a query to get the details of all passengers flying between a range of routes defined in run time.
- Task 17: Write a query to extract all the details from the routes table where the traveled distance is more than 2000 miles.
- Task 18: Write a query to create groups for the distance traveled by each flight into three categories. The categories are, short distance travel (SDT) for >=0 AND <= 2000 miles, intermediate distance travel (IDT) for >2000 AND <=6500, and long-distance travel (LDT) for >6500.
- Task 19: Write a query to extract ticket purchase date, customer ID, class ID and specify if the complimentary services are provided for the specific class on the ticket_details table. If the class is Business and Economy Plus, then complimentary services are given as Yes, else it is No
- Task: 20: Write a query to extract the first record of the customer whose last name ends with Scott using a cursor from the customer table.

### Datasets required for project: [Airlines_datasets.zip](https://github.com/Anushreebh/Air-Cargo-Analysis/files/11375449/Airlines_datasets.zip)

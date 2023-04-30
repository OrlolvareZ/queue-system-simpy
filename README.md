# Simulating a queue system with SimPy

This is a Jupyter notebook containing the solution for a prompt given in the Simulation course.

In order to fulfill the simulation, I used SimPy, a Python package por simulating processes, which allows you to define proccesses, events, resources and more.

## The formulation

A self-service store normally has 3 servers operating, from 7:00 am to 22:00 pm, with an average total service capacity that follows a Poisson distribution of λ = 15 customers per hour. Customers arrive at this store according to a Poisson distribution with mean λ of 12 customers per hour. Simulate the operation for 1 day of service and determine the following:

a) Total number of customers served in the day.
b) Average waiting time per customer
c) Average idle time per server
d) Maximum waiting time for one customer
e) Minimum waiting time of a customer
f) Effective time worked per server
g) Based on the results obtained, what is your recommendation regarding the number of cash registers: shall the number of servers be maintained, increased or decreased?
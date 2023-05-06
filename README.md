# Simulating a queue system with SimPy

This is a Jupyter notebook containing the solution for a prompt given in the Simulation course.

In order to fulfill the simulation, I used SimPy, a Python package por simulating processes, which allows you to define proccesses, events, resources and more.

### En español

Si quieres examinar el programa en español, abre el archivo sim_sistema_colas.ipynb, en lugar de queue_system.ipynb.

## The formulation

A self-service store normally has 3 servers operating, from 7:00 am to 22:00 pm, with an average total service capacity that follows a Poisson distribution of λ = 15 customers per hour. Customers arrive at this store according to a Poisson distribution with mean λ of 12 customers per hour. Simulate the operation for 1 day of service and determine the following:

1. Total number of customers served in the day.
2. Average waiting time per customer
3. Average idle time per server
4. Maximum waiting time for one customer
5. Minimum waiting time of a customer
6. Effective time worked per server
7. Based on the results obtained, what is your recommendation regarding the number of cash registers: shall the number of servers be maintained, increased or decreased?

## Get started!

```
    # To get the repo
    git clone https://github.com/OrlolvareZ/queue-system-simpy.git
```
```
    # To get numpy and simpy, if you don't already have them
    pip install -r requirements.txt
```

## Contributing

If you want to contribute to this project, install the `nbdev` package, that makes merging .ipynb files easier (by installing git hooks that only send changes regarding cell code).

```
    pip install nbdev2
    # and, in your repo folder:
    nbdev_install_hooks
```

See more about the package [here](https://nbdev.fast.ai/tutorials/git_friendly_jupyter.html).
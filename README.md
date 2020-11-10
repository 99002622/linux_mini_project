# linux_mini_project


![C/C++ CI](https://github.com/99002622/Mini-Project/workflows/C/C++%20CI/badge.svg)


![Unit testing](https://github.com/99002622/Mini-Project/workflows/Unit%20testing/badge.svg)


![Valgrind](https://github.com/99002622/Mini-Project/workflows/Valgrind/badge.svg)

![cppcheck-action](https://github.com/99002622/Mini-Project/workflows/cppcheck-action/badge.svg)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/65a9c9c6e25f475fbcd418964981cbeb)](https://app.codacy.com/gh/99002622/linux_mini_project?utm_source=github.com&utm_medium=referral&utm_content=99002622/linux_mini_project&utm_campaign=Badge_Grade)


Burger Buddies Problem: Design, implement and test a solution for the IPC problem specified below. Suppose we have the following scenario:

Cooks, Cashiers, and Customers are each modeled as a thread.
Cashiers sleep until a customer is present.
A Customer approaching a cashier can start the order process.
A Customer cannot order until the cashier is ready.
Once the order is placed, a cashier has to get a burger from the rack.
If a burger is not available, a cashier must wait until one is made.
The cook will always make burgers and place them on the rack.
The cook will wait if the rack is full.
There are NO synchronization constraints for a cashier presenting food to the customer. Implement a (concurrent multi‐threaded) solution to solve the problem and test it thoroughly. Show output runs that illustrate the various possibilities of the set up. (BurgerBuddies.c → BBC)

Execute

Use the following command to run the code:

gcc BurgerBuddies.c -lpthread 

./a.out



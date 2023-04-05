# FHTW_BIC_MCSD_Assign2 Description:

Timer Task

The purpose of this task is to become familiar with the concept of interrupts as well as timers and become aware of the functional limitations due to certain implementations.

Task Description
Based on the STM32L Getting Started Project evaluate and add the following functionality:

Write a function _tim_timeout_blocking() that will return after a specified timeout time provided as parameter to the function in a suitable way. The function shall be implemented as a blocking function, i.e., the system shall be put into a sleep mode until the timeout time elapses.

Write a function _tim_timeout_nonblocking_with_callback() that will return after a specified timeout time provided as parameter to the function in a suitable way. The function shall be implemented as a non-blocking function, i.e., the function shall return immediately. After the timeout elapses a callback function provided via a function pointer argument shall be invoked.

Create an simple application in your main() function that tests these functions.

# Points:

10/10

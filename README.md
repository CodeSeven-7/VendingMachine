# VendingMachine
PHP Task

/* THE CONTENT OF THE TASK
 * Write a console application that simulates the operation of a vending machine.
 * Use the provided code.
 * 
 * OBJECTIVE
 * Your task is to implement the interfaces existing in it.
 * The app should work as shown below.
 * 
 * ASSUMPTIONS:
 * 1. The application is operated by entering money symbols (N, D, Q, DOLLAR) and actions
 * (GET-A, GET-B, GET-C, RETURN-MONEY).
 * 2. At the time of launch, the program creates one item of products: A, B and C.
 * 3. The starting balance of the slot machine is $ 0.
 * 4. The prices of the products are as follows:
 * A - $ 0.65
 * B – $ 1
 * C - $ 1.5
 * 5. The machine supports coins with the following denominations:
 * $ 0.05 (nickel),
 * $ 0.1 (dime),
 * $ 0.25 $ (quarter)
 * $ 1.00 (dollar)
 * 6. The interfaces cannot be modified.
 */

----- HOW IT SHOULD WORK -----

// Input: DOLLAR

// Current balance: 1.00 (DOLLAR)

// Input: GET-B

// B

// Input: Q

// Current balance: 0.25 (Q)

// Input: Q

// Current balance: 0.50 (Q, Q)

// Input: Q

// Current balance: 0.75 (Q, Q, Q)

// Input: Q

// Current balance: 1.00 (Q, Q, Q, Q)

// Input: GET-B

// Item not found. Please choose another item.

// Input: RETURN-MONEY

// Q, Q, Q, Q

// Input:

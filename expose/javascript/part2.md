## Expose Part 2
1. Prints 3, because i was declared using var it is able to be accessed outside the for loop
2. Prints 150, because discountedPrice was declared using var, so the last calculated discountedPrice is accessable outside of the for loop
3. Prints 150, because finalPrice is decalred with var and is also the rounded version of discountedPrice.
4. Returns [ 50, 100, 150 ], because the return statement prints the values in the discounted array.
5. Uncaught reference error, because i is declared with let inside the for loop, which doesnt allow i to be accessed outside of the for loop
6. Uncaught reference error, because discountedPrice is declared with let inside the for loop, which doesnt allow discountedPrice to be accessed outside of the for loop
7. Prints 150, because finalPrice was declared with let in the function, but not in the for loop so it can be accessed outside the for loop
8. Returns [ 50, 100, 150 ], because discounted was declared with let within the function, so return prints the values in the array.
9. Uncaught reference error, because i is declared with let inside the for loop, which doesnt allow i to be accessed outside of the for loop
10. Prints 3, because length was declared with const in the function, which allows the variable to be read within the funciton.
11. Returns [ 50, 100, 150 ], because the return statement prints the values in the discounted array and although discounted was declared as a const, because it is an array, it didnt get reassigned but rather had values pushed into its memory.
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. '32', since integers map to strings
    B. 1, '3' becomes number 3
    C. 3, since null equates to 0
    D. '3null', null maps to string
    E. 4, true equates to 1
    F. 0, both false and null equate to 0
    G. '3undefined', undefined maps to string
    H. NaN, subtraction by undefined results in NaN
14. A. true, string 2 becomes number 2
    B. false, string 2 is greater than string 12
    C. true, '2' coverts to number 2
    D. false, string 2 does not equal number 2
    E. false, true converts to 1
    F. true, boolean(2) equates to true
15. == is normal equality, which does type conversion for 0/false and 1/true, while === does not.
17. [2, 4, 6], the function pushes ther result of the function dosomething into the new array and returns it
19. 1
    4
    3
    2
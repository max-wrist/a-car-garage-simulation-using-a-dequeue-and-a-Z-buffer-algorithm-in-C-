/**
 * main function to run the car garage simulation using de-queue and Z-buffer algorithm.
 * 
 * The function provides an interface for the user to add and remove cars from the garage,
 * view the Z-buffer, and exit the program. The Z-buffer is used to keep track of the order
 * of cars in the garage, with the highest priority cars in front and the lower priority cars
 * in the back.
 * 
 * The function contains a while loop that continues to run until the user decides to exit the
 * program. The user is presented with four options:
 * 1. Add car to the garage
 * 2. Remove car from the garage
 * 3. View Z-buffer
 * 4. Exit
 * 
 * If the user selects option 1, they are prompted to enter the data for the car and the position
 * in the Z-buffer. The `enqueueAtRear` function is called to add the car to the garage, and the
 * `updateZBuffer` function is called to update the Z-buffer with the car's position.
 * 
 * If the user selects option 2, the `dequeueAtFront` function is called to remove a car from the
 * front of the garage. The user is then prompted to enter the position in the Z-buffer, and the
 * `removeFromZBuffer` function is called to remove the car's position from the Z-buffer.
 * 
 * If the user selects option 3, the contents of the Z-buffer are displayed on the screen.
 * 
 * If the user selects option 4, the program exits.
 * 
 * If the user selects an invalid option, an error message is displayed and the loop continues.
 * 
 * Returns 0 if the program exits successfully.
 */

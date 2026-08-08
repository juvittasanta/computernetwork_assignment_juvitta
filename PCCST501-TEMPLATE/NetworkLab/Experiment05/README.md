# Network Lab Experiment

## Aim
To implement five client–server applications using TCP sockets in C, demonstrating reliable communication between clients and servers through message exchange, arithmetic operations, string processing, array processing, and matrix analysis, including identifying matrix types and calculating the sum and trace.

## Commands Used
gcc server.c -o server
gcc client.c -o client
./server
./client

## Procedure
The server and client programs for each experiment are compiled using GCC and executed in separate terminals. The server creates a TCP socket, binds it to the respective port, and waits for a client connection. The client connects to the server and sends the required data. The server processes the received data by performing greeting communication, arithmetic calculations, string operations, array calculations, or matrix analysis depending on the experiment. The processed results are then sent back to the client and displayed.

## Output
The five experiments successfully produced the expected results: the client received “Hello Client” in Experiment 1; arithmetic results including sum, difference, product, and quotient were obtained in Experiment 2; string length, uppercase, and reverse were obtained in Experiment 3; sum, average, maximum, and minimum were calculated in Experiment 4; and the matrix type, sum of elements, and trace were determined in Experiment 5.

## Conclusion
The five client–server applications were successfully implemented using TCP sockets in C, demonstrating effective network communication and server-side processing of different types of data, including messages, integers, strings, arrays, and matrices.

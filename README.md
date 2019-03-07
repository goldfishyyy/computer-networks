**Socket Programming**

This application performs the same task as following with UDP and TCP:

1.  The client gets a set of integers and the length of the set as command line
    arguments

2.  The client sends the set of integers to the server

3.  The server computes the total, the highest number, the lowest number, and
    the mean(in float)

4.  The server sends back the result to the client

5.  The client receives the results and prints them out.

**Instruction about How to Use UDP Socket**

There are two python scripts for the UDP socket: UDP_Server.py and UDP_Client.py

-   If your IDE allows parallel run, run UDP_Server.py and UDP_Client.py
    concurrently. The order of which script to run first doesn’t matter.

-   If your IDE doesn’t support parallel run, use bash and type the following
    command:

>   python UDP_Server.py & UDP_Client.py

**Test Case 1: (Valid inputs)**

-   Input: length of set=3, set of interger=1,2,4

-   Expect output:

>   The total is 7

>   The minimum is 1

>   The maximum is 4

>   The average is 2.3333333

![](media/fd91bdd9ce2c9e803d779c72af11e8e5.png)

**Test Case 2: (Invalid length )**

-   input: length of set=0,1

-   Expect output:

>   Keep displaying prompts to ask the user to input a valid input until getting
>   one

![](media/158cfc4f1227ae1068b14613932e0a1a.png)

**Test Case 3: (Invalid numbers)**

-   Input: length of set=2, set of interger=1, 5.5

-   Expect output:

>   Keep displaying prompts to ask the user to input a valid input until getting
>   one

![](media/51c2afd410dc1b0b7104e86efda1221b.png)

**Test Case 4: (Invalid input type)**

-   input: length of set=five, intergers=two

-   Expect output:

>   Keep displaying prompts to ask the user to input a valid input until getting
>   one

![](media/8f29ddeb2e6de7889e32891243a5c7b7.png)

**Instruction about How to Use TCP Socket**

There are two python scripts for the TCP socket: TCP_Server.py and TCP_Client.py

-   If your IDE allows parallel run, run TCP_Server.py and TCP_Client.py
    concurrently.

>   NOTE: HAVE TO RUN TCP_Server.py FIRST, THEN RUN TCP_Client.py

-   If your IDE doesn’t support parallel run, use bash and type the following
    command:

>   python TCP_Server.py

>   Python TCP_Client.py

![](media/2ccfe7f0cfb327073efe7ee35aa33e06.png)

**Test Case 1: (Valid inputs)**

-   Input: length of set=3, set of interger=1,2,4

-   Expect output:

>   The total is 7

>   The minimum is 1

>   The maximum is 4

>   The average is 2.3333333

![](media/7ca0ac688f6150c96bc483320b46e68c.png)

**Test Case 2: (Invalid length )**

-   input: length of set=0,1

-   Expect output:

>   Keep displaying prompts to ask the user to input a valid input until getting
>   one

![](media/284426dd2688d2dec6cb406eb4b98b9d.png)

**Test Case 3: (Invalid numbers)**

-   Input: length of set=2, set of interger=3.3

-   Expect output:

>   Keep displaying prompts to ask the user to input a valid input until getting
>   one

![](media/e19b66464a8616a0ee8224c6173d800d.png)

**Test Case 4: (Invalid input type)**

-   input: length of set=five, intergers=two

-   Expect output:

>   Keep displaying prompts to ask the user to input a valid input until getting
>   one

![](media/1726f1e76cbf07fff61182d5630fb6d6.png)

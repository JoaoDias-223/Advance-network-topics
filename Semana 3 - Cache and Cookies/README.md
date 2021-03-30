# Cache and Cookies - Wireshark

## Table of Contents
* [Exercício 1](#exercise-1)
* [Exercício 2](#exercise-2)
* [Exercício 3](#exercise-3)

## Exercise 1

![ex1.1-6](Images\ex1,1-6.png)

1. HTTP Version

        HTTP/1.1

2. Languages 

        English (United States)
        Portuguese (Brazil)

3. Source and Destination's IP

        Mine: 10.0.0.103
        Server: 128.119.245.12

4. Server Code

        304 Not Modified

5. Last time modified

        Wed, 24 Mar 2021 05:59:01 GMT

6. Bytes sent to browser

        661 Bytes (5288 bits)

7. Header not in package

        None

## Exercise 2

1. Cache in the 1st Message

        No

2. Return of the server

        200 OK
        It returned an html page in the application layer because it wasthe first time accessing the site and it was not stored in browser1s cache

     ![ex2.2](Images\ex2,2.png)
     
![ex2.2](Images\ex2,3-4.png)

3. Last modified

        Thu, 25 Mar 2021 05:59:01 GMT

4. Second Server Code

        304 Not Modified
        The server doesn't return the content because it's already in stored in browser's cache


## Exercise 3

![ex3-1](Images\ex3,1-3.png)

1. GET Messages

        The browser sent 2 GET messages (Number 751 and 772)

2. Answer to the GETs
        
        The answer is in line 783

3. Code returned in anser
        
        304 Not Modified

4. TCP Protocols

        It was necessary 4 TCP segments to receive the HTML page response

   ![ex3-4](Images\ex3,4.png)
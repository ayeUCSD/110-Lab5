# Lab 5 Questions & Answers


## Q1: Recall the ThreadingWithThread and ThreadingNoThread implementations. Did you observe any  differences when running the two programs and clicking on the buttons? If you did, why do you think this happens?

> When running `ThreadlingNoThread`, I could not click the `color` button for 5 seconds after clicking on the `calculate` button. With `ThreadlingWithThread` I was able to click `color` after clicking `calculate`. We think this happens because with no threads, the program must halts on `calculate` for 5 seconds before it can process any clicks of `color`. With threads, both button listeners can run at the same time which means all button clicks can be listend to at the same time.

## Q2: What is a REST API?

## Q3: What is the desired action performed by the GET, POST, PUT and DELETE methods?

> GET is to query data from a server.
> POST is to send data to the server
> PUT is to send OR update data to/on the server
> DELETE is for deleting data on the server

## Q4: Why is 127.0.0.1 a special IP address?

> This IP address represents the local computer network (just the one machine). It also only allows for other connections on the local network.

## Q5: What is the MVC design pattern? Name one benefit of using it in your software engineering project.

> 

## Q6: Why do we use thread pools to handle incoming requests? What advantages does this provide compared to creating a new thread to handle every new request?

> In this way, we are able # Lab 5 Questions & Answers


## Q1: Recall the ThreadingWithThread and ThreadingNoThread implementations. Did you observe any  differences when running the two programs and clicking on the buttons? If you did, why do you think this happens?

> When running `ThreadlingNoThread`, I could not click the `color` button for 5 seconds after clicking on the `calculate` button. With `ThreadlingWithThread` I was able to click `color` after clicking `calculate`. We think this happens because with no threads, the program must halts on `calculate` for 5 seconds before it can process any clicks of `color`. With threads, both button listeners can run at the same time which means all button clicks can be listend to at the same time.

## Q2: What is a REST API?

## Q3: What is the desired action performed by the GET, POST, PUT and DELETE methods?

> GET is to query data from a server.
> POST is to send data to the server
> PUT is to send OR update data to/on the server
> DELETE is for deleting data on the server

## Q4: Why is 127.0.0.1 a special IP address?

> This IP address represents the local computer network (just the one machine). It also only allows for other connections on the local network.

## Q5: What is the MVC design pattern? Name one benefit of using it in your software engineering project.

> 

## Q6: Why do we use thread pools to handle incoming requests? What advantages does this provide compared to creating a new thread to handle every new request?

> In this way, we are able 
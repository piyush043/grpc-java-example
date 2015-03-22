grpc Create Poll Example
==============================================

In order to run the poll Service simply execute one of the gradle tasks `pollServiceServer`,
`pollServiceClient`.

For example, say you want to create a poll for a moderator. First you want to start
the server and then have the client connect to it.

Assuming you are in the grpc-java root folder you would first start the pollServiceServer
by running

```
$ ./gradlew :grpc-examples:pollServiceServer
```

and in a different terminal window then run the route guide client by typing

```
$ ./gradlew :grpc-examples:pollServiceClient
```

That's it!

Please refer to [Getting Started Guide for Java] (https://github.com/grpc/grpc-common/blob/master/java/javatutorial.md) for more information.

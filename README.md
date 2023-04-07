# simon-websocket

This deliverable demonstrates peer to peer communication using WebSocket.

Seeing the way the front end was able to communicate with the server and in turn the back end to not only create but also authenticate users was really cool. It was cool to see how the code was prepared to respond to any response from the server, either 200 or anything else. I also thought the way the back end encrypts the password to store in the database was cool because it allows the database to be breach and still have user's data relatively safe, at least to a point.

The use of websockets was interesting to look at. I don't feel like I totally understand it still, but I'm getting there. The idea of it using a type of "ping/pong" communiction to figure out if the websocket should still be active to me was interesting, its cool that it will monitor that. With all the sockets being stored in an array and then read out each time it is accessed, are there ever perfomance issues that come along if there are large amounts of people communicating over your websocket?   
Just thinking for my startup, is there a way to make it so that only one person can communicate with another? I guess it would just have to do with the designated ids for the connections and then making sure the message is sent to only the correct id.   
In play.js I don't totally get how the configureWebSocket works with the onmessage portion, mainly event parameter passed into it. I assume that its just a predefined Javascript variable. I'm still trying to figure out how broadCast events calls the displayMsg and configureWebSocket functions, because it seems clear that it does, I just don't know how.

# simon-react

The router is a really interesting concept to me and makes the idea of using react for a single page website make way more sense. At first the idea of a single page website really confused me, even using react. It just seemed lilke it was going to be really complex and kind of redundant. But not using the router you pretty much have separate HTML pages that are all displayed on a single HTML page depending on the user input. It helps break things down and makes it more simple. Not that all the code is simple, I still don't think I totally understand everything, but this way seems more intuitive to me when it comes to following what the code is actually doing. 

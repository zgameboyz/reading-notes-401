# reading-notes-401


## Reading 19 Authentication, Authorization, Cookies

Using HTTP cookies

An http cookie is a small piece of data thata server sends to the user's web browser. The browser may store it and send it back with later requests to the same server. Typically, it is used to tell if two requests came from the same browser-- keeping a user logged in , for example.  To create a cookie you need to set the cookie. Then with every request to the server the cookie will be sent back with all the previously stored data. 

Cookies can have determined lifetimes if designated or last indefinitely. You can do this by seting an exires value equal to a DD/MM/YYYY format at a designated time based off of GMT.

Cookies themselves are just plain-text files stored by the client.


[Table Of Contents](README.md)
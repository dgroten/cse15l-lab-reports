#Lab Report 2#

##Daniel J. Groten##

Code:

![Image](image1.png)

Server:

![Image](image2.png)

The method handleRequest is called. The relevant argument is the URL and the relevant field is the field string as it stores the chat log.

The field string changes every time a new message is entered in the chat by adding the new message to all of the preexisting messages.

Initially, the string is empty, but then my code finds the query in the URL and separates the user and the message from the query and adds them to the field string.

Then, the field string is returned and appears on the chat.

![Image](image3.png)

Everything is the same as the previous example, but this time the initial string field is not zero. It already contains the previous user and message.

Instead of erasing the previous user and message, my code takes the new user and message and adds them to the string field before returning the string so that all messages are displayed

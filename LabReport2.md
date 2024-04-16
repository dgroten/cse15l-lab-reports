# Lab Report 2

## Daniel J. Groten

### Part 1

![Image](image1.png)

![Image](image2.png)

The method handleRequest is called. The relevant argument is the URL and the relevant field is the field called `string` which stores the chat log.

The field `string` changes every time a new message is entered in the chat by adding the new message to all of the preexisting messages as a new line.

Initially, `string` is empty, but then my code finds the query in the URL and separates the user and the message from the query and adds them to `string`.

Then, the updated `string` is returned and appears on the website.

![Image](image3.png)

Everything is the same as the previous example, but this time the initial `string` field is not zero. It already contains the previous user and message.

Instead of erasing the previous user and message, my code takes the new user and message and adds them to `string` before returning `string` so that all messages are displayed

### Part 2

![Image](image4.png)

![Image](image5.png)

![Image](image6.png)

### Part 3

It seems obvious as I'm saying this now, but it never really clicked with me before that everything we do online occurs somewhere on a physical computer.

I used to think of the internet as a cloud, something non-solid that is just floating in the air, but in reality every time we access a server on the internet we are connecting to a physical piece of technology.

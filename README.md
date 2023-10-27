# WebChatServerInC

Live Demo:https://replit.com/@fabiantorrestec/WebChatServerInC#README.md

Web Chat Server in C, CS 361 - using Linux System Calls via I/O Multiplexing

---------------

Picture of how it looks like when running:
<img width="1199" alt="image" src="https://github.com/fabiantorrestech/WebChatServerInC/assets/46858378/362b99e6-f53e-446e-a072-7cc1ed5e75c4">

----------------
How to compile:

Run make, or run all the commands contained in MakeFile.

    	gcc -g -o webchat csapp.c server.c -lpthread

----------------
How to run:

To run, you will need to run the executable with a valid open port number (in this case, i use port 3366).

	./webchat 3366

Then on the same machine, you can test this out by having the terminal open side-by-side with the web browser by navigating to localhost:<port>.

If it is working correctly, you can type a message in the textbox and press enter or click the button to send the message, and you will see that same data reflected in the console over and over.

<img width="176" alt="image" src="https://github.com/fabiantorrestech/WebChatServerInC/assets/46858378/d004dbd8-3329-4b64-ac5b-849cb1224f2e">

For another user to connect, they must be on the same network and you need to keep the terminal open to keep the server running.

To stop the server, go to the terminal window and press Ctrl+C to stop the application.

Enjoy!

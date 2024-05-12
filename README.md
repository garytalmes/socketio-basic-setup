# Getting Started with Web Sockets 

I went ahead and got a very basic, bare-bones implemention of socket.io set up. You'll see 
in the `server.js` how we import socket.io and then integrate it with other Express code. 
I tested it quickly with REST API calls and everything seems compatible.

In the public folder you'll see two script tags on the `index.html` page that must be loaded 
on any page where you want the chat functionality.

## Your Work 

If you decide you want to continue and use sockets in your app and get credit for it being 
your extra technology, you need to figure out any two of the items below.

- For every message displayed on the browser, we should see the author of the message and the date/time for when it was sent.
- Only logged in users should be able to use the chat feature.
- All chats should be stored in the database.
- If someone types `\logout` into the chat they should automatically be logged out.
- When viewing a chat message from someone, there should be a link where we can see that person's profile.
- Next to each chat message should a small avatar image of the message author 
- It should be possible to send emojis as messages also.
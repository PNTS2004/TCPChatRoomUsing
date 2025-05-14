Sure! Here's a friendly, human-like `README.md` you can use for your chat app:

---

# TCP Chat Room

It’s a beginner-friendly client-server program that lets multiple users chat in real-time using sockets and threading — all happening on your local machine.

---

## How it works

This project uses Python’s `socket` and `threading` modules to build a basic chatroom:

* The **server** listens for incoming connections.
* Each **client** connects with a nickname and joins the chat.
* Messages sent by any client are **broadcast to everyone else**.

No GUI, just good old terminal-based chatting!

---

## Files

* `server.py`: Runs the chat server.
* `client.py`: Runs a client instance so you can join the chat.

You’ll need at least **two terminals** (or more) — one for the server, and one or more for clients.

---

## How to run

1. **Start the server**
   Open a terminal and run:

   ```bash
   python server.py
   ```

2. **Start the client**
   Open another terminal (or more) and run:

   ```bash
   python client.py
   ```

   It’ll ask you to enter a nickname. That’s how you’ll show up in the chat.

---

## Example

```
Choose a nickname: Alice
Alice: Hello everyone!
Bob: Hey Alice!
```

Each message is shown with your nickname — like a group chat.

---

## Note

* This only works locally (`127.0.0.1`) unless you configure it for remote use.
* It’s not encrypted or secured — strictly for learning purposes.

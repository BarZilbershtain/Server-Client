# Server-Client
Implemention of an extended version of the TFTP (Trivial File Transfer Protocol) system in Java, using a multi-threaded server-client architecture. The server was designed using the Thread-Per-Client (TPC) model, supporting concurrent file transfers from multiple users. 
The server supports essential operations such as file upload (WRQ), download (RRQ), delete (DELRQ), directory listing (DIRQ), login (LOGRQ), and broadcast notifications (BCAST) to connected clients. The server also encodes and decodes messages using a binary protocol. On the client side, I developed a program with two threads — one handling user input and the other handling incoming messages from the server. Communication was implemented over TCP, with careful attention to synchronization, protocol adherence, and correct handling of messages types.



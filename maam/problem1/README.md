Implement a simple file transfer protocol (FTP) using connection-oriented and connectionless
sockets. The connection-oriented FTP works as follows: At the client side, the file to be
transferred is divided into units of 100 bytes (and may be less than 100 bytes for the last unit
depending on the size of the file). The client transfers each unit of the file to the server and
expects an acknowledgment from the server. Only after receiving an acknowledgment from
the server, the client transmits the next unit of the file. If the acknowledgment is not received
within a timeout period (choose your own value depending on your network delay), the client
retransmits the unit. The above process is repeated until all the contents of the file are
transferred. The connectionless FTP works simply as follows: The file is broken down into
lines and the client sends one line at a time as a datagram packet to the server. There is no
acknowledgment required from the server side.

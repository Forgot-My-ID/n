Develop a streaming client and server application using connectionless sockets that works as
follows: The streaming client contacts the streaming server requesting a multi-media file
(could be an audio or video file) to be sent. The server then reads the contents of the
requested multi-media file in size randomly distributed between 1000 and 2000 bytes and
sends the contents read to the client as a datagram packet. The last datagram packet that will
be transmitted could be of size less than 1000 bytes, if required. The client reads the bytes,
datagram packets, sent from the server. As soon as a reasonable number of bytes are received
at the client side, the user working at the client side should be able to launch a media player
and view/hear the portions of the received multi-media file while the downloading is in
progress

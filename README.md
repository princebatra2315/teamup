# Team up

![color-line](https://i.imgur.com/ufmIs45.png)

A simple application to demonstrate Real time editing content with websockets.

## `server`

Socket io server which runs on `localhost:4001`. It handle the client connections. Every message is now in `update content` channel. This will change to dynamic rooms in future.

## `web`

This is a React app which contains a `textarea` where we can write stuff (which syncs). This will be replaced by a RTE.

Any types of contributions are welcome.

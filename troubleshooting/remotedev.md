# RemoteDev

## Visual Studio Code

when using vs code remote tunnel, you need a non root user to start the vs code server.&#x20;

if you start the vs code server by `code tunnel`, it will be on foreground, once you close the tunnel, the vs code server will be shutdown.&#x20;

if you want to run the vs code server on background, make sure you install service by following command first:

`code tunnel service install`

`if there are errors when executing above command, executing the following command first:`

`loginctl enable-linger dev`

`apt install dbus-user-session`

*

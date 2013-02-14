lycaste
=======

noVNC websocket to TCP proxy and web server.

running
-------

running proxy and webserver::

    cd noVNC
    ./utils/websockify --web ./ 8080 33.33.33.12:5900


then just access http://localhost:8080/vnc.html?host=localhost&port=8080


`Lycaste <http://en.wikipedia.org/wiki/Lycaste>`_

lycaste
=======

noVNC websocket to TCP proxy and web server.

running
-------

running proxy and webserver::

    cd noVNC
    ./utils/websockify --web ./ 8000 localhost:5900


then just access http://localhost:8000/vnc.html?host=localhost&port=8000


`Lycaste <http://en.wikipedia.org/wiki/Lycaste>`_
lycaste
=======

noVNC websocket to TCP proxy and web server.


Documentation
-------------

Diagram describing backend technology and its interactions:

.. image:: diagram.png


running
-------

running proxy and webserver::

    cd noVNC
    ./utils/websockify --web ./ 8080 33.33.33.42:5900


then just access http://localhost:8080/vnc.html?host=localhost&port=8080


`Lycaste <http://en.wikipedia.org/wiki/Lycaste>`_

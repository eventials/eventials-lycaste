lycaste
=======

noVNC websocket to TCP proxy and web server.


Documentation
-------------

Diagram describing usgae of eventials-ophrys backend technology and its interactions as a lib for eventials-lycaste:

.. image:: diagram.png


deploy
------

deploy for dotcloud staging::

  pip install dotcloud
  dotcloud connect lycaste && dotcloud push


running
-------

running proxy and webserver::

    cd noVNC
    ./utils/websockify --web ./ 8080 33.33.33.42:5900


then just access http://localhost:8080/vnc.html?host=localhost&port=8080


`Lycaste <http://en.wikipedia.org/wiki/Lycaste>`_

Python stuff
============


Lib:        python
Version:    2.7.x
Link:       http://python.org/ftp/python/2.7.2/Python-2.7.2.tar.bz2
Install:    ./configure && make && make install
Comments:   If you choose to compile your python interpreter, you must link it
            against all optional libraries it requests. Like libreadline and so. I
            strongly suggest you to upgrade the python package of your favorite
            distro if it's not updated enough.


Lib:        python-imaging-library (PIL)
Version:    1.1.x
Install:    python setup.py install
Comments:   It's necessary to link it against all dependencies (even the
            optionals)


Lib:        zmq
Version:    2.1.10
Link:       http://download.zeromq.org/zeromq-2.1.10.tar.gz
Install:    ./configure && make && make install


Lib:        pyzmq
Version:    2.1.9
Link:       https://github.com/zeromq/pyzmq/downloads/pyzmq-2.1.9.tar.gz
Install:    python setup.py install --zmq=/zmq/prefix (provavelmente /usr)


Lib:        libevent
Version:    2.0.14
Link:       https://github.com/downloads/libevent/libevent/libevent-2.0.14-stable.tar.gz
Install:    ./configure && make && make install


Lib:        greenlet
Version:    0.3.1
Link:       http://pypi.python.org/packages/source/g/greenlet/greenlet-0.3.1.tar.gz
Install:    python setup.py install
Comments:   Please export the env var CFLAGS="-O0" if you're running a 32bits system


Lib:        gevent
Version:    0.13.6
Link:       http://pypi.python.org/packages/source/g/gevent/gevent-0.13.6.tar.gz
Install:    python setup.py install -I/libevent/include -L/libevent/lib
Comments:   Params -I and -L are paths to the inclue/lib dirs of libevent


Lib:        gevent_zeromq
Version:    0.2.0
Link:       http://pypi.python.org/packages/source/g/gevent_zeromq/gevent_zeromq-0.2.0.tar.gz
Install:    python setup.py install


Lib:        gevent-websocket
Version:    0.2.3
Link:       http://pypi.python.org/packages/source/g/gevent-websocket/gevent-websocket-0.2.3.tar.gz
Install:    python setup.py install


Lib:        gevent-socketio
Version:    0.2.0
Link:       http://pypi.python.org/packages/source/g/gevent-socketio/gevent-socketio-0.2.0.tar.gz
Install:    python setup.py install


Lib:        sqlalchemy
Version:    0.7.3
Link:       http://pypi.python.org/packages/source/S/SQLAlchemy/SQLAlchemy-0.7.3.tar.gz
Install:    python setup.py install


Lib:        flask
Version:    0.8
Link:       pypi.python.org/packages/source/F/Flask/Flask-0.8.tar.gz


Lib:        Werkzeug
Version:    0.8.1
Link:       http://pypi.python.org/packages/source/W/Werkzeug/Werkzeug-0.8.1.tar.gz
Install:    python setup.py install


Lib:        Jinja2
Version:    2.6
Link:       http://pypi.python.org/packages/source/J/Jinja2/Jinja2-2.6.tar.gz
Install:    python setup.py install


Lib:        anyjson
Version:    0.3.1
Link:       http://pypi.python.org/packages/source/a/anyjson/anyjson-0.3.1.tar.gz
Install:    python setup.py install


Lib:        tweetstream
Version:    1.1.1
Link:       http://pypi.python.org/packages/source/t/tweetstream/tweetstream-1.1.1.tar.gz
Install:    python setup.py install


Lib:        wtforms
Version:    0.6.3
Link:       http://pypi.python.org/packages/source/W/WTForms/WTForms-0.6.3.zip
Install:    python setup.py install


Lib:        flask-wtf
Version:    0.5.2
Link:       http://pypi.python.org/packages/source/F/Flask-WTF/Flask-WTF-0.5.2.tar.gz
Install:    python setup.py install


Lib:        oauth2
Version:    1.5.170
Link:       http://pypi.python.org/packages/source/o/oauth2/oauth2-1.5.170.tar.gz
Install:    python setup.py install


Lib:        flask-oauth
Version:    0.11
Link:       http://pypi.python.org/packages/source/F/Flask-OAuth/Flask-OAuth-0.11.tar.gz
Install:    python setup.py install


PHP stuff
=========


Lib:        wordpress
Version:    3.2.1
Link:       http://wordpress.org/latest.tar.gz
Install:    Wordpress package is a self-contained instance, so to install it,
            you usually just need to decompress the tarball in a directory
            visible by your webserver and it's done. Distributions like Debian
            has a more complex approach to make it possible to run more than one
            instance with the same source code and to install different versions
            at the same time a system. But I guess it's too much work for a single
            site.
Comments:   To make wordpress work properly, you'll need to install/enable
            mysql and gd (the graphics library).


Lib:        Twig
Version:    1.3.0
Link:       https://github.com/fabpot/Twig/tarball/v1.3.0
Install:    All you have to do is to install the library in a directory
            visible by the PHP include system. In debian, /usr/share/php
            is the right place. It's possible to install twig using pear
            too. The following simple commands do this job:
            # pear channel-discover pear.twig-project.org
            # pear install twig/Twig

Introduction
============

.. image:: https://readthedocs.org/projects/adafruit-circuitpython-gc_iot_core/badge/?version=latest
    :target: https://circuitpython.readthedocs.io/projects/gc_iot_core/en/latest/
    :alt: Documentation Status

.. image:: https://img.shields.io/discord/327254708534116352.svg
    :target: https://discord.gg/nBQh6qu
    :alt: Discord

.. image:: https://travis-ci.com/adafruit/Adafruit_CircuitPython_GC_IOT_CORE.svg?branch=master
    :target: https://travis-ci.com/adafruit/Adafruit_CircuitPython_GC_IOT_CORE
    :alt: Build Status

Google Cloud IoT Core Client for CircuitPython


Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_
* `Adafruit CircuitPython JWT <https://github.com/adafruit/Adafruit_CircuitPython_JWT>`_
* `Adafruit CircuitPython Logging <https://github.com/adafruit/Adafruit_CircuitPython_Logger>`_


Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://github.com/adafruit/Adafruit_CircuitPython_Bundle>`_.

Installing from PyPI
=====================
.. note:: This library is not available on PyPI yet. Install documentation is included
   as a standard element. Stay tuned for PyPI availability!


On supported GNU/Linux systems like the Raspberry Pi, you can install the driver locally `from
PyPI <https://pypi.org/project/adafruit-circuitpython-gc_iot_core/>`_. To install for current user:

.. code-block:: shell

    pip3 install adafruit-circuitpython-gc-iot-core

To install system-wide (this may be required in some cases):

.. code-block:: shell

    sudo pip3 install adafruit-circuitpython-gc-iot-core

To install in a virtual environment in your current project:

.. code-block:: shell

    mkdir project-name && cd project-name
    python3 -m venv .env
    source .env/bin/activate
    pip3 install adafruit-circuitpython-gc-iot-core

Usage Example
=============

Usage example within examples/ folder.

Contributing
============

Contributions are welcome! Please read our `Code of Conduct
<https://github.com/adafruit/Adafruit_CircuitPython_GC_IOT_CORE/blob/master/CODE_OF_CONDUCT.md>`_
before contributing to help this project stay welcoming.

Sphinx documentation
-----------------------

Sphinx is used to build the documentation based on rST files and comments in the code. First,
install dependencies (feel free to reuse the virtual environment from above):

.. code-block:: shell

    python3 -m venv .env
    source .env/bin/activate
    pip install Sphinx sphinx-rtd-theme

Now, once you have the virtual environment activated:

.. code-block:: shell

    cd docs
    sphinx-build -E -W -b html . _build/html

This will output the documentation to ``docs/_build/html``. Open the index.html in your browser to
view them. It will also (due to -W) error out on any warning like Travis will. This is a good way to
locally verify it will pass.

License
=======

This library was written by Google for MicroPython. We've converted it to
work with CircuitPython and made changes so it works with boards supported by
CircuitPython and the CircuitPython API.

We've added examples for using this library to transmit board telemetry data along
with sensor data to Google's Cloud Platform.

This open source code is licensed under the Apache license (see LICENSE) for details.
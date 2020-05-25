
Introduction
============

.. image:: https://readthedocs.org/projects/adafruit-circuitpython-fingerprint/badge/?version=latest
    :target: https://circuitpython.readthedocs.io/projects/fingerprint/en/latest/
    :alt: Documentation Status

.. image :: https://img.shields.io/discord/327254708534116352.svg
    :target: https://discord.gg/nBQh6qu
    :alt: Discord

.. image:: https://github.com/adafruit/Adafruit_CircuitPython_Fingerprint/workflows/Build%20CI/badge.svg
    :target: https://github.com/adafruit/Adafruit_CircuitPython_Fingerprint/actions/
    :alt: Build Status

This library is a fork of the original Adafruit fingerprint library. This library adds support for the GROW R503. For more information about this sensor, visit the `website <http://www.zjgrow.com/grow-r503-new-circular-round-two-color-ring-indicator-led-control-dc33v-mx10-6pin-capacitive-fingerprint-module-sensor-scanner-p2112363.html>`_

Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_

Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://github.com/adafruit/Adafruit_CircuitPython_Bundle>`_.

TODO
=============
- This library at the moment does not support checksum. Right now the checksum is ignored. Af future release should solve this issue.
- The R503 has custom features such as a LED circular light. Native support would be nice. 

Usage Example
=============

See 'examples' folder for full usage demo!



Documentation
=============

This library iterates on the original Adafruit library. For information on building (original) library documentation, please check out `this guide <https://learn.adafruit.com/creating-and-sharing-a-circuitpython-library/sharing-our-docs-on-readthedocs#sphinx-5-1>`_.

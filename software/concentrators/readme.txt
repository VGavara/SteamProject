Software/concentrators. Readme.

This directory stores software developments addressed to manage concentrators. A concentrator is a device that allows a manager accessing to the litems (layout items) in its network in a network technology agnostic way.

This directory organizes its information in a directory structure with these levels:

  1.- A first level based on the concentrator underlying network technology (dcc, 802.11.4, ble, zigbee, wifi, ...)
  2.- A second level based on the concentrator operating system (linux, raspbian, tirtos, baremetal, ...). Note that, in the case that an operating system distribution had a strong hardware dependency (as raspbian), it will be considered not as a distribution but as a whole operating system. Finally, note that those developments addressed to gateways not running on any operating system but on the hardware, the operatin system will be considered as "baremetal" (that would be the case of Arduino, for instance).
  3.- A third, optional level, based on the concentrator hardware whenever that feature determined different software developments. That would be the case of those baremetal developments, ie, those running not on the top of an operating system but on the whole hardware.

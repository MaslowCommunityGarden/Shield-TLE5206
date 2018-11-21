This is our version of the original TLE5206 board, designed by @blurfl for the Maslow community, with the following modifications.

    The PCB now is the same size and shape of the arduino.

    The expansion or development connections are removed.

    Added a new connection for a 12v fan.

    Tracks are wider and we added a few more vias to improve connections.

    Eliminated the third connector on the 12v male, to avoid a potential short circuit with the USB port on the arduino (the third pin connector has no application on this board), pic 5.

    Moved the 12v track out from underneath the heat sink. The back plate of the TLE5206 is internally connected to ground, having the 12v main track right underneath the heat sink (GND), could make it prone to short circuit.

# linuxcnc-code-snippets

This where I will keep different code snippets for different common scenario's in linuxcnc.

<h3> estop-code </h3><br>
This estop code ties external-estop with estop in linuxcnc gui. Both have to be reset
to get a clear estop. I have some machines that have an external system you have to press a button and get a green lite.
I tie this loop into the external estop loop so to start the machine, you need to press
the button wait for green lite, then if estop is clear, you can turn on the machine. IF you dont get a green lite
then you cannot get a clear estop.

**** mpg-code****
This code snipet is for adding an mpg wheel with axis selector and increments.
It uses mux4.

**** pause-resume button****
This code is for adding a hardware button on a control panel.
It will pause the program, then it can resume when pressed a second time.

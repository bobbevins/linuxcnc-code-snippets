# linuxcnc-code-snippets

This where I will keep different code snippets for different common scenario's in linuxcnc.


**** estop-code****

This estop code ties external-estop with estop in linuxcnc gui. Both have to be reset
to get a clear estop. I have some machines that have an external system you have to press a button and get a green lite.
I tie this loop into the external estop loop so to start the machine, you need to press
the button wait for green lite, then if estop is clear, you can turn on the machine. IF you dont get a green lite
then you cannot get a clear estop.




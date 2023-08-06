# EpidemicBroadcast

N nodes are randomly placed on a 2D floorplan. A random node within the floorplan produces
a message that should reach all users as soon as possible. Communications are slotted. Each node has a broadcast radius R defined so that only the receivers within that radius from the transmitter receive the message. A node that receives more than one message in the same slot experiences a collision and it is not able to decode any of them.
After a node successfully receives a message, it keeps extracting a value from a Bernoullian RV with success probability p on every slot, until it achieves success, after which it relays the message and stops.

Credits: Fabio Piras, Giacomo Volpi and Guillaume Quint
# AutoStart module.

A peace of hardware, which controls an open collector output, based on energy mesured by a AC Current Sensor Transformer (CT).

This project is about securing a waterpump.

The idea is to monitor if the waterpump is running too long, and then break the power if that's the case.

Power is controlled by IHC®. To monitor if the waterpump is running, this autoStartd moduld is used.
The CT will mesure if the waterpump is running or not, at the open collector output will be connected to a IHC® Input 24/x module.

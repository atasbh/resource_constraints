# resource_constraints

In this project, our goal is to load the Hapag-Lloyd AG containers from Hamburg port and deliver them to customers in different cities in Germany. There are some limitations in this project that need to be considered:

The loading of cargo at the port can only take place between 6:00 and 9:00, which gives a six-hour window for loading. During this time, all trucks must be loaded.
Customers located in the northern cities should receive their cargo between 7:00 and 14:00, while those in the southern cities should receive it between 15:00 and 20:00. This means that the delivery times are restricted to specific hours in these regions.
Each truck at the port takes 60 minutes to load, while unloading at each city takes 30 minutes. This needs to be factored into the overall scheduling.
The port can load a maximum of two vehicles at the same time, and this needs to be taken into account when planning the schedule.
It is assumed that the weight and volume of delivering cargo are equal for each city.

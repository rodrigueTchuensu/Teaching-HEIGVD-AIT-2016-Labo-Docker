







##Task 0: Identify issues and install the tools  

1. [*M1*] Yes we can use this solution in a production environment but it has some limitations. this solution is not scalable.  

2. [*M2*] To add new webapp containers to the infrastructure, you first need to instanciate the webapp container, then you get it's IP address and add it to the HAProxy configuration file. Finally you need to restart the HAProxy container for it to take into account the changes that have been done to it's configuration file.

3. [*M3*] From the discussion we had in class with our teacher, we have to make things to occur automatically. We could provide a script that will be run automatically to edit the configuration file in HAProxy container,   

4. [*M4*]  By using an agent like serf, that will make it possible for the nodes to discover other nodes belonging to same infrastructure and with the help of a script that is ran automaticaly in case of any accountable chage, the necessary information will be inscribe in the configuration file for any upcoming node.

5. [*M5*]

6. [*M6*]


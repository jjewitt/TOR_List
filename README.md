
This repo contains lists of TOR nodes, updated directly from TOR's back end servers.
If a node is only a middle node, it's ignored for the purposes of this project. 

1. exit_nodes.csv - simply a single-column file of IP addresses, one per line. See file metadata for last update time.
2. guard_nodes.csv - like above, only for guard nodes.
3. recent_nodes.csv - these are guard and exit nodes that have not been seen in greater than about 2 days. Not the best for alerting, but still good for hunting.
4. tor_nodes.json - all three in one package. See below for structure.

   The lists are updated at least every 12 hours.

JSON File structure example:

![image](https://github.com/user-attachments/assets/55d3c20c-6de9-4115-8126-01beb575eb9a)


This repo contains a list of TOR nodes.
1. exit_nodes.csv - simply a single-column file of IP addresses, one per line. See file metadata for last update time.
2. guard_nodes.csv - like above, only for guard nodes.
3. recent_nodes.csv - these are guard and exit nodes that have not been seen in greater than about 2 days. Not the best for alerting, but still good for hunting.
4. tor_nodes.json - all three in one package. See the file for structure.

   The lists are updated at least every 12 hours.

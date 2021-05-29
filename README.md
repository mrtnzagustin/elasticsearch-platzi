# elasticsearch-platzi
Basic repo for elasticsearch Platzi course 

# Error
If you have the error "ERROR: [1] bootstrap checks failed es01    | [1]: max virtual memory areas vm.max_map_count [65530] is too low, increase to at least [262144]", run in host: `sudo sysctl -w vm.max_map_count=262144`

The other option is to set discovery.type=single-node in docker environment
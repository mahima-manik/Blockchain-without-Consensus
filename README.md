# cop701bitcoin

When we run sst.py from the terminal using the command "sudo python sst.py", the user is asked for the number of nodes. 

On giving as input the number of nodes, the topology is created and the terminals for each host is opened.

sst.py executes merge6.py on each host. 

Before running sst.py, make sure to change the path in sst.py to the path where merge6.py is stored.

Each host is given two options:
1. Making a transaction: The host is given an option to make a transaction of bitcoins to some other host.
2. Verifying the ledger: At any point of time, a host can verify its ledger with the ledger's of all other nodes.

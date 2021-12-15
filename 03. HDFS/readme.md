# Hadoop Core Components

## HDFS

- Storage :- Distributed file system
- Name Node
  - Master Daemons
  - Maintains and Manages DataNodes
  - Records metadata of data nodes lke location, size, premissions, hierarchy..etc
  - heartbeat of datanodes
- Data Node
  - Slave daemons
  - Stores actual data
  - Serves read and write requests from the clients
- Secondary NameNode
  - Checkpointing :- process of combining edit logs and FSImage (editLog + FsImage = New FsImage)

# contents of NameNode

- EditLog
- FsImage
- editLog (new)

# contents of secondary namenode

- editLog
- fsImage
- fsImage(final)

<img src="./01.png">

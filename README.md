Built a simple key-value store with replication, partitioning, and failure handling in the Dynamo manner in Android.
1. Established connections, started server and client threads, and handled incoming requests using a file-based content provider.
2. Linearizability was preserved by quorum replication.
3. Without a hitch, it handled the simultaneous functioning of many nodes (AVDs) crashes, recoveries, failures, and re-joins.
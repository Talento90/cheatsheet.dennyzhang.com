# Design a system checking the health of 10,000 nodes

Design a system that checks the health of 10,000 nodes. Each of 10,000 modes have an API exposed that you have to call and check the health. This API takes 1-5 seconds to respond. There is UI which tells which nodes are healthy OR not healthy. Your system should provide API for this UI. This UI refreshes every 10 mins. So, every 10 mins your system should be able to update data about those 10,000 nodes.

Requirements & Use cases:

Scale:

High Level Design:

Detail Design:

# How to release 1GB binary to 10,000 servers

Requirements & Use cases:

Scale:

High Level Design:

Detail Design:

# Store 2TB data in three 1TB disks with redundancy

Say 2TB data is A and B. For three disks, we store data as A, B and A XOR B.

If any of three disks is down, we can still retrieve the original data: A and B.

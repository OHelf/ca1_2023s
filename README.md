# ca1_2023s

include your report here. 

In ROS2, calling the command 'ros2 topic' gives a list of topics for the speaker/listeners.

bw: This command allows the user to monitor the bandwidth utilization of the present nodes.

delay: This command displays the delay between when a message is published and when it is heard.

echo: This command allows the user to display a message from a topic/speaker. The user can specify a data type and how the message is formatted (i.e. csv, array, etc.)

find: This command prints a list of topics of a type the user specifies.

hz: This command displays the average rate of message publishing.

info: This command gives info about a user-defined topic.

list: This command displays a list of topics available to the user.

pub: This command allows the user to publish a message of a specified data type to an available topic. It also provides node properties like how long a node is left up after the last message, node history, reliability, and durability.

type: This command prints a node's type.


In ROS2, calling the command 'ros2 node' allows the user to request information about what nodes are running, and what they are doing.

info: This command provides information about running nodes. You can specify a specific node and get information about it with this command.

list: This command provides a list of running nodes. 

When looking at node and topic information, you can also add the following arguments:

--use-sim-time: This command enables simulation for a node.

--spin-time SPIN_TIME: This command allows the user to decide the time it takes for a node to be discovered, but only for nodes that are not already using a running daemon.


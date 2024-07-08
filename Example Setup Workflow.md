### Example Setup Workflow
1. Create cloud account and user role
2. Spin up remote desktop
3. Create a Virtual Private Cloud network scoped based on project
4. Partition your VPC into subnets and create an internet gateway for public incoming connections
5. Create a directory to manage users and install user management tools
6. Create roles for various actions such as launching new instances. These roles will be assigned to users based on function.
7. Create security groups that allow access through predefined ports based on function. E.g.: 3389 for Remote Desktop
8. Create tags to easily manage your setup as a group
9. Add virtual storage to your remote desktop
10. File system service for different file system types - NetApp, OpenZFS, Windows File Server, SMB
11. Update security groups to create rules for different inbound connections - e.g.: Ephemeral ports for RPC
12. Create new file system for shared storage and specify size
13. Create alias (CNAME) for file system, and map to instance for easy connection
14. Using the user management tools, Create organizational hierarchy of users and map users to the file system for access
15. Create users for artists, update password policies and enable login
16. Create a launch template saving all the configurations into an easily repeatable action
	![[IMG_0356.jpeg]]
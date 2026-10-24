First, the EC2 intances were launched with a basic web server name. Key pairs were created (that use the same name as the web server name). A security group was created for each of the instances. The same "DoNotDelete" VPC was used for each of the instances. 

The CPU, memory and disk usage/uptime show me the instance is likely not in use when there is no traffic being directed to it.

One thing that became easier with repetition was the creation of the creation of the inbound rules SSH and http.

One error I ran into was the SSH instance not loading properly. I swapped web browsers from Brave to Chrome which resolved the issue for now while still investigating the root issue preventing the SSH connection within Brave.



See the table created with Markdown below:



| Deployment | Public IPv4 address | Connection Method | Screenshot | Instance Terminated
| -------- | -------- | -------- | ------ | ----- | 
| 1  | 3.88.185.82  | EC2 / SSH  | screenshots/InstanceB_SS.png |  No (Will be eventually)
| 2  | 98.84.149.28  | EC2 / SSH  | screenshots/InstanceC_SS.png | No (Will be eventually)
| 3  | 54.226.75.159  | EC2 / SSH | screenshots/InstanceD_SS.png | No (Will be eventually)
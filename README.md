# IMAPEX - UCS Director

Intro here

### UCS Director Workflows

 - Importing
 - version management
 - screen shots

### UCS Director Tasks
Explain difference between tasks and workflows

Tasks should be atomic operations - create a Lun, Set the number of CPUs in a VM, Register an IP address

Tasks are common behaviors that are common across organizations

Workflows are structured chains of tasks - can include flow control (branching, loops)

Workflows reflect the unique procedures of different organizations


 - Reports and converting them into tasks

### Logging

 - Developer mode Log files, debugging

###  REST API

Explain UCSD Rest API here
```
Request URL
http://<UCSD_IP>/app/api/rest?formatType=json
&opName=userAPISubmitWorkflowServiceRequest
&opData={
param0:"Change_VM_Size",
param1:{ "list":[
{ "name":"VM_Identity",
"value":"45" },
{ "name":"Update_CPU",
"value":"2" },
{ "name":"Update_RAM",
"value":"2048" }
] },
param2:-1}


```



###  Communities

Explain UCSD communites

**Workflow Index**

**Task Index**

### Some Important Example Worflows

### Customization

**Custom Task**

Example Custom Task - UCSD Integration with Ansible Tower
https://github.com/blairhicks/ucsd-ansible-tower.git


### Open Automation

Explain open automation here

### Derivatives

Explain Derivatives
 - UCSD
 - UCSD Express (Hadoop) 
 - UCSD ICF (Inter Cloud) 
 - UCSD VACS (Containers on Steroids) 
 - UCSD IMC Supervisor

### Further Reading

UCS Director Fundamentals Guide:
http://www.cisco.com/c/en/us/td/docs/unified_computing/ucs/ucs-director/fundamentals-guide/5-4/b_UCS_Director_Fundamentals_Guide_54.html

New Cook Books
http://www.cisco.com/c/en/us/support/servers-unified-computing/ucs-director/products-programming-reference-guides-list.html


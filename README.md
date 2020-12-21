# Task 11.1

## Description:


## Solution

created playbook for this:

- HADOOP_INFRASTRUCTURE_WITHOUT_CLIENT.YML : PLAYBOOK to create hadoop setup witout client
- hdfs-core.xml      :  Configuration file
- core-site.xml      :  Configuration file
- DEL_HADOOP_INFRASTRUCTURE_WITHOUT_CLIENT.YML : Playbook to Delete whole setup
- hadoop-1.2.1-1.x86_64.rpm      :   Hadoop setup file


<b>

Imp: First make group in inventory with tag as namenode and datanode. Then play this playbook.

---
Inventory:

[namenode]
ip ...  ... ....

[datanode]
ip1 ... ... ...
ip2 ... ... ...
ip3 ... ... ..

...




Command : ansible-playbook hadoop_infrastructure_without_client.yml
</b>

#NOTE: System should have pip and ansible before running this playbook. 

Thank You 


CREATER: Kaushal Soni


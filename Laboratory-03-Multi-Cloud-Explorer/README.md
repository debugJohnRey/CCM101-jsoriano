# Checkpoint 7: Continue Your Linux Investigation 

| System Category | Linux Command | Investigation Findings |
| :--- | :--- | :--- |
| Operating System | `cat /etc/os-release` | Ubuntu 24.04.4 LTS. |
| CPU Information | `lscpu` | The server have 1 CPU. It use a Intel Xeon E312xx processor running at 2.0GHz. The architecture are x86_64. |
| Memory | `free -h` | It have a total of 1.9Gi of memory. Currently it use 466Mi. |
| Disk Space | `df -h` | The main root folder have a size of 19G. It use 5.4G and have 13G available. |

## Cloud Migration Answer
If we migrates this Linux server to the cloud, we can uses the virtual machine services from the major providers. For AWS, it can be host on Amazon EC2. If we chooses Azure, it will runs on Azure Virtual Machines which fully support Ubuntu 24.04. On Google Cloud Platform, we can use Google Compute Engine to hosts it. These service provide virtual servers that works exactly like the Linux playground.
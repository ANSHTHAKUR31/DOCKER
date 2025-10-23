Befor we start about docker lets learn about VMs

 virtual machine is a logical islolation on the physical servers with help of software called as hypervisor(xen).
 vm has its own operating system , such example of VMs are EC2 instances 

why we move to conatiners from vm 
=> bcoz not utilizing the vm at its full capicity

conatiners are lightweight in nature why ? 
=> the downt have their own full (os and resources ) they rely on host os and host system

so conatiners do not have its own os , well they have minimal os called as Base-image

A conatiner is a pcakage or a bundle which is a combination of your application + application libraries/dependencies + system dependecies


life cycle of conatiner :
dockerfile -> image -> container

commands——[docker engine]

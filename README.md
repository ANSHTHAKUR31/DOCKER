# Befor we start about docker lets learn about VMs

<img width="1108" height="555" alt="Screenshot 2025-10-23 at 3 14 22 PM" src="https://github.com/user-attachments/assets/e873e828-e650-4fb7-8464-2a9a43fc3feb" />


 * virtual machine is a logical islolation on the physical servers with help of software called as hypervisor(xen).
*  vm has its own operating system , such example of VMs are EC2 instances 

## why we move to conatiners from VMs

<img width="634" height="511" alt="Screenshot 2025-10-23 at 3 18 47 PM" src="https://github.com/user-attachments/assets/43c49a3c-a160-4dbf-861e-d9ccaff57d89" />

-  bcoz of not utilizing the vm at its full capicity

### conatiners are lightweight in nature why ? 
- the don't have their own full (os and resources ) they rely on host os and host system

- so conatiners do not have its own os , well they have minimal os called as Base-image

<img width="889" height="511" alt="Screenshot 2025-10-23 at 3 20 49 PM" src="https://github.com/user-attachments/assets/958a9624-f232-400f-bbe7-079bf310f402" />

* A conatiner is a pcakage or a bundle which is a combination of your application + application libraries/dependencies + system dependecies


#### life cycle of conatiner :
 ```dockerfile -> image -> container
commands——[docker engine]
```



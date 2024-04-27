 -  AWS account create
 - Enter valid details only
 - Create root account
 - Create MFA
 - IAM  - Identity Access Manager
	 - Create IAM user
	 - Attach policy -admin access
	 - use always iam user 
	 - Once user created, click the user 
	 - Security credentials tab for MFA setup
 - Setup Billing dashboard

	 - Navigate to account dropdown select billing section
	 - Billing preference update
	 - Cloud watch  - monitoring service 
* Request certificate for domain purchased
	* SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are cryptographic protocols that provide secure communication over a computer network. They're like special envelopes that keep your messages safe as they travel from one place to another on the internet.
	* -   **Encryption**: Scrambles data during transmission, making it unreadable without the right key.
-   **Authentication**: Verifies the identity of the website/server you're connecting to, ensuring it's not a fake.
-**Integrity**: Protects data from tampering during transmission, ensuring it arrives as sent.
- AWS CNAME - CVALUE bind with Godaddy accout
- IAM user login

## VM setup

 - -   **Definition**: Virtual machines (VMs) are software-based emulations of physical computers. They allow multiple operating systems (OS) to run on a single physical machine.
    
-   **Purpose**: VMs enable the creation of multiple isolated environments on a single physical server, each with its own OS and applications. This allows for better resource utilization and flexibility in managing computing resources.
    
-   **Components**:
    
    -   _Hypervisor_: Software that creates and manages VMs on a physical server. It allocates resources, manages guest OS instances, and facilitates communication between VMs and physical hardware.
    -   _Guest OS_: The operating system installed within each virtual machine.
    -   _Virtual Hardware_: Emulated hardware components provided to each VM, including virtual CPUs, memory, disk storage, and network interfaces.
-   **Benefits**:
    
    -   _Resource Consolidation_: VMs allow multiple virtualized servers to run on a single physical server, reducing hardware costs and improving resource utilization.
    -   _Isolation_: Each VM operates independently of others, providing strong isolation between applications and operating systems.
    -   _Flexibility_: VMs can be easily created, cloned, moved, and deleted, providing flexibility in deploying and managing software environments.
    -   _Disaster Recovery_: VMs can be backed up, replicated, and migrated between physical servers, facilitating disaster recovery and high availability solutions.
-   **Use Cases**:
    
    -   _Server Consolidation_: Running multiple virtual servers on a single physical server to reduce hardware costs and energy consumption.
    -   _Development and Testing_: Providing developers with isolated environments to test software applications without affecting production systems.
    -   _Cloud Computing_: Hosting virtualized infrastructure and services in cloud environments, enabling scalability and on-demand resource provisioning.
-   **Challenges**:
    
    -   _Performance Overhead_: VMs incur a slight performance overhead compared to running directly on physical hardware due to virtualization layer.
    -   _Resource Allocation_: Efficient resource allocation and management are crucial to prevent over-provisioning or under-provisioning of virtualized resources.
    -   _Security Concerns_: VMs introduce additional attack vectors, and security measures must be implemented to protect against VM escape attacks and unauthorized access.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE5MTI1MDkxMiwtNjgxODUwNjgxLC0xND
czMTEwODUsMTkyNjczMjAxOCwtNDk4Mjc3MTE5LDE2MDI5MzUz
NDEsLTE4MjQ1NjkyNzMsODk0MDcwOTgwXX0=
-->
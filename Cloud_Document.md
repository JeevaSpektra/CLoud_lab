   #                                             **Practice Use for Adding template in Cloud Labs** 
# **Overview** 
   
Windows Virtual Desktop is a desktop and app virtualization service that runs on the cloud.

Here's what you can do when you run Windows Virtual Desktop on Azure:

   - Set up a multi-session Windows 10 deployment that delivers a full Windows 10 with scalability.
   - Virtualize Microsoft 365 Apps for enterprise and optimize it to run in multi-user virtual scenarios.
   - Provide Windows 7 virtual desktops with free Extended Security Updates.
   - Bring your existing Remote Desktop Services (RDS) and Windows Server desktops and apps to any computer.
   - Virtualize both desktops and apps.
   - Manage Windows 10, Windows Server, and Windows 7 desktops and apps with a unified management experience.

## **General Hierarchy**

### **Host Pools**

Host pools are a collection of one or more identical virtual machines within Windows Virtual Desktop tenant environments. Each host pool can be associated with multiple RemoteApp groups, one desktop app group, and multiple session hosts. Host Pools can be one of two types: 

   - **Personal**, where each session host is assigned to individual users. 
   - **Pooled**, where session hosts can accept connections from any user authorized to an application group within the host pool. You can set additional properties on the host pool to change its load-balancing behavior, how many sessions each session host can take, and what the user can do to session hosts in the host pool while signed in to their Windows Virtual Desktop sessions. You control the resources published to users through application groups. 

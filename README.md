# Dev Container with Docker Compose 
## 2 containers (Python with Debian 11) - Backend and MySQL Setup Instructions
### Pre-Requisites: Ensure you have Visual Studio Code (VSC) and Docker installed with Windows Subsystem for Linux (WSL2).

This guide will assist you in setting up a development container that runs Docker and includes a well-defined tool/runtime stack. The container comprises Python and MySQL databases on an Debian 11 Linux base for backend, along with Visual Studio Code (VSC) plugins customised to suit our requirements.

After completion of this setup, it allows you to open or clone code in a local or cloud-hosted Dev Container and take advantage of VS Code's full development feature set.

## Setup Steps

**1. Download the Repository Zip:**
  - Click Code Button > Download ZIP to download the zip file from this repository.
  
  <img width="676" alt="image" src="https://github.com/limkimhoe/docker-python-mongo-mysql/assets/22229616/93cbc897-bc7f-420d-9cb4-3f778061af53"><br/><br/>

   
**2. Create Project Workspace:**
   - Create a "Workspace" folder on your C:\ or D:\ drive.
   - Inside the Workspace folder, create a subfolder for your project.
     - Example: C:\Workspace\YOUR_PROJECT_NAME
   - Note: This step links your local Workspace folder with the container's Workspace folder. 
     
**3. Unzip the Repository:**
   - Unzip the downloaded zip file into your project folder.
   - Your project folder should now have a structure like this:
     
  <img width="126" alt="image" src="https://github.com/limkimhoe/docker-python-mongo-mysql/assets/22229616/97638aba-86f6-4866-bf16-d101267a98e0"><br/><br/>
  
     
**4. Install Dev Containers Extension:**
   - Launch Visual Studio Code (VSC) and install the Dev Containers extension.

   <img width="800" alt="image" src="https://github.com/limkimhoe/docker-python-mongo-mysql/assets/22229616/9d4d500c-bbe2-4f55-bf95-1d27849b232d"><br/><br/>
   
   
**5. Open Your Project in VSC:**
   - Open your project folder by clicking File > Open Folder and navigate to your project folder.
   
   <img width="240" alt="image" src="https://github.com/limkimhoe/docker-python-mongo-mysql/assets/22229616/5a9578d9-72b4-49be-83b3-01d779f585d2"><br/><br/>

   
**6. Reopen Container:**
    - A popup saying "Reopen" should appear in the bottom right corner. If not, follow these steps:
       - Press F1.
       - Type "Dev Container: Reopen Container".
   
   <img width="360" alt="image" src="https://github.com/limkimhoe/docker-python-mongo-mysql/assets/22229616/bb808168-70f0-4b77-be58-2106e0e5e12f"><br/><br/>
 
   - VSC will reopen the folder to BACKEND folder, download, and install the necessary container files. This may take 5-15 minutes depending on your internet speed.<br/><br/>

   <img width="959" alt="image" src="https://github.com/limkimhoe/Docker-Python-Frontend-Backend-Postgresql/assets/22229616/09241417-4020-412d-ad7f-f1a9096635e7"><br/><br/>

  
## Congratulations! Your setup is complete, and you are ready for Python development!

    

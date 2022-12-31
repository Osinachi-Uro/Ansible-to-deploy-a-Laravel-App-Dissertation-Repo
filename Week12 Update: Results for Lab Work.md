#### Find below steps taken and the results of running the whole ansible script to deploy the laravel app.

From the last update (Week 11), two virtual servers were created on Digital Ocean. A control node and a managed node, find them below:

<img width="943" alt="Droplets" src="https://user-images.githubusercontent.com/83463641/210149110-2b09cf42-52c8-439b-a003-33c9d51c099d.PNG">

### Steps
The following steps were taken to successfully deploy a laravel application using Ansible configuration management tool.

#### 1. I SSH into the control node and created a new user with sudo previledges
<img width="755" alt="1  Create new user and assign the user sudo previledges" src="https://user-images.githubusercontent.com/83463641/210149147-74a6c7c8-b518-4552-81ea-44edcd15e9c0.PNG">

#### 2. Installed Ansible dependencies and Ansible on the control node
<img width="642" alt="2  Install Ansible dependencies" src="https://user-images.githubusercontent.com/83463641/210149208-9a44e3b3-b449-45f3-a4d5-7ec46c0cb334.PNG">

#### 3. Established a successfull connection with the managed node from the control node
<img width="769" alt="4 ssh into managed snode from control node" src="https://user-images.githubusercontent.com/83463641/210149288-b2b37c79-3c6a-458d-bc9e-6437be29166b.PNG">

#### 4. Established a successfull Ansible connection with the managed node
<img width="731" alt="5  Establish a successfull ansible connection to the managed node" src="https://user-images.githubusercontent.com/83463641/210149325-76c94d64-1e73-453d-ad7d-b73767239824.PNG">

#### 5. Create a host inventory file containing information about the host server (the managed node) and a playbook containing the execution script (ansible tasks)
<img width="643" alt="host Inventory file" src="https://user-images.githubusercontent.com/83463641/210149357-7c422af9-2c9a-4fc8-93a5-000c3bc8dbed.PNG">
<img width="920" alt="playbook of 402 lines" src="https://user-images.githubusercontent.com/83463641/210149490-c566e601-7a28-4dfc-a7ce-3fcfac769a48.PNG">

#### 6. Below are screenshots of the ansible playbook successfully executed.
<img width="677" alt="7  Play 1" src="https://user-images.githubusercontent.com/83463641/210149556-da6089ab-a618-48b0-8d5d-5df4efad3a4b.PNG">
<img width="951" alt="7  Play 2" src="https://user-images.githubusercontent.com/83463641/210149559-97905294-b70f-439a-adbb-b61a7065c817.PNG">
<img width="377" alt="7  Play 3" src="https://user-images.githubusercontent.com/83463641/210149562-7effff96-89c0-4a8b-bd58-72b5882c7595.PNG">
<img width="579" alt="7  Play 4" src="https://user-images.githubusercontent.com/83463641/210149565-c59afc6f-5e5b-48c9-b1b1-053c6499fa0f.PNG">
<img width="607" alt="7  Play 5" src="https://user-images.githubusercontent.com/83463641/210149569-bffdb7d5-153d-4aa1-a26a-c1ecf584921f.PNG">
<img width="842" alt="7  Play 6" src="https://user-images.githubusercontent.com/83463641/210149577-fe75844f-3790-4e17-b75a-c2395e11a9c7.PNG">
<img width="782" alt="7  Play 7" src="https://user-images.githubusercontent.com/83463641/210149588-2ac51919-1922-4033-8529-6235202ff29d.png">
<img width="929" alt="7  Play 8" src="https://user-images.githubusercontent.com/83463641/210149595-309c9693-6c46-4347-a185-1f29c7f1527d.PNG">

#### 7. Below are screenshots of the Apache Page showing Apache server successfully installed using Ansible
<img width="735" alt="Apache page displayed" src="https://user-images.githubusercontent.com/83463641/210149632-ba04bf34-5fd0-4023-b003-17fb4335cfd2.PNG">

#### 8. Below are screenshots of the Laravel Application successfully deployed
<img width="906" alt="Laravel page displayed" src="https://user-images.githubusercontent.com/83463641/210149653-a9935592-6adc-4f3c-b0f0-4377b12dd7b2.PNG">

#### 9. Below are screenshots of the Laravel Application successfully deployed, the web page secured using ssl and a domain name (osinachiuro.me) assigned to the web page.
<img width="896" alt="Secured Laravel Page displayed" src="https://user-images.githubusercontent.com/83463641/210149686-76e7b50e-234a-48d4-8e78-e05dffaa7913.PNG">

### Thank you!

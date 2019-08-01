# Setting up git and basic commands

I am covering some basic day to day commands involved in GIT, starting from the installation and setup both in windows and linux. 

1. [Installation](#Installation)
2. [Basic commands](#Basic-Commands)

## Installation

**1. Install git**

    Windows: https://git-scm.com/downloads

    Linux : 
    >sudo apt-get install git

**2. Generate ssh key**

      Windows:
      1. Open Git gui 
      2. Help ->Show sshkey -> click Generate key. (copy the text inside text box - starting with ssh-rsa)

      Linux:
      1. Open terminal type the following commands
    
      > ssh-keygen -t rsa -C "abc@test.com"
      
      > cat ~/.ssh/id_rsa.pub 
      
      2. Copy the text - starting with ssh-rsa
      
**3. Login to Gitlab or Github (with your credentials)**

**4. Click on User-avatar -> Settings -> ssh and Gpg keys - Paste the ssh key, enter the title and click on save.**

   Open gitbash or terminal and enter the following command.
   
   > ssh -T git@github.com  
   
   You should receive a welcome message. Note ssh key for the github and gitlab could slightly vary. 

**5. Setting up git user details**
    Open Terminal / Git bash in 

      > git config --global user.name "<<< firstname lastname>>>"
      
      > git config --global user.email "<<< abc@test.com >>>"
      
      > git config --global -l 
      
      you should see the following result
      
      ```
      <<< firstname lastname >>>
      <<< abc@test.com >>>
      ```
      
## Basic Commands

    

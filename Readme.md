## Setting up git and basic commands
1. Installation
2. Basic commands

# Installation

1. Install git 

    Windows: https://git-scm.com/downloads

    Linux : 
    >sudo apt-get install git

2. Generate ssh key

      Windows:
      1. Open Git gui 
      2. Help ->Show sshkey -> click Generate key. (copy the text inside text box - starting with ssh-rsa)

      Linux:
      1. Open terminal type the following commands
    
      > ssh-keygen -t rsa -C "abc@test.com"
      
      > cat ~/.ssh/id_rsa.pub 
      
      2. Copy the text - starting with ssh-rsa
      
3. Open Gitlab or Github (with your credentials)

4. Click on User-avatar -> Goto Settings -> ssh and Gpg keys - Paste the ssh key, enter the title and click on save

5. Setting up user details, Open Terminal / Git bash in 

      > git config --global user.name "<<< firstname lastname>>>"
      
      > git config --global user.email "<<< abc@test.com >>>"
      
      > git config --global -l 
      
      you should see the following result
      
      ```
      <<< firstname lastname >>>
      <<< abc@test.com >>>
      ```

    

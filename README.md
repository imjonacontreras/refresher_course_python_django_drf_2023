# Profiles REST API

Profiles REST API course code.

Steps i did in this exercise.

Set up a development environment with Python, Django, and DRF, including installing necessary packages and dependencies;
    "git add ." - always type when any changes is made like adding or removing files
    "git commit -am "message here" "
        this means, commit all changes and add message or comment
Create public/private SSH key pair for security measures when pushing to GitHub; 
    command is ssh-keygen -t rsa -b 4096 -C "emailaddress here"
        this means 'ssh-keygen' run ssh-keygen tool 
        with '-t' with type 'rsa' that has bytes '-b 4096'
        '-C " "' is for the comment
    after entering the command, the terminal generates key
        asked me for filw in which to save a key. i saved it by default
        directory is created
        terminal asked me to create passphrase
        terminal generated key finterprint
    i entered 'ls ~/.ssh' to list .ssh files in the directory
        terminal listed id_rsa and id_rsa.pub. 
        id_rsa is private
        id_rsa is public. always use this one.
    I went to github > settings > SSH and GPG Key > New SSH Key
    Using git bash terminal, I output my public key by using this command, 'cat ~/.ssh/id_rsa.pub'
        always use the PUBLIC KEY. 




# Manipulation of Hitachi Arrays using PFRest
## Setup
* Create storage_vault.yml file using ansible-vault using:

    ansible-vault create storage_vault.yml 
    
* Populated the required variables:

    ---
    
    storage_ip: 1.1.1.1 #This is the IP of your array <br>
    storage_username: ma....ce #Storage Username to use example<br>
    storage_password: raid-ma....ce #Storage Password to use example
    
# Running a playbook
* Check the variables at the top align to your goal. 
* Execute the required play in example:<br>
  ansible-playbook -vv create_volume.yml --ask-vault-pass



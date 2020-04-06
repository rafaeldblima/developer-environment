# Playbook developer environment

**warning**: In `install.yml`change `<YOUR-USER-HERE>` to your user and if needed add others users

## Roles
   >You can remove any role, that you don't need to in `install.yml`
    
   * Pyenv
   * Pipenv
   * Docker
   * NVM && Node
   
   > TODO: More roles

## Using the playbook

   - install the dependencies
      ```bash
       pip install -r requirements.txt
     ```
   - Running the playbook
      ```bash
       ansible-playbook install.yml -K
     ```
     
     **warning**: This commando will ask for your password to install packages
# ansible


### Run playbook with vault password file

```bash
 $ ansible-playbook playbook.yml --vault-password-file  .vault_pass.txt 
 ```
 
 ### Run playbook with tags
 ```bash
 $ ansible-playbook playbook.yml --vault-password-file  .vault_pass.txt --tags="set_up" 
 ```
 
  ### Encrypt vars file content
 ```bash
 $ ansible-vault encrypt vars.yml --vault-password-file .vault_pass.txt 
 ```
 
 
  ### Decrypt vars file content
 ```bash
 $ ansible-vault decrypt vars.yml --vault-password-file .vault_pass.txt 
 ```

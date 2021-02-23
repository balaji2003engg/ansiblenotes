# ansible basic commands

check the inventroy.txt hosts connectivity with ping command

            anisble all -m ping -i inventory.txt
            
  Syntax check for basicmodule.yml file
  
          ansible-playbook playbook.yml --syntax-check
          
   RUn the playbook basicmodule.yml with inventory module
   
           ansible-playbook basicmodule.yml -i inventory.txt

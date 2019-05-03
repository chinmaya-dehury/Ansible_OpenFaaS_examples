
# Example Description:  
Ansible playbook to build and deploy the “Thumb_local” function. The playbook would also invoke the function to test if the function is working.   
The function “Thumb_local” generates the thumbnail of a .jpg image present in a specific directory. The thumbnail image is then stored in the same directory. The image must be present in the “./img” subdirectory. 

# Prerequisite:  
  > Ansible 2.7.12  
  > Python 3.x  
  > OpenFaaS (faas-clli  v0.8.9)  
  > Docker 18.09.5  
# Execute the ansible
>> ansible-playbook thumb_playbook.yml

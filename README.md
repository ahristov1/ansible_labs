# ansible_labs

Ansible repo with automation labs.
<br>
<b>Ad-hoc commands:</b>
<ul>
    <li>ansible all --key-file <ssh_file> -i <inventory_file> -m ping</li>
    <li>ansible all -m gather_facts - will gather ifnromation regarding the nodes.</li>
    <li>Easier version of the same command is to create an ansible.cfg file and set it with two parameters inventory - to specify inventory file and private_key_file - specify the ssh key to log in to the nodes. </li>
</ul>

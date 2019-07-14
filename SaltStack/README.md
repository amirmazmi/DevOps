# SaltStack

### Installation instructions
Guide: <br>
https://repo.saltstack.com/#ubuntu

1. Import key  
   ```wget -O - https://repo.saltstack.com/py3/ubuntu/18.04/amd64/2019.2/SALTSTACK-GPG-KEY.pub | sudo apt-key add -```

2. Create /etc/apt/sources.list.d/saltstack.list  
   ```deb http://repo.saltstack.com/py3/ubuntu/18.04/amd64/2019.2 bionic main```

3. Run updates

4. Install packages  
   ```sudo apt install salt-master salt-minion salt-ssh salt-syndic salt-cloud salt-api```
 
<br><br>
### Post installation configuration
   
   

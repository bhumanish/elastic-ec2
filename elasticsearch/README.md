1. Create a new EC2 Security Group
   Port 9300 should only be open to rest of the security group (Elasticsearch Transport Layer)
   Port 9200 and/or Port 80 should be carefully restricted (Elasticsearch Command Layer)
   Port 22 should be open (SSH Access)
2. Create and download an EC2 keypair
   You can only download this once, and instances are locked to a key, be careful!
3. Install Ansible on your local machine
   Use your package manager or download directly from Ansible.
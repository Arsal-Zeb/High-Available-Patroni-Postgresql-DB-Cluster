# High-Available-Patroni-Postgresql-DB-Cluster
This repo contain Ansible script to setup high available 2-3-5-7... node postgresql DB cluster via Patroni

1. Install and setup Ansible so that can access and ping all nodes in the cluster from Ansible machine
2. Download the necessary rpm file and put it in the /INSTALLERS directory
3. First, run the etcd.yaml script to install and configure etcd
4. After that, run patroni script to setup patroni and PostgreSQL
5. Check the cluster health.

   # For a detailed step-by-step procedure, please follow my Medium article. Thanks 
   https://medium.com/@arsalanzeb11/building-a-highly-available-postgresql-cluster-with-patroni-and-ansible-on-rhel-9-for-production-ddeb6529f198 
   

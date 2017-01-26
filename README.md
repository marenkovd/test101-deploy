# test101-deploy
Configure sloppy eployment for test101 on standalone kube with ansible playbook.

What:

  - Install NGINX reverse proxy for test101. Nginx proxy connects to the kubes servies published on clusterIP
  - Install kubes service for test101. User static clusterIP to avoid dns configuration
  - Install kubes deployment for test101. Use latest tag, pre pull image. 

  

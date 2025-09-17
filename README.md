# docker-test-key

Task 1:
I have created an AWS EC2 instance and performed all tasks on it.

-> I have created a demo React and Node-based repo and integrated the frontend and backend Dockerfiles in their respective folders.
-> Moreover, the nginx.conf file you can find in the root folder. and also docker-compose file to start and up both containers.


Task 2:

-> I have added .gitlab-ci.yml file in which I have mentioned the SSH_PRIVATE_KEY, SSH_KNOWN_HOSTS, DEPLOY_USER, DEPLOY_HOST, CI_REGISTRY_USER & CI_REGISTRY_PASSWORD variables. Which is a GitLab CI/CD variable for securely storing the details for an EC2 instance.
-> I have to take the deploy named runner on the server. That is configured on the server and, according to that, managed gitlab-ci.yml

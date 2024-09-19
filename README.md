**DevOps Project**

Steps Followed:

<img width="274" alt="image" src="https://github.com/user-attachments/assets/452e0263-8c65-49b7-8799-bdeca68e73f8">


1.  Create a Dockerfile from the git repository
2.  Built a Docker Image from the file
  Commands:
    - docker build -t 2048-game .
    - docker images
3.	Create Docker Container
    - docker run -d -p 80:80 IMAGE_ID
4. Deploy containerized Docker game on AWS cloud



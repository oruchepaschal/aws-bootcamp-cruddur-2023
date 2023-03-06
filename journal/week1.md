# Week 1 — App Containerization

## Required Assignments

For week 1, I was able to create the Docker files for
both backend and frontend applications and run them

## Homework stretch

- Completed all requirements for week 1
- Delved deep into container security concepts, and grasping and practicing the concepts of container image security
- discovered vulnerabilities in bootcamp docker compose file using Synk vulnerability scanner (email notification and dashboard report)
- practiced further on containerizing apps
- built images and pushed to the most popular free container registry, Dockerhub
- some a blocker I in running the frontend container, but fixed it

Encountered exiting error whilst trying to start the frontend container, investigating further and realized I hadn't installed the node modules. 

error logs below:
```sh
2023-03-02 23:14:40 
2023-03-02 23:14:40 > frontend@0.1.0 start
2023-03-02 23:14:40 > react-scripts start
2023-03-02 23:14:40 
2023-03-02 23:42:20 
2023-03-02 23:42:20 > frontend@0.1.0 start
2023-03-02 23:42:20 > react-scripts start
2023-03-02 23:42:20 
2023-03-02 23:42:57 
2023-03-02 23:42:57 > frontend@0.1.0 start
2023-03-02 23:42:57 > react-scripts start
2023-03-02 23:42:57 
2023-03-02 23:14:40 sh: 1: react-scripts: not found
2023-03-02 23:42:20 sh: 1: react-scripts: not found
2023-03-02 23:42:57 sh: 1: react-scripts: not found
````

## Resources and resource links
![dockerized_frontend](journal/proof/Week1/dockerized_frontend.png)

![Logical Docker images](/journal/proof/Week1/localimages.png)

![Snyk report](/workspace/aws-bootcamp-cruddur-2023/journal/proof/Week1/snyk-conainer-vulnerability-scan.png)

![Pushed to Repo - Frontend] (/journal/proof/Week1/dockerhub-front.png)

![Pushed to Repo - Backend] (/journal/proof/Week1/dockerhub-back.png)

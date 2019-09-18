# Git Practice Guide
## https://learngitbranching.js.org

# ML Trainings:
## https://www.coursera.org/learn/linear-algebra-machine-learning/home/welcome
## https://www.coursera.org/learn/multivariate-calculus-machine-learning/home/info
## https://www.coursera.org/learn/pca-machine-learning/home/info


# Running Flask on Docker Swarm
## https://testdriven.io/blog/running-flask-on-docker-swarm/
## https://testdriven.io/blog/running-flask-on-kubernetes/
## https://github.com/sir-waqas/flask_docker_swarm
## https://code-maze.com/ci-jenkins-docker/
## https://syndicode.com/2019/04/05/ci-cd-pipeline-using-docker-and-jenkins-step-by-step/

#### git remote -v
#### git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
#### git checkout -b master
#### git push -u origin master

### docker login

### docker build -t cheemstb/flask-docker-swarm_web:latest -f ./services/web/Dockerfile ./services/web
### docker push cheemstb/flask-docker-swarm_web:latest

### docker build -t cheemstb/flask-docker-swarm_db:latest -f ./services/db/Dockerfile ./services/db
### docker push cheemstb/flask-docker-swarm_db:latest

### docker build -t cheemstb/flask-docker-swarm_nginx:latest -f ./services/nginx/Dockerfile ./services/nginx
### docker push cheemstb/flask-docker-swarm_nginx:latest



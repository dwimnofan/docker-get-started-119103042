# docker-get-started-119103042
## Dwi Muhamad Nofan

### Requirement
- git installed
- docker installed
- github account
- code editor

#### Preparation
- open terminal/cmd
- clone repo https://github.com/dwimnofan/docker-get-started-119103042
```
git clone https://github.com/dwimnofan/docker-get-started-119103042.git
```

#### Part 1
Start docker/getting-started images
```
docker run -d -p 80:80 docker/getting-started
```

#### Part 2
[Build the app’s container image](https://docs.docker.com/get-started/02_our_app/#build-the-apps-container-image)
[Start an app container](https://docs.docker.com/get-started/02_our_app/#start-an-app-container)
```
docker run -dp 3000:3000 getting-started
```
open your web browser to http://localhost:3000.
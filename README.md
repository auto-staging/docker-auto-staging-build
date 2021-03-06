# Docker Auto Staging CodeBuild Image

> Docker image used in the Auto Staging CodeBuild Job

[Image on Docker Hub](https://cloud.docker.com/u/autostaging/repository/docker/autostaging/auto-staging-codebuild/general)

## Commands

### Build image

``` bash
docker build -t autostaging/auto-staging-codebuild:terraform1x ./terraform1x
```

### Push image to DockerHub

- Make sure you have your DockerHub login configured
  
    ``` bash
    docker login
    ```

- Push image
  
    ``` bash
    docker push autostaging/auto-staging-codebuild:terraform1x
    ```

### Push to AWS ECR

- See `build_for_aws_ecr.sh* to build & push to the public AWS ECR.

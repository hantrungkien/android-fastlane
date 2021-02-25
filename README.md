### Fastlane for Android apps on GitLab

![Docker Pulls](https://img.shields.io/docker/pulls/hantrungkien/android-fastlane.svg)
![Docker Automated](https://img.shields.io/docker/automated/hantrungkien/android-fastlane.svg)
![Docker Build](https://img.shields.io/docker/cloud/build/hantrungkien/android-fastlane.svg)

## Sample usages
### GitLab
*.gitlab-ci.yml*

```yml
image: hantrungkien/android-fastlane:latest

stages:
  - deploy

deploy:
  stage: deploy
  script:
     - fastlane distribute
```

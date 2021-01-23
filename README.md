# Jenkins Kata

Look into the [`labs`](./labs) folder for exercises

## Open in google cloud shell

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://console.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https://github.com/praqma-training/jenkins-katas.git)

Switch to `setup` and spin up the Jenkins server by running:
`docker-compose up -d`

Jenkins will be running on port `8080`, and can be reached by pressing the Web Preview button in the upper right corner of the Cloud Shell window, and selecting `Preview on port 8080`.

| Username | password                         |
| :------- | :------------------------------- |
| admin    | `adminpassword2020` without 2020 |

## Layout of this repository

```bash
.
├── app             # The application itself
├── ci              # Folder for all the ci specific files
├── component-test  # Python component test and setup
├── examples        # Examples of the different exercise solutions and more.
├── img             # Images for the readmes in the labs folder
├── labs            # All different exercises in Jenkins
└── setup           # Setup of jenkins.

```

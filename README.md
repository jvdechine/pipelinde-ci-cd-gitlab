# Deploy Node CI
Deploy Node with CI

In this project I'm showing how to create a Gitlab CI integration with your nodejs application hosted in a linux server.

- Connect to the server using SSH
- Pull repository
- Run npm

It necessary:

- Send the .gitlab-ci file to your repository in Gitlab.
- Create two environment variables: PRIVATE_KEY and IP_SERVER.

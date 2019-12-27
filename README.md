# Jenkins

jenkins(master-slave) + docker

## Deployment

### Docker

- Install docker on all nodes
- create a user 'docker' and add to group 'docker' to run docker containters

### Jenkins

Run jenkins using official docker image `jenkinsci/blueocean`.

### Jenkins slaves

Run jenkins slave using docker image `aeternuss/jnlp-slave` which contains docker cli.

# A Pentest Pivot Example
This is a set of docker containers used for quickly testing pivoting techniques. It goes along with the article on nullsweep about how to employe various pivoting techniques.

[A Pivot CheatSheet for Pentesters](https://nullsweep.com/pivot-cheatsheet-for-pentesters)

## How to run
```bash
docker-compose build
docker-compose up
```

The SSH machine has a user and password defined in the dockerfile. The SSH service is running on localhost port 20022.

The username and password is: pentester/letspivot

### Logging into the SSH machine
```bash
ssh pentester@localhost -p 20022
password: letspivot
```
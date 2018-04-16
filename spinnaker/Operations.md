# Operations

Upgrade Spinnaker to latest

```
sudo apt-get upgrade -y spinnaker
```

Check version of Spinnaker installed

```
dpkg -s spinnaker | grep Version
```

Connect to server via SSH tunnel

```
ssh -i ~/Keys/spinnaker -L 9000:localhost:9000 -L 8084:localhost:8084 -L 8080:localhost:8080 ubuntu@host
```

## Configuring Spinnaker



# odin-recipes
if getting errors with ssh
- check if ssh server is active
```bash
sudo service ssh status
sudo service ssh start
```
- check connection with the github server
```bash
ssh -T git@github.com
```
if still not working
- check firewall and ensure port 22 is open
    -> can create inbound and outbound rules for Port 22


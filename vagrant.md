
#### Enter via 'ssh' to Vagrant VM

- Purpose is to avoid using `vagrant ssh`
- Target VM should be up and running
In folder with .vagrant folder run: 
```bash
vagrant ssh-config > __conf-ssh && ssh -F __conf-ssh default && rm __conf-ssh
```

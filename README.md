# devops-kub-plugin

# "Install" plugin by moving it to a directory in your $PATH
```sh
sudo mv ./kubeplugin /usr/local/bin
```

# Check that kubectl recognizes plugin:
```sh
kubectl plugin list
```

# Now check plugin with example below:
```sh
kubectl kubeplugin <resource_type> <namespace>
```

# linux-annoying-locals
Fix the stupid annoying Locals in Linux


***Run these commands***
```
echo "LC_ALL=en_US.UTF-8" | sudo tee -a /etc/environment
echo "en_US.UTF-8 UTF-8" | sudo tee -a /etc/locale.gen
echo "LANG=en_US.UTF-8" | sudo tee -a /etc/locale.conf
``` 
```
sudo locale-gen en_US.UTF-8
``` 

Congrats, your got rid of it.

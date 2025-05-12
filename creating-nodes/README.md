###

![alt text](image.png)
![alt text](image-1.png)

## add hostname of your choice

## add pass word and click next

![alt text](image-2.png)

## choose template

![alt text](image-3.png)

## Select disk size

![alt text](image-4.png)

## Select no of cores

![alt text](image-5.png)

## Select 'Ram'/ memory size

![alt text](image-6.png)

## choose ipv4 (your network CIDR range)

## IP of your rauter

![alt text](image-7.png)

## DNS leave as it is

## check and confirm details. Click finish

![alt text](image-8.png)

## IT should say 'Test Ok'

![alt text](image-9.png)

## start your node

![alt text](<Screenshot 2025-05-12 at 4.27.23 PM.png>)

1. Default username is always 'root' and use password which you created during the initial stage of creating the node

## if everything goes well you should see you node like this

![alt text](image-10.png)

# Always create a user (there should be no access to the node directly)

## we have created a user name itachi

````bash
adduser itachi

![alt text](image-11.png)

```bash
adduser itachi sudo
# Add user (itachi here.) to sudo group
![alt text](image-12.png)
````

## ssh into your from your personal pc

```bash
ssh your-node-name@your-ip-addr

![alt text](image-13.png)
```

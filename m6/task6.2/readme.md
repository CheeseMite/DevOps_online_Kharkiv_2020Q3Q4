# Task6.2

## Created 3 VMs  
![config](res/1.png)  

## Config of VM1  
![config](res/2.png)
![config](res/3.png)  
## Config of VM2  
![config](res/4.png)  
## Config of VM3  
![config](res/6.png)  
![config](res/7.png)  

## Listed internal networks
![config](res/8.png)  
## Created dhcp server
![config](res/9.png)  
### as a result 
![config](res/10.png)  
## vm2 and vm3
![config](res/11.png)  
![config](res/12.png)  
## Disabled systemd-resolved as it conficts with dnsmasq
![config](res/16.png)  
## Configured dnsmasq as dhcp server
![config](res/13.png)  
### it works!  
![config](res/14.png)  
![config](res/15.png)  

## dnsmasq as dns-caching-server
### set iptables rules
![config](res/18.png)  
### configured resolv.cong on vm1  
![config](res/17.png)  
### result on vm2
![config](res/19.png)  
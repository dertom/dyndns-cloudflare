# dyndns-cloudflare

DynDNS with your own domain!  
script gets your public IP and updates the entry at cloudflare  


## HowTo

create the A entry at cloudflare manually  
download the script  
create the config file (updateDNScloudflare.sh.config) in the same folder as the script  
run the script  
create a cronjob  


## updateDNScloudflare.sh.config  

AUTHKEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx  
DNSENTRY=your.dns.entry  
AUTHEMAIL=your@email.send  

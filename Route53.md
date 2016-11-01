#Spinup EC2 instance
install apache webserver                                                              .    
Start the server                                                                      .
Open port -80                                                                         . 
#create a Loadbalancer                                                                .
Select the security group                                                             .
configure health group                                                                .
Add ec2 instance                                                                      .
#Start creating Route53                                                               .
Enter the domain name and slect type                                                  .
>it create s name server records                                                      .
# Add server name to the hosting site                                                 .
# Configure naked domain name or Adress                                               .
Using create record set                                                               .
Select the Alias and routing policy and press create                                  .

#route 53 routing policies                                                            .
Simple- it is a simple policy it is default policy or single resource                 .
Weighted- it helps to split the traffic between the servers                           .
Latency- it helps to route the tarfic based on the lowest network latency of end user .
Fail over- it helps the route the trafic if one server is failed to another active server .
Geo location- it helps the route the trafic based on the end user location            .



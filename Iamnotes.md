#login in to Aws account and to IAM console
we can change the IAM users sign-in link
>Never use the root acount for any reason and if any key is generated we can get it only once.
#MFA-Multi factor authentication 
It is used for securing the root user acess by activating the diferent types of authentications
1.click on manage MFA.
2.select a virtual MFA device.
3.we can select google authenticator.
4.Scan the qr pic from the phone and give two passwords respectively.
5.Activate the acoount.
#creating individual IAM users
1.select the create individual IAM users (manage users) in security status. 
2.select the create new users.
3.Enter the user names and create.
4.you have to download the credentials and save it securly.
5.After creating the user we have to assing the pasword to it by clicking on the check box 
  beside the user and the select the option manage passwords in user actions.
6.in this we have two options assing auto generated or custom psswd.
7.After creating user will not have any permissions to it until we give it by assining the policies.
8.select the policies and select the list given and attach them to the users.
9.we can assign the policies by creating groups and adding users to it.
#Apply an IAM password policy -we can give by slecting manage password policy.
 

# LaunchingEC2

Launching an EC2 Instance in Amazon Web Services


Using AWS management console, I selected the virtual machine with ec2 instance I wanted which is a Linux machine through the wizard which helps guiding you through the initial setup process.

<img width="965" height="176" alt="image" src="https://github.com/user-attachments/assets/d3faccc9-81d5-4c40-8b4a-2b60a4f0e348" />

Picked the default instances type which was the General Purpose which is free to use, adding 20GB to it, and tags.
 
<img width="934" height="222" alt="image" src="https://github.com/user-attachments/assets/ceebbe12-f025-4a12-896d-33dd3eb97b35" />
 
<img width="873" height="291" alt="image" src="https://github.com/user-attachments/assets/622fe6cd-367d-453f-8766-cca4bd56abc1" />

 
For my security group I selected SSH connections with any source then I would review my settings from what I created. I need a keypair in order to enter my instances that’s where the keypair comes into play.

<img width="570" height="353" alt="image" src="https://github.com/user-attachments/assets/404b3e45-0fe4-42ca-ae1a-f2a8e2ab901f" />

I wasn’t aware at first until I used amazon guide pages to help create one.

<img width="975" height="281" alt="image" src="https://github.com/user-attachments/assets/a8adc064-364d-4c42-b84c-48aeecaec284" />

<img width="493" height="434" alt="image" src="https://github.com/user-attachments/assets/babe8535-d23b-4330-8ae9-cadbbda4e022" />

Now here I connected to my instances with a tool called PuTTY which I could use SSH protocols.

<img width="583" height="108" alt="image" src="https://github.com/user-attachments/assets/ad08a13c-d91c-4edd-8bdc-3c5de7a7c268" />
 
PuTTY doesn’t natively support the private key format (.pem) generated from amazon EC2 that we downloaded, so we going to use puttygen to convert the AWS key to a .ppk format which is required from putty. This is a must!!

<img width="634" height="244" alt="image" src="https://github.com/user-attachments/assets/8be204e4-7307-45b6-9253-34e7cd17d16f" />
 
I uploaded the key file from my computer that I downloaded and loaded it into the generator.

<img width="444" height="577" alt="image" src="https://github.com/user-attachments/assets/96720815-cccc-4442-af06-30045291a3ba" />

I got an alert the first time I connected to the instances from the machine but after it’s normal to just start without any alerts.

<img width="430" height="309" alt="image" src="https://github.com/user-attachments/assets/7b356d66-ac94-4eb0-8abe-be26a7b70071" />

The username for my newly created instances is ec2-user which is default.

<img width="502" height="427" alt="image" src="https://github.com/user-attachments/assets/eb7648b5-7b1b-4ea6-baf1-046c4e72172e" />

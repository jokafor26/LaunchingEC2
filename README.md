# LaunchingEC2

Launching an EC2 Instance in Amazon Web Services
Using AWS management console, I selected the virtual machine with ec2 instance I wanted which is a Linux machine through the wizard which helps guiding you through the initial setup process.

 ![Image](https://github.com/user-attachments/assets/acc1f093-3890-49b9-8146-c8c18bd676c4)

Picked the default instances type which was the General Purpose and it’s free to use and adding 20GB to it as well as adding tags.
 
![Image](https://github.com/user-attachments/assets/54a7eeb1-82dc-4010-98c4-878d56b6745b)
 
![Image](https://github.com/user-attachments/assets/b45fa31e-f6a3-4f80-893e-514fbe0ca4f3)

![Image](https://github.com/user-attachments/assets/a9532b3a-0990-4d86-893c-ba5576843402)
 

For my security group I selected SSH connections with any source then I would review my settings from what I created. we need a keypair in order to enter my instances that’s where the keypair comes into play.

![Image](https://github.com/user-attachments/assets/b94260b7-4805-4efc-853e-b3a013bad9ab)

I needed a keypair in order to enter my instances that’s where the keypair comes into play. Wasn’t aware at first until I used amazon guide pages to help create one.

 ![Image](https://github.com/user-attachments/assets/abac3688-0a7a-4a88-be21-dc6e004518a8)

 ![Image](https://github.com/user-attachments/assets/ec9c3e8e-dac3-40af-afad-65db67a2b1a5)

Now here I connected to my instances with a tool called PuTTY which I could use SSH protocols.

![Image](https://github.com/user-attachments/assets/a0e042d6-9d65-4c85-b9f3-b2f45aed8c23)
 
PuTTY doesn’t natively support the private key format (.pem) generated from amazon EC2 that we downloaded, so we going to use puttygen to convert the AWS key to a .ppk format which is required from putty. This is a must!!

 ![Image](https://github.com/user-attachments/assets/daa5116e-62aa-40b1-86d1-92c620aa4db9)
I uploaded the key file from my computer that I downloaded and loaded it into the generator.

 ![Image](https://github.com/user-attachments/assets/3d75cfb4-c4d3-4db8-bb1e-310371d8369f)

 ![Image](https://github.com/user-attachments/assets/52ea8a7a-6cb0-4d38-8f27-4df4972984ec)

I got an alert the first time I connected to the instances from the machine but after it’s normal to just start without any alerts.

 ![Image](https://github.com/user-attachments/assets/dcb8276a-ea6f-4066-ad4f-509d8f811edb)

The username for my newly created instances is ec2-user which is default.

 ![Image](https://github.com/user-attachments/assets/2bbbd2a3-577b-4b58-b222-ecd0f00f9da3)
































 










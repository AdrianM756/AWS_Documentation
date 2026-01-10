## Create Security Group

On this demo, we will create a security group under default VPC.
<br>

On the search bar, type and select **Security groups**.

<img width="913" height="184" alt="image" src="https://github.com/user-attachments/assets/b9c97289-9702-465c-b24b-b8ad975c26fe" />
<br>

On the upper-right corner, click on **Create security group**.

<img width="1605" height="111" alt="2026-01-10_12-06" src="https://github.com/user-attachments/assets/737582a9-3bcf-40d4-bbb6-a884aa2bcbf9" />
<br>

We will name the security group as ```xfusion-sg``` and the description as ```Security group for Nautilus App Servers```.

<img width="1042" height="347" alt="2026-01-10_12-10" src="https://github.com/user-attachments/assets/cd852484-0896-4e83-a859-6a6250756f11" />
<br>

On the **Inbound rules**, add the inbound rule of type ```HTTP```, with port range of ```80```. Enter the source CIDR range of ```0.0.0.0/0```. Next, Add another inbound rule of type ```SSH```, with port range of ```22```. Enter the source CIDR range of ```0.0.0.0/0```.

<img width="1586" height="212" alt="image" src="https://github.com/user-attachments/assets/f11ff736-7946-49d8-8ba0-5179645dc914" />
<br>

Scroll down and on the lower-right corner, select **Create security group**.

<img width="356" height="95" alt="2026-01-10_12-14" src="https://github.com/user-attachments/assets/d6042ee2-be7a-48d9-aaae-88c19595ad9c" />
<br>








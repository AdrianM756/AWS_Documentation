## IAM Policy: Create Read-only Access on EC2

On the AWS Console search bar, type ```IAM```.

<img width="711" height="143" alt="image" src="https://github.com/user-attachments/assets/313fa47a-b4f5-4a17-8cd2-84815bcee986" />
<br>
<br>

Under ```Access Management```, select ```Policies```.

<img width="221" height="202" alt="image" src="https://github.com/user-attachments/assets/18ecac4f-cc02-4966-b27c-e5b9320b38a3" />
<br>
<br>

Click ```Create policy```.

<img width="110" height="63" alt="image" src="https://github.com/user-attachments/assets/345c4205-bd67-470a-9cd1-b0c022beabda" />
<br>
<br>


For the service, we will select ```EC2```. this policy must allow users to view all instances, AMIs, and snapshots in the Amazon EC2 console. To to that, we will choose the following:

* DescribesImages
* DescribeInstances
* DescribeSnapshots

Once done, click on ```Next```.

<img width="1619" height="836" alt="image" src="https://github.com/user-attachments/assets/e8272147-520f-4ff1-beca-3de168d2cf91" />
<br>
<br>

We will then name this ```iampolicy_james``` then click ```Create policy```.

<img width="320" height="181" alt="image" src="https://github.com/user-attachments/assets/ba68b12a-a1c6-4e90-9a2e-a202a29160a3" />
<br>
<br>





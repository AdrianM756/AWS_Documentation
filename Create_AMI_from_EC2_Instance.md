## Create AMI from EC2 Instance

The process of creating an Amazon Machine Image (AMI) from an existing EC2 instance is essentially taking a "snapshot" of the server's current state. This allows you to clone the instance or keep a backup of its configuration.
<br>

## How it Works
When you create an AMI, AWS takes a snapshot of the instance's root volume (and any other attached EBS volumes). By default, AWS will reboot the instance to ensure data integrity during the snapshot process, though you can choose to override this option by unclicking the checkbox.

## Demo

On the AWS Dashboard, search and select ``EC2``.

<img width="847" height="154" alt="2026-04-25_18-54" src="https://github.com/user-attachments/assets/1d2d7b17-3a65-4d9a-807d-b46a6f5fbaf8" />
<br>
<br>

Under ```Instance```, click on the ```Instance ID```.

<img width="600" height="271" alt="2026-04-25_18-57" src="https://github.com/user-attachments/assets/3dfff84c-71fe-40e3-83e1-4aa0415df40a" />
<br>
<br>

Navigate to ```Actions``` > ```Image and templates``` > ```Create image```.

<img width="483" height="231" alt="2026-04-25_18-59" src="https://github.com/user-attachments/assets/dde46d42-ef76-47b0-9478-1c99c94151cc" />
<br>
<br>

Name it as you desire then leave it as default. Once done, click ```Create image```.

<img width="1407" height="830" alt="2026-04-25_19-01" src="https://github.com/user-attachments/assets/302796a5-3b7b-4d8c-be07-4129474ccfe0" />
<br>
<br>














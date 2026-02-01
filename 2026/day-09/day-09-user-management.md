1.Users & Groups Created
Users:
tokyo
berlin
professor
nairobi

Groups:
developers
devops
project-team

2.Group Assignments
developers:
tokyo
berlin

devops:
professor

project-team:
tokyo
nairobi

3.Directories Created (with Permissions):

Directory	Owner	Group	Permissions	Purpose
/dev-work	root	developers	770	Developer workspace
/devops-area	root	devops	750	Admin-only access
/project-data	root	project-team	770	Shared project files

4.Commands Used
Add group:
sudo groupadd developers

Add user:
sudo useradd tokyo

Add password:
sudo passwd tokyo

Add users to groups:
sudo usermod -aG developers tokyo

Create directories:
sudo mkdir /dev-work /admin-area /project-data

Assign group ownership:
sudo chown :developers /dev-work

Set permissions:
sudo chmod 770 /dev-work

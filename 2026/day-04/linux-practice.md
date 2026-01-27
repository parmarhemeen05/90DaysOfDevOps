1.Check running processes
top 
2.Inspect one systemd service 
systemctl status ssh
3.Capture a small troubleshooting flow
Check status:-
systemctl status ssh
Restart service:-
sudo systemctl restart ssh
Verfiy service:-
systemctl status ssh
Check if SSH port is listening:-
ss -tulnp | grep :22

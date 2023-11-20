SFTP stands for Secure File Transfer Protocol. 
It is a secure way to transfer files between two remote systems. 
SFTP is a separate protocol packagedbuilt into SSH that can implement FTP commands over a secure connection

1.To establish an SFTP connection, you need to have SSH access to the remote server. 
You can authenticate with passwords by default, but it is recommended to create SSH keys and transfer your 
public key to any system that you need to access. This is much more secure and can save you time in the long run 
1.Here are the steps to connect with SFTP:

Test SSH access with the following command: ssh sammy@your_server_ip_or_remote_hostname. 
If that works, exit back out by typing: exit.
Establish an SFTP session by issuing the following command: sftp sammy@your_server_ip_or_remote_hostname. 
You will connect to the remote system and your prompt will change to an SFTP prompt

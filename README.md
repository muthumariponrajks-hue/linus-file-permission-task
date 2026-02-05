Linux File Permission Task
Task: 
Create a file with .txt extension and set permissions:
Owner: read, write, execute
Group: read, write
Others: read only
Commands used:
touch /home/ubuntu/demo.txt
chmod 764 /home/ubuntu/demo.txt
stat /home/ubuntu/demo.txt
Output:
Access: (0764/-rwxrw-r--)

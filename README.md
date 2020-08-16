# FTP-Client-Server-Software
Implemented a simple version of FTP client/server software.It consists of two programs: ftpclient and ftpserver.

## Description 
1.  First, the ftpserver is started on a computer. 
2. It listens on a certain TCP port. Then, the ftpclient is executed on the same or
a different computer
3. The server’s address and port number are supplied in the command
line, for example, “ftpclient sand.cise.ufl.edu 5106”. 
4. The client will prompt for username and password. 
5. After logon, the user can issue three commands at the client side
  - “dir” to retrieve the list of file names available at the server
  - “get <filename>” to retrieve a file from the server 
  - “upload < filename>” to upload a file to the server.

## Built On
- Programming language: Java
- Operating System: Windows 
- Programming Tool: Eclipse
  

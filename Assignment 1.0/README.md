# ACA-FSWD-2021


## Command Prompt

Command Prompt is a command line interpreter application available in most Windows operating systems .It is highly popular because of the advanced commands it can run.But it is not just built on advanced commands,it is quite efficient in performing basic operations as well.
Following are some of the important **CMD commands**
  - **CD**(Change Directory): This command enables you to change the current directory i.e. to navigate to navigate to another folder.

    - CD takes you to the top of the directory tree. 
    - "CD Folder" with subfolders seperated by backslash character enables you to navigate to that specific folder in the drive.
    - CD.. enables you to go one folder up.
    
  - **D:/C:** : This command enables you to change the drive. 

  - **DIR** : This command is used to view the contents of the directory.

  - **MKDIR** : This command is used to make a new folder in the current directory.The syntax of this command is "MKDIR Folder".

  - **REN** : This command is used to rename a folder. To rename a folder, type "ren Folder NewFolderName".To rename a file, use "ren filename.extension newname.extension".

  - **COPY** : The copy command is used to copy files from one location to another.To use this command,type "copy location\filename.extension newlocation\newname.extension.

  - **XCOPY /s /i** : This command is used to copy a folder and its contents from one folder to another.

  - **DEL** : This command is used to delete files from the folder that you have created. The command "del folder" enables you to delete all files from the specified folder. Remember to confirm the deletion process by typing "y".
     - DEL *.DOCX- This is used to delete all files with the extension "DOC".
     - DEL Test*.*- It deletes all files beginning with "TEST".
     - DEL *.*- It deletes all the files from the current folder.

  - **RD** : This command enables you to delete an empty folder.
  - To launch an app with Command Prompt, navigate to the folder that contains the application and type the program's name(for example, **mspaint.exe**)

  - **help** : This command is used to get help in the Command Prompt.

_Note that Command Prompt is not case sensitive_


## Client-side

Client-side refers to the actions that are performed by the client.A client is a computer application, like a web browser that runs on the user's computer,smartphone or any other such device and links to the server.  


## Server-side

Server-side refers to operations that are performed by the server . A server is a computer application, such as a web server.Operations may be performed server-side because they require access to information or functionality that is not available to client, or because performing such operations on client side would be slow, insecure or unreliable.Server-side operations include those performed in response to client requests as well as those which perform maintenance tasks. 

## HTTP Protocols

HTTP is a protocol that is used by web browsers and web servers to communicate with each other over the Internet. It is an application level,connectionless text based protocol.The applications here are web browsers and web servers.Clients send HTTP request(via the protocol stack) to web servers for web pages,images and other web elements.The web server receives the request and checks for the desired page. If found, the request is serviced by the server otherwise an error, "Page Not Found" is sent.


## http vs https

HTTP stands for **Hypertext Transfer Protocol** and HTTPS stands for **Hypertext Transfer Protocol Secure** HTTPS is basically an HTTP protocol with additional security. The s in HTTPS stands for Secure . The most important difference between the two protocols is the **SSL certificate**. The main problem with the HTTP protocol is that the information that flows between the server and the browser is not encrypted and hence can be easily stolen. HTTPS protocols use an SSL(secure sockets layer) certificate which establishes a secure connection between the server and the browser and protects any sensitive information from being stolen. Even if someone manages to steal the data being transmitted, the person would not be able to understand it due to its encryption.Although the SSL feature in HTTPS makes the page loading slower as compared to HTTP.


## Frameworks vs Libraries

### Library
A library provides a set of helper functions/objects/modules which your application code calls for specific functionality.Libraries typically focus on a narrow scope.

### Framework
Framework has defined open or unimplemented functions or objects which the user writes to create as custom application. It has a wider scope and includes almost everything necessary to make a user application as per his own needs.

_The key difference between Libraries and Framework is the **Inversion of Control** or IoC. When we call a method from a library,we are in control. But in framework,the control is inverted i.e. the framework calls us._








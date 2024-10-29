# ForumWebViewer

![Screenshot](https://github.com/kidscripter/Forum-Web-Viewer/blob/main/Screenshot.PNG?raw=true)  
![Screenshot](https://github.com/kidscripter/Forum-Web-Viewer/blob/1b3b7175831ee2fefd8f3f0b651c17c607bfd1bd/Screenshot%202024-10-29%20163028.png)  
Forum Web Viewer is a web based viewer that uses the Zeiss Forum database and image repository.  
The build is setup to use Azure Enterprise Applications to register it with Entra.  
  
1. Add a read only user to the Forum database: https://stackoverflow.com/questions/1708409/how-to-start-mysql-with-skip-grant-tables  
2. To get started you will need to edit the following in the web.config  
 2a. Edit the connectionString with your forum database information.  
 2b. Edit appSettings to match your enterprise application configuration.  
  
Tested with Forum 4.2 running on IIS.

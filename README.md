# ApacheHttpdSwagger
The latest version of Apache and the Swagger Editor combined in a single package to make working with the Swagger Editor web application easier.  The Swagger Editor is a web application, designed to work in a web browser deployed on a server.  This allows you to quickly and easily create a local server and take advantage of native Swagger features and best practices that are based on http requests for additional Swagger component files.  The is especially helpful and a best practice when Swagger files start to become large and maintenance becomes a more difficult task in real world application of Swagger definition file(s).  Enjoy!  And have a great day!

👍😊

Andrew

# Cookbook:
This cookbook describes how to install the Apache Swagger Editor on your local workstation.  This is important as the Swagger Editor while functional to a limited degree on your local file system in a web browser is designed to be a web application running on a web server.  This is important to take advantage of features such as http references from Swagger files to other modular or shared Swagger json files by design, respectfully.  This modular pattern allows for better maintenance of more complex Swagger files and results in smaller more manageable Swagger components.  Further, true sharing of definitions between Swagger files allows for full automatic synchronicity of key standards that are designed to be synchronized at all times between Swagger files as major version shared standards.  The goal is to follow Swagger best practices, and also simplify and improve maintenance and modification of the Swagger files over time.

## Windows 10, 64bit:
1. Download the latest distro.  It is located in ApacheHttpdSwagger-1.0/distro/Windows-10-64bit/ directory.  Find the latest version
1. Unzip the zip file, you will see a directory called "Apache Software Foundation".
1. Copy the "Apache Software Foundation" folder to the following path:  C:\Program Files\
1. Open a command prompt and type the following commands:
    * `CD "C:\Program Files\Apache Software Foundation\Apache 2.4\bin" [press enter]`
    * `httpd.exe -k install [press enter]`
1. Open your favorite web browsers, and enter the following URL:
    * http://localhost/swagger-editor/
1. You should see the Swagger Editor load!
1. Bookmark this page as your local Swagger Editor Smile :)👍

### Congratulations, your Apache Httpd Swagger Editor is installed!
### NOTE:  With this configuration, the Apache Swagger Editor is running as a Service in your Windows installation.  This means it will automatically started and available when you turn on your workstation.

# Apache Configuration Details:
## Configure Work Directory Mod:
Directory browsing is also enabled in this configuration so that you can quickly confirm the web server / browser view of your local Swagger files.  You can modify your Swagger files in your file system editor of choice, save, then hit reload in the web browser and see your changes instantly reflected.  You can configure Apache to reference any location in your local workstation.  To change the path, refer to the following instructions for your work directory

## Add more Mods: :-)
All <your mod>Mod.conf files should be placed in the conf/mods/ directory.  These will automatically be referenced at Server start time or restart time.

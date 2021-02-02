# How to have multiple Teams application on Desktop via Electron

Please install NodeJS
Once Nodejs is installed in your system open the command line and execute the command below.

    npm install -g nativefier


After that look for your tenant

 ![Tenant](https://github.com/vivesg/electronteamspackage/blob/main/tenant.jpg)

Get your tenant ID

Then you need to run 

Create a folder and run

    nativefier.cmd https://teams.microsoft.com/_?tenantID=YOURTENANTID --name "NAMEOFAPP" --internal-urls .* --icon "Logo.ico"

There you go you are going to get a .exe app

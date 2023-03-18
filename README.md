# Odoo-addons-dev
Add-ons development environment template for Odoo's custom modules that combines VSCode and Docker.  


# Get Started 
This template is add-ons development environment template for Odoo's custom modules.

With the combination of VSCode and Docker, you can easily build add-ons development environment for Odoo's custom modules and start developing right away. Of course, you can also verify the operation of standard Odoo applications.

Install the following tools.  

1. [git](https://git-scm.com/)
1. [VSCode](https://code.visualstudio.com/download)
1. [Docker](https://www.docker.com/)


# How to use

## Using this template

1. Open the repository on github.  
   https://github.com/jp-rad/odoo-addons-dev

1. `Use this template`
   Click `Use this template`.  
   [Here - https://github.com/jp-rad/odoo-addons-dev/generate](https://github.com/jp-rad/odoo-addons-dev/generate)


## git clone

1. Open the command prompt and run below commands.

```CommandPrompt.cmd
mkdir c:\workgit
cd c:\workgit
git clone <your GitHub Code URL>
```

## VSCode, Reopen in Container

1. Open the git cloned folder in VSCode.  
1. Install the "Remote - Containers" extension to VSCode.
1. An icon for the extension "Remote - Containers" will be added to the bottom left corner of VSCode, click on that icon.  
1. Select "Remote-Containers: Reopen in Container" from the list.
1. The Docker container will start and you will be able to develop remotely from VSCode.


## custom_addons

1. You can develop your own add-ons in "custom_addons" folder, see the Odoo tutorials, etc.  
https://www.odoo.com/documentation/master/developer/howtos/backend.html
1. To add a new empty module, issue the following command
```
/opt/odoo/odoo/odoo-bin scaffold <module name>
```

## Log in to Odoo

1. Click on the "Debug and Run" icon on the left of VSCode, and with "Odoo addons" selected, click on the "Start Debugging" icon to start Odoo.
1. Once Odoo is running, open your browser, access Odoo, and log in (admin/admin).  
http://localhost/

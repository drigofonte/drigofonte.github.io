# Instructions

This is a Webflow based static website. Use the steps below to regenerate it.

1. Publish the site on Webflow
2. Use the following ```wget``` command to create an offline mirror copy
```
wget --recursive --page-requisites --adjust-extension --span-hosts --convert-links --restrict-file-names=windows --domains <subdomain>.webflow.io,uploads-ssl.webflow.com --no-parent <subdomain>.webflow.io
```
3. Move the contents of the ```<subdomain>.webflow.io``` folder to the root project folder.
4. Update the path to images and other assets for the files in the ```projects``` subfolder
4. Unzip the main ```CSS``` and ```JS``` files located in the ```uploads-ssl.webflow.com``` folder
5. Update the path of the ```CSS``` and ```JS``` references in all HTML files
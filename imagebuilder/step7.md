# Monitor image builds

At this point, you have queued your image to be built.  You can monitor the
progress of the build by looking at the *Images* tab on the 
*example-http-server* page.

![Select Blueprint Images Tab](./assets/Select-Images-Tab.png)

The *Images* tab contains a list of all the images built from this blueprint.
You will see that the one you just created is likely still *Image build pending* but should transition to *Image build in progress* status, as pictured 
below.

![Build In Progress](./assets/Build-in-Progress.png)

>**NOTE:** At anytime during or after the build, you can review the log messages by using the *Logs* button.  For example, if there is a problem with the build which causes it to fail.

Once the build completes the status will update and the additional
options will allow you to download the completed virtual machine image.

![Build Completed](./assets/Build-Complete.png)


# Supr Software Supreme Guide

## Tasks

---

## Profiles
### Creating a profile
*Your profile information is saved on your local machine. Profile information is only used for purchasing items / registering for Instore Signups.*

1. Click the '+' icon located on the top right of the table.
  * You can click anywhere outside of the dialog or the 'x' icon to automatically cancel and close the dialog. Your profile will **not** be saved. 
2. You can edit the name by clicking the name at the top of the dialog. 
  *  If the profile name matches another profile, the previous profile will be overwritten.
3. Fill out the form, making sure to follow the format as expressed by the placeholder text.
  * **10-digit phone number with no spaces**
  * **Card Number, spaces included**
4. Click 'Save Profile' to save your profile.

### Importing profiles
1. Click the import icon located towards the bottom of the profile table.
2. Select the .json file that contains the profile data.
  * **If the .json file is not formatted correctly then profiles will not be imported.**
3. Click 'Open'. Profiles will be imported from the specified .json file.

### Exporting profiles
1. Click the export icon located towards the bottom of the profile table.
2. Name the .json file and click 'Save'.
3. Your profiles will be exported to a .json file.
---

## Settings
### Deactivating your machine
Currently each license key is allowed 1 activation per machine. Deactivate your machine if you plan on using this software on another machine.

1. Click deactivate. You will be signed out and required to sign in again in order to use this software.

### Adding Proxy Lists
Proxy lists are saved to your local machine. 

1. Paste in your proxies one proxy per line in the textarea to the right of the proxy list table.
  * You will not be able to save the proxy list if improperly formatted.
  * Proper format is as follows: **proxy:port** or **proxy:port:username:password**
2. Hit 'Save' to save your proxy list.

### Editing Proxy Lists
Localhost proxy list is not editable. The selection of this proxy list when creating tasks will ensure that the task is using the IP of your local machine to execute the task.

1. Click the pencil icon in order to load the proxy list to the textarea located on the right.
2. Once changes are made hit 'Save'.
  * A confirmation dialog is presented when a proxy list will be overwritten.

### Deleting Proxy Lists
Localhost and Services proxy lists are not able to be deleted. These lists are necessary to certain software functions.

1. Click the trashcan icon in order to remove and delete the proxy list.

### Importing Proxy Lists
1. Click the import icon located towards the bottom of the proxy list table.
2. Select the .json file that contains the proxy list data.
  * **If the .json file is not formatted correctly then proxies will not be imported.**
3. Click 'Open'. Proxies will be imported from the specified .json file.

### Exporting Proxy Lists
1. Click the export icon located towards the bottom of the proxy list table.
2. Name the .json file and click 'Save'.
3. Your proxies will be exported to a .json file.

### Adding Discord Webhook
This will be used in order to notify you for successful checkouts.
1. Paste your discord webhook url and click save.
2. Your webhook will be saved and tied to your license key.
---

## Captcha
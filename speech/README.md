# Getting started with speech commands

**Setup**

1. Go to https://git-scm.com/download/win to download and install 64-bit Git for windows
2. Accept all installer defaults and finish installation
3. Go to the Start menu and type *git bash* into the search bar, then run *git bash*
4. In *git bash*, type ```cd ~``` to change into your home directory.
5. Type ```mkdir codeHome``` to create a directory for your coding projects. Or if you already have a directory for your coding projects, type ```cd *projectsdir*``` where *projectsdir* is your coding projects directory.
6. Clone this project into your local directory by typing

```git clone git://github.com/abf149/gittrains.git```

7. Type ```dir``` and you should now have a ```gittrains``` directory. 
8. Type ```cd gittrains/speech``` to change into the speech commands directory.
9. Type ```explorer .``` to open this directory in Windows Explorer
10. You should see an ```index.html``` file. Point Google Chrome to this file by copying the full directory path from the address bar of Windows Explorer and pasting it into Internet Explorer along with "index.html"

**Run**

1. When ```index.html``` loads in your browser it may ask to use your microphone. Press *accept*
2. Say *up*, *down*, *left*, *right*, or *clear* and you should see the dot on the screen following your directions.

**Monitoring output in Google Chrome**

1. In the top-right of Google Chrome you should see a vertically-oriented ```...``` which is the browser menu. Click this menu and choose **More tools > Developer tools**. This will open up the developer tools panel which has a menu along the top for *Elements*, *Console*, *Sources*, ...
2. In the menu at the top of developer tools, choose *Console*
3. Continue speaking into the microphone and you should see a running list of your commands

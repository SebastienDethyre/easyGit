# Easy Git !
A dialog box to ease the use of Git for Linux\n
```quickGit``` is a small version of the main script```gitDialog```

This little script works better with aliasses to access it from any local Git repository. (```aliasName='~/bin/easyGit/./gitDialog'```)
  - Needs to be installed in the ~/bin directory :

    ```mkdir ~/bin/easyGit && git clone https://github.com/SebastienDethyre/easyGit.git ~/bin/easyGit```
  - Requires the Zenity library : https://doc.ubuntu-fr.org/zenity

To avoid having to use Tab to confirm the width of the Files Manager Window ("Fichiers" -> "Largeur") once choosen,
especially to avoid using both hands, you'd probably want to modify the /usr/locale/zenity.ui file, 

around line 49 and before ```</object>```, add this one :
    ```<property name="has_default">True</property>```


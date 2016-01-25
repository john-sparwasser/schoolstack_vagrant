# schoolstack_vagrant
This holds the puphpet config.yaml for schoolstack

**Steps to get up and running**

-   Copy the raw config.yaml
-   Go to http://puphpet.com
-   Paste in the config.yaml, the site should detect this.
-   Click the green button until it says to download your vagrant.
-   Download the vagrant
-   Unzip the archive and rename the folder to schoolstack.
-   Place the folder in your a sensible place; I like to put my vagrants in ~/vagrant.
-   CD into the folder you just moved.
-   ln -s /path/to/schoolstack/folder
-   vagrant box update
-   Then just run vagrant up

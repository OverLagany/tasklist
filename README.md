# A task management module for Roundcube

This is a fork of a kolab/tasklist roundcube plugin aimed to work with JodliDev/calendar, roundcube calendar that supports CalDAV.
Basically this fork just updates dependencies of the original plugin

# INSTALLATION
```
cd /pathTo/roundcubemail

composer config repositories.tasklist vcs https://github.com/OverLagany/tasklist
composer require kolab/tasklist

bin/initdb.sh --dir=plugins/tasklist/drivers/database/SQL
```

# IMPORTANT

This plugin doesn't work with the Classic skin of Roundcube because no
templates are available for that skin.

Use Roundcube `skins_allowed` option to limit skins available to the user
or remove incompatible skins from the skins folder.



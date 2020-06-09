# Wordpress Install Script

This bash script is simplify your life to install latest Wordpress site from CLI.

It's downloads latest version from Wordpress.org
Unpack downloaded file, move all files to root folder, cleanup all unnecessary folder and archive.
Create new database and user for created site, generate unique password for database and show it in CLI as result.

## How to install

Put iWPInstall script file to bin folder: 
```
mv iWPInstall ~/bin/
```

Apply required permission: 
```
chmod 755 ~/bin/iWPInstall
```

## How to use?

Go to Wordpress folder and use following command:
```
iWPInstall dbname
```

Sample of output:
```
Downloading Wordpress
Extracting...
Cleanup...
Apply Folders and Files Permissions!
Creating database...
DBNAME: dbname
DBUSER: dbname
DBPASS: 707assfc41160d23be7d7e
Done!
```

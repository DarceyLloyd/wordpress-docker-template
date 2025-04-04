# Wordpress Docker Template

## Information
Docker dev environment for Wordpress testing and development.

## Usage

1. Install docker desktop and run it (you will need a docker account)
2. Download this git repo zip and extract at a low directory level as close to the root of the drive as possible as wordpress directory and file names can easily exceed windows path and file name limits
3. Open a CMD / Terminal / Shell window and CD to the path you extracted the zip file

eg
```
cd d:\mywpsite
```

4. Now type in
```
u
```
or
```
u.bat
```
If you want to use docker directly type in
```
start /B "" docker-compose up --build
```

<br>
Your website will now be available on the web address 127.0.0.1 or localhost in the web browser.

You will also have PHPMyAdmin on 127.0.0.2
<br><br>

On first run you will be prompted to setup wordpress, enter the following details:


```
Database name: wp_db
Username: root
Password:
Database host: mysql
Table prefix: wp_
```

NOTE: The password field should be blank

Then wordpress will guide you through the rest...

<br><br>

## To shutdown

1. Type in the CMD / Terminal / Shell window you have used the following:
```
remove
```
or
```
remove.bat
```

2. Close the CMD / Terminal / Shell window
3. Exit docker desktop (note it minimises to icons bottom right on windows, just right click icon and choose "quit docker desktop")



<br><br>

## To restart from where you left off

1. Open a CMD / Terminal / Shell window
2. CD to the location you extracted the zip file
3. Type i nthe following
```
u
```
or
```
u.bat
```

4. Go to your browser and type 127.0.0.1 or localhost




<br><br>

## To start fresh
Follow the steps above for remove, close the CMD / Terminal / Shell window and delete the folder from your computer via your typical file browser. Then go to step 2 in in the usage guide above

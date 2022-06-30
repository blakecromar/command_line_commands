# Command Line Actions

## Bash

### Go into a folder

Note: You can list just a folder if you are already in it's directory. <br>
Note: Two dots `..` signal going up one folder

```
cd [folder or directory]
```

```
cd ..
```

### View all files and folders of a directionry

```
ls
```

### How to check where your virtiual enviornment is located on your computer

```
where python
```

### How to check where you are on your computer
```
pwd
```

### How to clear the terminal
```
clear
```

### Determine user within the terminal
```
whoami
```

### Determine if you can connect to a website from where you are at
```
ping [website]
```

### How to terminate a process on command line
Note: This is the command for Mac users

```
control+c
```

### How to give user reading permissions to a file
```
chmod 0400 [file_name]
```

### How to exit out of a user session on terminal
Use this command to exit out of an instance user session.

```
exit (or control+d) | Used to exit out of instance.
```

### How to list all processes related to a port number
```
lsof -i -n -P | grep <PORT NUMBER>
```

### How to kill a process related to a port 
```
Note: If you want to kill a process related to a port search for all process with `lsof -i -n -P | grep <PORT NUMBER>`

kill <PROCESS ID> 
```

## Python

### How to check your python version

```
python --version
```

### Creating a virtual envioronment
Note: You can specify the specific version of python you would like to use. <br>
Note: Once the python version is specifically decided upon you can't change it for the environment. <br>
Note: If you don't list a version it will automatically choose a recent `python` release.

```
python -m venv ~/.[your-repo-name]
```

```
python[version-number] -m venv ~/.[your-repo-name]
```

### Activating a virtual envioronment
```
source ~/.[your-repo-name]/bin/activate
```

### How to deactivate virtual envioronment
```
deactivate
```

### How to install a package to environment

Note: `--upgrade` upgrades a packages to the newest version. <br>
Note: You can modify a package version number or have the package come installed with a specific version with `==`

```
pip install [package-name]
```

```
pip install [package_name] --upgrade
```

```
pip install [package_name]==[version_number]
```

### How to add all packages from requirements.txt file to environment

```
pip install -r requirements.txt
```

### How to unintall a package

```
pip uninstall [some-package-name]
```

## How to view all packages in an environment
Note: `--outdated` lists just packages that can be updated

```
pip list
```

```
pip list --outdated
```

### How to check your pip version
```
pip --version
```

### How to update pip
```
python -m pip install --upgrade pip
```

## Authors

* **Blake Cromar** - *Initial work* 

## Acknowledgments

* (None Listed)

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
## Python

### Creating a virtual envioronment

```
python -m venv ~/.[your-repo-name]
```

### Activating a virtual envioronment
```
source ~/.<your-repo-name>/bin/activate
```

### How to deactivate virtual envioronment
```
deactivate
```

### How to install a package to environment

Note: `--upgrade` upgrades a packages to the newest version

```
pip install [package-name]
```

```
pip install [package_name] --upgrade
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

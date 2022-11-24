# Sample insider engine package
Last Insider engine version -> [github page](https://github.com/almartdev/insiderengine)

#### Insider engine 0.5 doesnt have this feature yet. It'll be able on Insider engine version 0.6 or newer.

Insider engine demo package is a sample package that you can import into your projects and use tools that are not installed in insider engine. To import a package look at all this stuff down here! You will need to have installed [git](https://git-scm.com/downloads) to import them.

# Import guide
Open your project in the sandbox editor and, on the menu bar, go to ```file``` > ```import package```, write the https or ssh to the package, like this github repository
```
https://github.com/AlmartDev/demo-package.git
```
or with SSH
```
git@github.com:AlmartDev/demo-package.git
```
and then click the import button.
the package will be imported to your project. 

  ## Import package window
  ![Package importer](https://raw.githubusercontent.com/AlmartDev/InsiderEngine/latest/Screenshots/ImportPackageWindow.png)
  
  ## What is a ```.insiderpack``` file?
  If you wanna create your own package, you can create a ```..insiderpack``` file to make insider engine now more stuff about your package. Look at ```demo-package.insiderpack``` to see the sample file. First line should be the package name, then the version, and a short description. Example:
  ```
demo-package
1.0.0
with demo package you can see how insider engine packages work
  ```
# Package version
 - 1.0.1
 - Oldest insider engine version tested in -> 0.6.0.1_build_4, [0.6]

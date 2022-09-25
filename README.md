# Sample insider engine package
Insider engine [0.6] -> [github page](https://github.com/almartdev/insiderengine)

#### Insider engine 0.5 doesnt have this feature yet. It'll be able on Insider engine version 0.6 or newer.

Insider engine demo package is a sample package to import into your projects and use tools that are not installed by default on your insider engine version. To import a project please take a look at all this stuff down here! You will need to have installed [git](https://git-scm.com/downloads) to import them.

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
the package will be imported to your project. So, to use the files into the package just include something like ```#include "../yourpackage/yourfile.h"``` and then you can use all the stuff into the package.

# Package version
 - 1.0.1
 - Oldest insider engine version tested in -> 0.6.0.1_build_4, [0.6]

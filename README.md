# _Sample project_

(See the README.md file in the upper level 'examples' directory for more information about examples.)

This is the simplest buildable example. The example is used by command `idf.py create-project`
that copies the project to user specified path and set it's name. For more information follow the [docs page](https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/build-system.html#start-a-new-project)



## How to use example
We encourage the users to use the example as a template for the new projects.
A recommended way is to follow the instructions on a [docs page](https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/build-system.html#start-a-new-project).

## Example folder contents

The project **sample_project** contains one source file in C language [main.c](main/main.c). The file is located in folder [main](main).

ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`
files that provide set of directives and instructions describing the project's source files and targets
(executable, library, or both). 

Below is short explanation of remaining files in the project folder.

```
├── CMakeLists.txt
├── main
│   ├── CMakeLists.txt
│   └── main.c
└── README.md                  This is the file you are currently reading
```
Additionally, the sample project contains Makefile and component.mk files, used for the legacy Make based build system. 
They are not used or needed when building with CMake and idf.py.

Fonctionnement du bouton / gestion button
Reveil suite à Appui
Sinon Eteint le bouton si pas d'utilisation pendant 30 minutes (avec bluetooth  enregistrer)

lancement Connection bluetooth si appui > 10 s
clignotement rapide lors de recherche bluethooth
allumé 100% si connecté à bluetooth

Appui court si alumé - Volume Down (photo) 

gestion Led
Si pas de Bluetooth - clignote lentement - Arret au bout de 5 min
Si bluetooth - Allumé
Si recherche bluethooth - cligote rapide - Arret au bout de 5 min

test de commit avec GITHUB

2eme test avec MaC

# Overview

Greyzen is a hacking tool designed for the game Grey Hack. It is capable of hacking into almost anything by scanning libraries and attempting overflows. As you use it, it keeps track of all known vulnerabilities in a generated file called vulndb. This file enables the program to be even faster in its tasks when it comes across a library it has seen before.

# Installation

To use Greyzen in-game, follow these steps:

1. Use the Greybel VS Extension in Visual Studio Code to build the main.src file.
2. This will create a build/installer.src file that can be copied over into CodeEditor.exe in-game.
3. Compile and run the installer.src file in a folder of your choosing to recreate the files on your in-game system.

# Usage

To use Greyzen, follow these steps:

1. Open the Grey Hack game.
2. Run the installer.src file in-game to install Greyzen.
3. Use the following command syntax to run Greyzen:

```
    greyzen [target-ip] [target-port]
    greyzen [target-ip]
    greyzen [path to lib file]
```

4. Greyzen will scan the libraries and attempt overflows to gain access to the target.
5. If vulnerabilities are found, Greyzen will generate a vulndb file to speed up future hacks.

# Contributing

If you wish to contribute to Greyzen, please follow these steps:

Fork the repository.
Create a new branch for your changes.
Make your changes and commit them.
Push your changes to your fork.
Submit a pull request.
License
Greyzen is licensed under the MIT License.

# DevEnvironment

Create a development environment for development of a javascript app, using Vagrant and VirtualBox.

## Instructions
(First make sure Vagrant and VirtualBox are installed on your computer)

__ 1. Git Clone__

Use the repository's link to clone the files onto your computer

__ 2. Vagrant up__

Enter into the repo on your Terminal command line, and execute the "vagrant up" command. This will execute the necessary commands and install the necessary gems to run the environment.

__ 3. Access the web app__

To access the app in your browser, type in the url "http://development.local:3000"

__ 4. Development __

In order to develop the app further, you must access it in the vagrant shell. To achieve this, once "vagrant up" has finished executing, execute the "vagrant ssh" command to enter the shell in Terminal. Once there, access the app folder using the project path "/app". Any changes made to the app folder in the vagrant shell will be made to the app folder in your original repo, and vice versa.
